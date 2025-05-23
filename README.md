# Tasklisk Management

A simple yet powerful task list management application built with **Laravel 12** and **React**. This project offers a modern full-stack solution for managing tasks efficiently, combining the robustness of Laravel for the backend with the flexibility of React for the frontend.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Task Management**: Create, read, update, and delete tasks seamlessly.
- **Modern UI**: Responsive and intuitive user interface built with React.
- **API Integration**: RESTful API endpoints powered by Laravel.
- **State Management**: Efficient state handling using React hooks.
- **Modular Architecture**: Clean and maintainable codebase with separation of concerns.

## Tech Stack

**Frontend**:
- React
- TypeScript
- Vite
- Tailwind CSS

**Backend**:
- Laravel 12
- PHP
- MySQL (or other supported DB)

**Tooling**:
- Composer
- NPM
- Prettier
- ESLint

## Getting Started

### Prerequisites

Make sure you have the following installed:

- PHP >= 8.1
- Composer
- Node.js >= 16.x
- NPM
- MySQL (or compatible database)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mrhanafi/tasklisk-management.git
   cd tasklisk-management
   ```

2. Set up the backend:

   ```bash
   composer install
   cp .env.example .env
   php artisan key:generate
   ```

   Configure your `.env` file with your database credentials.

3. Set up the frontend:

   ```bash
   npm install
   ```

### Running the Application

1. Start the Laravel server:

   ```bash
   php artisan serve
   ```

2. Start the Vite development server:

   ```bash
   npm run dev
   ```

Access the app at `http://localhost:3000` or the port configured in Vite.

## Project Structure

```
tasklisk-management/
├── app/                 # Laravel application code
├── bootstrap/           # Laravel bootstrap files
├── config/              # Configuration files
├── database/            # Migrations and seeders
├── public/              # Public files
├── resources/           # Blade templates and frontend assets
├── routes/              # Route definitions
├── storage/             # Logs and compiled files
├── tests/               # Automated tests
├── .env.example         # Example env config
├── composer.json        # PHP dependencies
├── package.json         # Node.js dependencies
├── tsconfig.json        # TypeScript config
├── vite.config.ts       # Vite config
└── ...
```

## Contributing

Contributions are welcome!

1. Fork the repo.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. Make your changes and commit:

   ```bash
   git commit -m "Add some feature"
   ```

4. Push to your branch:

   ```bash
   git push origin feature/YourFeatureName
   ```

5. Open a Pull Request.

Ensure your code follows the style guide and passes tests.

## License

This project is licensed under the [MIT License](LICENSE).
