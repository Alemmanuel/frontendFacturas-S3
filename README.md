# Frontend Facturas S3

A frontend web application for invoice management with AWS S3 integration.

## 📋 Overview

This project provides a user-friendly web interface for managing invoices (facturas) with cloud storage capabilities through Amazon S3. The application is built using vanilla HTML, CSS, and JavaScript, making it lightweight and easy to deploy.

## ✨ Features

- 📄 Invoice management interface
- ☁️ AWS S3 integration for document storage
- 📱 Responsive design
- 🎨 Clean and modern UI
- 🚀 Fast loading and lightweight

## 🛠️ Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling and responsive design
- **JavaScript** - Interactive functionality
- **AWS S3** - Cloud storage for invoice documents

## 📁 Project Structure

\`\`\`
frontend-facturas-s3/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
└── README.md          # Project documentation
\`\`\`

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- AWS S3 bucket (for full functionality)
- Basic knowledge of HTML/CSS/JavaScript

### Installation

1. **Clone the repository**
   \`\`\`bash
   git clone https://github.com/Alemmanuel/frontend-facturas-s3.git
   \`\`\`

2. **Navigate to the project directory**
   \`\`\`bash
   cd frontend-facturas-s3
   \`\`\`

3. **Open the application**
   - Simply open `index.html` in your web browser
   - Or serve it using a local web server:
   \`\`\`bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   \`\`\`

4. **Access the application**
   - Open your browser and go to `http://localhost:8000` (if using a local server)
   - Or directly open the `index.html` file

## ⚙️ Configuration

### AWS S3 Setup

To enable full S3 functionality, you'll need to:

1. Create an AWS S3 bucket
2. Configure CORS policy for your bucket
3. Set up appropriate IAM permissions
4. Update the S3 configuration in your JavaScript files

Example CORS configuration for S3:
\`\`\`json
[
    {
        "AllowedHeaders": ["*"],
        "AllowedMethods": ["GET", "PUT", "POST", "DELETE"],
        "AllowedOrigins": ["*"],
        "ExposeHeaders": []
    }
]
\`\`\`

## 🎯 Usage

1. **Open the application** in your web browser
2. **Upload invoices** using the provided interface
3. **Manage documents** stored in your S3 bucket
4. **View and organize** your invoice collection

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Alemmanuel**
- GitHub: [@Alemmanuel](https://github.com/Alemmanuel)

## 🐛 Issues

If you encounter any issues or have suggestions, please [open an issue](https://github.com/Alemmanuel/frontend-facturas-s3/issues) on GitHub.

## 📞 Support

For support and questions, please open an issue in the GitHub repository.

---

⭐ If you found this project helpful, please give it a star!
