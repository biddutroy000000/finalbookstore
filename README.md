# Final Bookstore

This project is a web-based Bookstore application built with Laravel (PHP framework) and Vite for asset bundling. It provides a platform to manage books and users, supporting CRUD operations and user authentication.

---

## 📺 Demo Video

<div align="center">
  
[![Book Store Laravel Demo](ss_link)](youtube_link)

</div>

> _Click the image above to watch the demo on YouTube!_


---

## Features

- **Book Management**: Add, edit, view, and delete books.
- **User Authentication**: Register, login, and manage users securely.
- **Database Integration**: Uses SQLite for development and testing.
- **MVC Architecture**: Clean separation of concerns using Laravel's MVC pattern.
- **Modern Frontend**: Asset bundling and hot reloading with Vite.
- **Testing**: Includes feature and unit tests for reliability.

## Project Structure

- `app/Models/` — Eloquent models for Book and User.
- `app/Http/Controllers/` — Controllers handling business logic.
- `database/migrations/` — Database schema migrations for users, books, and other tables.
- `resources/views/` — Blade templates for the UI.
- `routes/web.php` — Web routes for the application.
- `public/` — Publicly accessible files and entry point (`index.php`).
- `tests/` — Unit and feature tests.

## Getting Started

1. **Install dependencies**:
   ```sh
   composer install
   npm install
   ```
2. **Set up environment**:
   - Copy `.env.example` to `.env` and configure as needed.
   - Generate application key:
     ```sh
     php artisan key:generate
     ```
3. **Run migrations**:
   ```sh
   php artisan migrate
   ```
4. **Start development servers**:
   ```sh
   php artisan serve
   npm run dev
   ```
5. **Access the app**: Open [http://localhost:8000](http://localhost:8000) in your browser.

## Testing

Run tests with:
```sh
php artisan test
```

## License

This project is open-source and available under the MIT License.
