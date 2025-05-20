# Coffee Shop Challenge

A Python object-oriented programming project simulating a coffee shop domain with customers, coffees, and orders.

## Domain Model

This project implements a coffee shop domain with three main models:
- `Customer`: Represents a person who orders coffee
- `Coffee`: Represents a type of coffee that can be ordered
- `Order`: Represents a single purchase of a coffee by a customer

The relationships between these models are:
- A `Coffee` has many `Orders`
- A `Customer` has many `Orders`
- An `Order` belongs to a `Customer` and to a `Coffee`
- `Coffee` - `Customer` is a many-to-many relationship

## Setup Instructions

1. Clone the repository
