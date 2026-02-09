# Workshop Management System

A web-based Workshop Management System developed for Batik Tegalan to support daily business operations such as inventory management, sales transactions (POS), customer reservations, and educational content management.

This system is built using Laravel and focuses on providing a simple, reliable, and user-friendly interface for workshop administrators and staff.

## Features

* Inventory management (products & materials)
* Sales transactions (Point of Sale / POS)
* Customer reservations
* Educational content management
* Role-based access (Superadmin & Cashier)
* Admin dashboard for operational monitoring

## Tech Stack

* PHP
* Laravel
* Livewire
* Tailwind CSS
* MySQL

## Getting Started

### Prerequisites

Make sure you have installed:

* PHP 8+
* Composer
* Node.js & NPM
* MySQL

### Installation

1. Clone the repository

```bash
git clone https://github.com/carlosmarpaung08/workshop-management-system.git
cd workshop-management-system
```

2. Install dependencies

```bash
composer install
npm install
```

3. Copy environment file

```bash
cp .env.example .env
php artisan key:generate
```

4. Configure database in `.env`

```env
DB_DATABASE=workshop_db
DB_USERNAME=root
DB_PASSWORD=
```

5. Run migrations

```bash
php artisan migrate
```

6. Run the application

Open 4 terminals and run:

```bash
php artisan serve
npm run dev
php artisan queue:work
```

## Demo Accounts

### Superadmin

Email: [admin@batikworkshop.com](mailto:admin@batikworkshop.com)
Password: password

### Cashier

Email: [kasir@batikworkshop.com](mailto:kasir@batikworkshop.com)
Password: password

## Project Background

This project was developed as a real-world workshop management system for Batik Tegalan, aiming to digitalize manual processes and improve operational efficiency.

## Author

**Carlos Michael Marpaung** 
Software Engineer

* LinkedIn: [https://www.linkedin.com/in/carlos-michael-marpaung-836392267](https://www.linkedin.com/in/carlos-michael-marpaung-836392267)
* GitHub: [https://github.com/carlosmarpaung08](https://github.com/carlosmarpaung08)
