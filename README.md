# Railway Booking System

The Railway Booking System is a Python module that allows users to search for available trains, check fares, book train tickets, and manage their bookings. This module interacts with a MySQL database to store and retrieve train-related information and user bookings.

## Features

- **AvailableTrains():** Allows users to search for available trains based on the source and destination stations.
- **CheckFare():** Calculates the fare for a train journey based on the distance between the source and destination stations.
- **ShowBookings():** Displays the bookings made by a user.
- **BookTrain():** Enables users to book a train ticket.
- **CancelBooking():** Allows users to cancel a booked ticket.

## Installation

To use the Railway Booking System module, follow these steps:

1. Make sure you have Python installed on your system (version 3.0 or above).
2. Install the required dependencies by running the following command:
   ```shell
   pip install mysql-connector-python

## Usage
### Available Functions
The Railway Booking System module provides the following functions:

AvailableTrains(): Displays a list of available trains based on the user's source and destination stations.
CheckFare(): Calculates the fare for a train journey based on the distance between the source and destination stations.
ShowBookings(): Shows the bookings made by a user.
BookTrain(): Allows a user to book a train ticket.
CancelBooking(): Enables a user to cancel a booked ticket.
