# Reverb API Next

A Laravel-based API project with real-time capabilities using Laravel Reverb.

## Prerequisites

- PHP >= 8.1
- Composer
- MySQL/PostgreSQL
- Node.js & NPM (for frontend assets if needed)

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd reverb-api-next
```

2. Install PHP dependencies:
```bash
composer install
```

3. Create and configure your environment file:
```bash
cp .env.example .env
```

4. Generate application key:
```bash
php artisan key:generate
```

5. Configure your database in the `.env` file:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

6. Run database migrations:
```bash
php artisan migrate
```

## Running the Application

1. Start the Laravel Reverb server:
```bash
php artisan reverb:start
```

2. Start the queue worker:
```bash
php artisan queue:work
```

3. Start the Laravel development server:
```bash
php artisan serve
```

## Authentication

To access the system, login using the following credentials:

- Role: Product Owner
- Email: [Your Product Owner Email]
- Password: [Your Password]

## Features

- Real-time updates using Laravel Reverb
- Queue-based job processing
- Role-based authentication
- RESTful API endpoints

## Contributing

Please read our contributing guidelines before submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
