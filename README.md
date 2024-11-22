# NexaCRM
A powerful and dynamic CRM (Customer Relationship Management) Dashboard built with PHP, Bootstrap, and JavaScript. Designed for managing contacts, companies, industries, and users efficiently, this project also includes integrated theming options, dark mode support, and custom notifications.

### Features

## Core Modules
- Dashboard: An overview of key metrics, recent activities, and upcoming events.
- Contacts Management: Add, edit, and delete contacts, with search and pagination support.
- Companies Management: Manage associated companies, their contacts, and outreach data.
- Message Logs: Track communication with contacts, including templates for recurring messages.
- Users Management: Manage users, roles, and permissions.

## Additional Features
- Theme Customization:
Light, Dark, and Monochrome modes.
- Sidebar theming options.
-RTL and LTR layout support.
- Dynamic Notifications:
- Real-time notifications pulled from the activity log.
- Badge updates and dropdown listing.
- Responsive Design: Fully responsive for desktop and mobile views.
- Action Logs: Tracks and logs all user activities for audit purposes.

# Installation

##Prerequisites
- Web Server: Apache/Nginx
- PHP: Version 7.4 or higher
- MySQL: For database management
- Composer: To manage dependencies
-Node.js: Optional, for compiling assets (e.g., SCSS, JavaScript)

#Setup
- Clone the repository:

`
git clone https://github.com/leb_toki/crm-dashboard.git
`

`
cd crm-dashboard
`

- Install PHP dependencies:

` 
composer install
`

- Install front-end dependencies (if applicable):

`
npm install
`

- Create a .env file for environment variables:

`
cp .env.example .env
`
- Configure the .env file with your database credentials:

`
DB_HOST=127.0.0.1
DB_DATABASE=crm_dashboard
DB_USERNAME=root
DB_PASSWORD=your_password
`

- Access the app in your browser:

`
http://localhost/crm
`

# Usage
- Admin Dashboard

The admin panel provides comprehensive control over the CRM, allowing you to:

- View notifications, manage users and roles.
- Switch themes and adjust layout settings dynamically.
- View real-time stats about contacts, companies, and industries.

# Modules
- Contacts: Add, edit, and delete contacts. Assign contacts to companies and industries.

- Companies: Manage associated industries and contacts.
- View outreach statistics and message logs.
- Users Add users with specific roles (Admin, Manager, Sales, Support).Change user settings, profile, and password.

- Themes: Switch between Light, Dark, and Monochrome modes.

- Customize sidebar and header styles.

Screenshots

Dashboard Overview

Dark Mode

Contacts Module

## Folder Structure

crm-dashboard/
├── assets/                # Static assets (CSS, JS, images, fonts)
│   ├── css/               # Stylesheets (e.g., Bootstrap, custom CSS)
│   ├── js/                # JavaScript files (e.g., custom scripts)
│   ├── images/            # Image assets for the app
│   └── fonts/             # Web fonts used in the application
├── includes/              # Reusable PHP components
│   ├── helpers/           # Helper functions for reusability
│   ├── connections.php    # Database connection setup
│   └── sessions.php       # Session management scripts
├── dashboard/             # Core dashboard files
│   ├── index.php          # Main dashboard page
│   ├── widgets/           # Dynamic widgets for the dashboard
│   └── partials/          # Navbar, sidebar, and common UI elements
├── modules/               # Individual modules (contacts, companies, etc.)
│   ├── contacts/          # Contact management module
│   ├── companies/         # Company management module
│   └── users/             # User and role management module
├── config/                # Configuration files
│   └── config.php         # Application-wide settings
├── migrations/            # Database migrations
│   ├── create_users_table.php  # Migration script for users table
│   ├── create_contacts_table.php  # Migration script for contacts table
│   └── create_roles_table.php    # Migration script for roles table
├── public/                # Publicly accessible files
│   ├── index.php          # Entry point for the application
│   ├── .htaccess          # Apache configurations (if applicable)
│   └── uploads/           # Directory for uploaded files (e.g., images)
├── README.md              # Documentation for the project
└── .env.example           # Example environment configuration file


# Contributing
Contributions are welcome! Please follow these steps:

- Fork the repository.
- Create a feature branch:
- git checkout -b feature-name
- Commit your changes:

`
git commit -m "Add feature description"
`

- Push to the branch:
- git push origin feature-name
- Create a pull request.

# License
This project is licensed under the MIT License.

# Credits
- Developed by Tarek Tarabichi
- Icons by Feather Icons
- Framework: Bootstrap 5

# Contact
For questions or suggestions, contact us at:

- Website: 2tinteractive.com
