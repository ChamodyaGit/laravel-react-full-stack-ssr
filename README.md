# Laravel React Full Stack SSR

This is a full-stack Laravel and React project using Laravel Breeze with Inertia, Server-Side Rendering (SSR), TypeScript, and Dark Mode enabled.

## Installation

### Prerequisites
Ensure you have the following installed:
- PHP (>=8.1)
- Composer
- Node.js & npm
- MySQL (or another preferred database)

### Steps

1. **Install Laravel Installer Globally:**
   ```sh
   composer global require laravel/installer
   ```

2. **Create a New Laravel Project with Breeze & React:**
   ```sh
   laravel new laravel-react-full-stack-ssr
   cd laravel-react-full-stack-ssr
   ```

3. **Install Laravel Breeze with React & SSR:**
   ```sh
   php artisan breeze:install react --dark --ssr --typescript
   ```

4. **Install Dependencies:**
   ```sh
   composer install
   npm install
   ```

5. **Set Up Environment Variables:**
   ```sh
   cp .env.example .env
   ```
   Update `.env` with database credentials.

6. **Run Migrations:**
   ```sh
   php artisan migrate
   ```

7. **Build Frontend Assets:**
   ```sh
   npm run build
   ```

8. **Start Vite for Development:**
   ```sh
   npm run dev
   ```

9. **Start Laravel Development Server:**
   ```sh
   php artisan serve
   ```

