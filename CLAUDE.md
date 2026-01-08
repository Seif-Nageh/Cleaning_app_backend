# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Backend API for a cleaning application. This repository is configured for Laravel PHP framework.

## Project Status

This is a fresh repository. Laravel needs to be initialized before development can begin.

## Initial Setup (if not yet done)

```bash
# Install Laravel via Composer
composer create-project laravel/laravel .

# Copy environment file and generate application key
cp .env.example .env
php artisan key:generate

# Install dependencies
composer install
```

## Common Commands

### Development Server
```bash
# Start Laravel development server
php artisan serve

# Start on specific port
php artisan serve --port=8080
```

### Database
```bash
# Run migrations
php artisan migrate

# Rollback migrations
php artisan migrate:rollback

# Fresh migration (drops all tables)
php artisan migrate:fresh

# Run seeders
php artisan db:seed
```

### Testing
```bash
# Run all tests
php artisan test

# Run specific test file
php artisan test --filter=TestClassName

# Run tests with coverage
php artisan test --coverage
```

### Code Quality
```bash
# Clear all caches
php artisan optimize:clear

# Cache configuration
php artisan config:cache

# Cache routes
php artisan route:cache
```

## Architecture Notes

To be documented once the application structure is established.
