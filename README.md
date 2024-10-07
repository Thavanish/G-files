# G_Files

A modern, secure, and extensible file management system with a plugin architecture.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

## 🚀 Features

- 📁 Advanced file management with drag-and-drop support
- 🔌 Plugin system for extending functionality
- 🎥 Built-in media viewer (images, videos, PDF)
- 📝 File editor with syntax highlighting
- 🔍 Full-text search with metadata indexing
- 🔄 File versioning and history
- 🔐 Enterprise-grade security
- 🎨 Customizable themes
- 💾 Automated backups
- 📱 Responsive design for mobile devices

## 🛠️ Technology Stack

- **Backend**: Java 17, Spring Boot 3.x
- **Frontend**: React 18, Tailwind CSS
- **Database**: PostgreSQL
- **Security**: JWT, Spring Security
- **Testing**: JUnit, React Testing Library
- **Build Tools**: Maven, npm
- **CI/CD**: GitHub Actions

## 📋 Prerequisites

- Java 17 or higher
- Node.js 18 or higher
- PostgreSQL 13 or higher
- Maven 3.8+
- Git

## 🚀 Quick Start

1. Clone the repository
```bash
git clone https://github.com/your-username/G_Files.git
cd G_Files
```

2. Setup database
```bash
sudo -u postgres psql
CREATE DATABASE gfiles;
CREATE USER gfiles WITH ENCRYPTED PASSWORD 'your_password';
GRANT ALL PRIVILEGES ON DATABASE gfiles TO gfiles;
```

3. Configure application
```bash
cp .env.example .env
# Edit .env with your settings
```

4. Run the application
```bash
# Backend
cd backend
mvn spring-boot:run

# Frontend
cd frontend
npm install
npm start
```

Visit `http://localhost:3000` to access G_Files.

## 🔒 Security Features

- CSRF protection
- Rate limiting
- Anti-virus scanning
- XSS prevention
- Input validation
- JWT authentication
- Content Security Policy
- Encrypted storage

## 🔌 Plugin Development

See [Plugin Development Guide](docs/plugin-development.md) for creating custom plugins.

## 📚 Documentation

- [Installation Guide](docs/installation.md)
- [User Guide](docs/user-guide.md)
- [API Documentation](docs/api.md)
- [Security Guide](docs/security.md)
- [Contributing Guide](CONTRIBUTING.md)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
