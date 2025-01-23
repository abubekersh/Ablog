# **Blog Website**

## **Description**  
A simple and user-friendly blog website built using Laravel. This application allows users to register, log in, and manage blog posts, providing basic CRUD (Create, Read, Update, Delete) functionality for posts.

---

## **Features**
- User registration and login system.
- Create, edit, delete, and view blog posts.
- Responsive design using Blade templates.
- Basic category management (optional).
- Search functionality (optional).

---

## **Technologies Used**
- **Backend**: Laravel 10, PHP 8.2
- **Frontend**: Blade templates, HTML, CSS
- **Database**: MySQL (or SQLite for development)
- **Tools**: Composer, Artisan CLI

---

## **Setup Instructions**

### Prerequisites
1. Install [PHP](https://www.php.net/downloads) (v8.2 or higher).  
2. Install [Composer](https://getcomposer.org/).  
3. Install [MySQL](https://dev.mysql.com/downloads/) or use an SQLite database.  
4. Install [Node.js](https://nodejs.org/) for front-end dependencies.

### Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/abubekersh/blog-website.git
   cd blog-website
2. Install dependencies:
	```bash
	composer install
	npm install && npm run dev
3. Copy the .env.example file to .env:
	```bash
	cp .env.example .env
4. Generate an application key:
	```bash
	php artisan key:generate
5. Set up your database in the .env file:
	```env
	DB_CONNECTION=mysql
	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE=blog_db
	DB_USERNAME=root
	DB_PASSWORD=yourpassword
6. Run migrations to set up database tables:
	```bash
	php artisan migrate
7. Serve the application locally:
	```bash
	php artisan serve
8. Optional: Seed the Database
	If you create seeders for dummy data, add this step:

	```bash
	php artisan db:seed
### Screenshots
(Add screenshots of your homepage, blog post list, and other features once you finish building.)

### Future Enhancements
- Implement an admin panel for user and post management.
- Add advanced search filters (e.g., by category or date).
- Enable file uploads for blog post images.
### License
