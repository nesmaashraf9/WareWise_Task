
# Warewise Management System

## Overview
Snipe-IT is a powerful, open-source IT asset management system designed to help organizations track and manage their IT assets, licenses, accessories, and consumables. Built on the Laravel framework, it provides a comprehensive solution for IT asset lifecycle management, from procurement to retirement.

The system offers robust features for:
- Complete asset lifecycle management
- Software license tracking and compliance
- User and department management
- Location and status tracking
- Customizable reporting and auditing
- Barcode and QR code support
- API integration capabilities
- Role-based access control
- Audit and maintenance tracking
- Customizable checklists for asset verification

Snipe-IT is particularly valuable for:
- IT departments managing large asset inventories
- Organizations requiring compliance and audit trails
- Companies needing to track software licenses
- Educational institutions managing student/teacher devices
- Any organization requiring detailed asset accountability

The system is designed to be:
- User-friendly with an intuitive interface
- Highly customizable to meet specific needs
- Scalable for organizations of any size
- Secure with role-based permissions
- Accessible via web browsers and mobile devices

## Features

### Core Asset Management
- Asset tracking and management
- License management
- User management
- Department management
- Location tracking
- Accessory management
- Consumable tracking
- Component management

### Checklist System
The system includes a robust checklist feature that allows:
- Creation and management of custom checklists
- Multiple checklist types for different purposes
- Question-based verification system
- User tracking for all checklist operations
- Soft delete functionality for data recovery
- Hierarchical organization of checklists and questions

## Technical Stack
- **Framework**: Laravel 8.x
- **Database**: MySQL/PostgreSQL
- **Frontend**: Blade templates with Bootstrap
- **Authentication**: Laravel's built-in authentication system
- **Version Control**: Git

## Requirements
- PHP >= 7.4
- MySQL >= 5.7 or PostgreSQL >= 10.0
- Composer
- Node.js & NPM (for frontend assets)
- Web server (Apache/Nginx)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/snipe-it.git
cd snipe-it
```

2. Install PHP dependencies:
```bash
composer install
```

3. Install frontend dependencies:
```bash
npm install
```

4. Create environment file:
```bash
cp .env.example .env
```

5. Generate application key:
```bash
php artisan key:generate
```

6. Configure your database in `.env` file

7. Run migrations:
```bash
php artisan migrate
```

8. Build frontend assets:
```bash
npm run dev
```

## Configuration
- Configure your web server to point to the `public` directory
- Set up your database credentials in `.env`
- Configure mail settings for notifications
- Set up file storage for uploads

## Usage

### Asset Management
1. Create categories for your assets
2. Add manufacturers and suppliers
3. Create assets and assign them to users
4. Track asset status and history

### Checklist System
1. Create checklists for different purposes
2. Add questions to checklists
3. Use checklists for asset verification
4. Track checklist completion and history

## Security
- Role-based access control
- User action tracking
- Soft delete functionality
- Secure password hashing
- CSRF protection
- XSS prevention

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
This project is licensed under the AGPL v3 License - see the [LICENSE](LICENSE) file for details.

## Support
- Documentation: [Documentation Link]
- Issues: [GitHub Issues]
- Community: [Community Forum]

## Credits
- Original Snipe-IT Team
- Contributors and maintainers
- Open source community

## Acknowledgments
- Laravel Framework
- Bootstrap
- jQuery
- All other open source libraries used in this project
