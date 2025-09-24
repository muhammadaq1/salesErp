# SalesERP v9.8

A comprehensive ERP (Enterprise Resource Planning) system built with PHP CodeIgniter framework for small to medium businesses.

## Features

- Sales Management
- Purchase Management
- Inventory Management
- Customer Management
- Supplier Management
- Accounting & Financial Reports
- Multi-user Access Control
- Invoice Generation
- Stock Management
- Real-time Reporting

## System Requirements

- PHP 8.0 or higher
- MySQL 5.7 or higher
- Nginx or Apache web server
- PHP Extensions: mysqli, mbstring, gd, curl, zip, xml

## Installation

### Automated Deployment

This project is configured for automatic deployment to VPS using GitHub Actions.

1. Push code to the main branch
2. GitHub Actions will automatically deploy to VPS at: `45.61.140.213`

### Manual Installation

1. Clone the repository
2. Copy `application/config/database.example.php` to `application/config/database.php`
3. Configure your database settings
4. Import the database from `install/sql/install.sql`
5. Set proper file permissions for writable directories

## Default Login

After installation, access the system at your domain and use the credentials created during installation.

## Configuration

### Database Configuration

Edit `application/config/database.php` with your database credentials:

```php
$db['default'] = array(
    'hostname' => 'localhost',
    'username' => 'your_username',
    'password' => 'your_password',
    'database' => 'your_database_name',
    'dbdriver' => 'mysqli',
);
```

### Web Server Configuration

Ensure URL rewriting is enabled for clean URLs.

## License

This software requires a valid purchase license from CodeCanyon.

## Support

For support and documentation, visit the project's support forum or contact the developers.

<!-- Deployment trigger: 2025-09-24 22:09 -->
