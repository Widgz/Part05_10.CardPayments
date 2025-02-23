# This is the solution for the exercise "Card payments" from the Part 5 (item 4. Objects and references) of MOOC's Java Programming I from the University of Helsinki.


## Development of a payment system for a cafeteria

### Overview

This project is a simple payment system for a cafeteria, allowing customers to pay for meals using either cash or a payment card. The system consists of two main components:

### 1. PaymentCard ("Dumb Card")

A basic payment card that only tracks the balance.

- Methods to:

  - Check the balance.

  - Add money to the card.

  - Attempt to make a payment (only if funds are sufficient).

  The card does not store prices or handle transaction logic.


### 2. PaymentTerminal

Handles payments for meals, either in cash or via a PaymentCard.

Supports two types of meals:

* Affordable meal: €2.50

* Hearty meal: €4.30

  - Payment methods:

    - Cash payments: If sufficient funds are provided, the terminal registers the payment and returns change.

    - Card payments: The amount is deducted from the card if the balance is sufficient.

    - Allows adding money to a PaymentCard, increasing both the card balance and the terminal's cash register.

    - Tracks the number of meals sold.

Features

- Cash and card payments for meals.

- Change calculation for cash transactions.

- Balance validation for card transactions.

- Money loading feature for payment cards.

- Tracking of total sales and terminal cash balance.
