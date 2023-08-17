# Asset Management System

This is a web-based Asset Management System built using Laravel.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)


## About

The Asset Management System is a web application designed to help manage assets and purchase invoices. It allows users to add, edit, and delete assets, as well as create purchase invoices and track inventory quantities.

## Features

- Add, edit, and delete assets
- Create and manage purchase invoices
- Automatically updates asset quantities based on purchase invoices
- User authentication and access control

## Getting Started

Follow these steps to get the Asset Management System up and running on your local machine:

1. Clone this repository: `git clone https://github.com/your-username/asset-management-system.git`
2. Navigate to the project directory: `cd asset-management-system`
3. Install Composer dependencies: `composer install`
4. Create a copy of the `.env.example` file and name it `.env`: `cp .env.example .env`
5. Generate the application key: `php artisan key:generate`
6. Configure your database settings in the `.env` file
7. Run database migrations: `php artisan migrate`
8. Start the development server: `php artisan serve`

## Usage

1. Access the application by opening your browser and navigating to `http://localhost:8000`
2. Register a new account or log in using existing credentials
3. Add assets through the "Add Asset" page
4. Create purchase invoices through the "Add Purchase Invoice" page
5. View and manage assets and purchase invoices on their respective index pages

