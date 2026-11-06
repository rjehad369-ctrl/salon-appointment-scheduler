# Salon Appointment Scheduler 💇‍♀️💅

A interactive command-line Bash script that interfaces with a PostgreSQL database to manage salon services, register customers, and schedule appointments. This project is built as part of the **freeCodeCamp Relational Database Certification**.

## ✨ Features

- **Dynamic Service Menu:** Displays a numbered list of available salon services fetched directly from the database.
- **Error Handling:** Automatically detects invalid service choices, displays an error message, and re-presents the service menu.
- **Customer Management:** Checks customer phone numbers; if a customer doesn't exist, it collects their name and registers them automatically.
- **Appointment Booking:** Seamlessly links customers and services to schedule appointments at a custom user-defined time.
- **Confirmation Messages:** Outputs precise, well-formatted confirmation messages upon successful booking.

## 🛠️ Technologies Used

- **Bash Scripting (Shell)**
- **PostgreSQL**
- **Git & GitHub**

## 🗄️ Database Schema

The PostgreSQL database (`salon`) consists of three main tables:
1. **`services`**: Stores salon offerings (`service_id`, `name`).
2. **`customers`**: Stores client contact details (`customer_id`, `phone`, `name`).
3. **`appointments`**: Relates customers to services and times (`appointment_id`, `customer_id`, `service_id`, `time`).

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/rjehad369-ctrl/salon-appointment-scheduler.git](https://github.com/rjehad369-ctrl/salon-appointment-scheduler.git)
   cd salon-appointment-scheduler
