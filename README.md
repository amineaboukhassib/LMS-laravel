# LMS Laravel

A modern Learning Management System (LMS) starter template built with the **Laravel** framework, featuring a high-performance **React** frontend powered by **Inertia.js** and styled with **Tailwind CSS**.

---

## 🚀 Features

- **Authentication System**: Built-in authentication powered by Laravel Fortify.
- **Passkey Support**: Secure, passwordless login using WebAuthn/Passkeys.
- **Two-Factor Authentication (2FA)**: Advanced security setup with recovery codes.
- **Modern Dashboard**: Responsive navigation and workspace layouts using Radix UI primitives.
- **Appearance & Theme Toggles**: Support for light, dark, and system appearance modes.
- **Developer Workflows**: Integrated Vite dev server, TypeScript checking, Pint PHP linting, and ESLint configurations.

---

## 🛠️ Tech Stack

- **Backend**: PHP 8.3+, Laravel 13.x
- **Frontend**: React 19.x, TypeScript, Inertia.js (React adapter)
- **Styling**: Tailwind CSS v4.0
- **UI Components**: Radix UI Primitives (Avatar, Dialog, Dropdown Menu, Select, Separator, Sidebar, Tooltip)
- **Icons**: Lucide React

---

## 📦 Prerequisites

Before setting up the project, make sure you have the following installed:
- PHP 8.3 or higher
- Composer
- Node.js & npm
- A database server (MySQL / MariaDB or SQLite)

---

## 🔧 Installation & Setup

1. **Clone the repository** (if not already done):
   ```bash
   git clone https://github.com/amineaboukhassib/LMS-laravel.git
   cd LMS-laravel
   ```

2. **Run the setup wizard**:
   This composer script automatically installs dependencies, configures the environment file, generates application keys, runs database migrations, and builds the production frontend assets:
   ```bash
   composer run setup
   ```

3. **Configure Database (if needed)**:
   Open the `.env` file and configure your database settings:
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=lms_laravel
   DB_USERNAME=root
   DB_PASSWORD=
   ```

---

## 💻 Development Workflow

Start the backend server, queue listener, and Vite frontend development server concurrently with a single command:

```bash
composer run dev
```

The application will be accessible at:
- **Web App**: [http://localhost:8000](http://localhost:8000)
- **Vite Hot-Reload Server**: [http://localhost:5173](http://localhost:5173)

### Available Scripts

- **Lint Backend**: `composer run lint`
- **Lint Frontend**: `npm run lint`
- **TypeScript Check**: `npm run types:check`
- **Run Tests**: `composer run test`
- **Build for Production**: `npm run build`

---

## 📄 License

This project is open-sourced software licensed under the [MIT license](LICENSE).
