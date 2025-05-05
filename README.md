# MSE License Portal

A modern web application for managing business licenses built with **Laravel** and **Tailwind CSS**. The system provides a seamless and responsive experience with advanced license tracking and user role management Website.

## 🔥 Features

- 🎨 Modern UI with Tailwind CSS  
- 🌓 Dark/Light mode with system preference detection  
- 📱 Responsive design for all screen sizes  
- 🔍 Advanced search functionality  
- 📋 Complete CRUD for licenses  
- 🔔 SweetAlert2 notifications  
- 🎭 Role-based access control (RBAC)  
- 📊 License status tracking and updates  

## ✅ Prerequisites

Before you begin, ensure you have the following installed:

- PHP >= 8.2  
- Composer  
- Node.js & NPM  
- MySQL  
- Git  

## 🚀 Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/mse-license-portal.git
cd mse-license-portal
```

### 2. Install PHP & JS Dependencies

```bash
composer install
npm install
```

### 3. Environment Setup

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Configure Database

Open the `.env` file and update these lines:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=mse_license_portal
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

### 5. Database Migration & Seeding

```bash
php artisan migrate
# (Optional) Seed database with sample data
php artisan db:seed
```

### 6. Start Development Servers

```bash
php artisan serve
```

Visit [http://localhost:8000](http://localhost:8000) in your browser.

In a new terminal:

```bash
npm run dev
```

## ⚙️ Development Commands

### Common Artisan Commands

```bash
# Create new migration
php artisan make:migration create_table_name_table

# Create new controller
php artisan make:controller ControllerName

# Clear application cache
php artisan cache:clear
php artisan config:clear
php artisan view:clear

# Run tests
php artisan test
```

## 🗂️ Project Structure

```
mse-license-portal/
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   └── Middleware/
│   └── Models/
├── database/
│   ├── migrations/
│   └── seeders/
├── resources/
│   ├── views/
│   │   └── licenses/
│   └── css/
├── routes/
└── public/
```

## 🧪 Build Commands

### Development

```bash
npm run dev
```

### Production

```bash
npm run build
```

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository  
2. Create your feature branch:  
   ```bash
   git checkout -b feature/AmazingFeature
   ```  
3. Commit your changes:  
   ```bash
   git commit -m "Add some Amazing Feature"
   ```  
4. Push to the branch:  
   ```bash
   git push origin feature/AmazingFeature
   ```  
5. Open a Pull Request  

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

## 📬 Support

For support, contact [https://www.linkedin.com/in/abhinandan-sah/](https://www.linkedin.com/in/abhinandan-sah/m) or create an issue in the [repository](https://github.com/Abhinandan-Sah/mse-license-portal/issues).

## 👥 Authors

- **Name** – [@Abhinandan-Sah](https://github.com/Abhinandan-Sah)

## 🙏 Acknowledgments

- Laravel Team  
- Tailwind CSS Team  
- All contributors  

