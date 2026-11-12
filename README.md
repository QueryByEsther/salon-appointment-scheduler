
# Salon Appointment Scheduler

## Overview

A command-line salon appointment scheduling system built using PostgreSQL and Bash.

The application allows customers to view available salon services, book appointments, and register their details. Returning customers are identified using their phone numbers.

## Technologies Used

- PostgreSQL
- SQL
- Bash Scripting
- Relational Database Design

## Database Structure

The project uses three related tables:

- **customers:** Stores customer names and phone numbers.
- **services:** Stores the salon's available services.
- **appointments:** Stores appointment details and links customers to services.

## Features

- Displays available salon services.
- Validates service selections.
- Registers new customers.
- Recognizes returning customers using phone numbers.
- Records appointments.
- Connects records using foreign keys.

## Skills Demonstrated

- Database creation and management
- Primary and foreign keys
- SQL queries and data insertion
- Relational database design
- Bash scripting
- Database integration with shell scripts

## Project Files

| File | Description |
|---|---|
| `salon.sh` | Bash appointment scheduler |
| `salon.sql` | PostgreSQL database backup |

## Author

Esther Murigi

GitHub: [QueryByEsther](https://github.com/QueryByEsther)
