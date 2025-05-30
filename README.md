# PayStell Backend 💫

> Backend for a payment system for merchants powered by the Stellar network

PayStell Backend is the server-side component of a payment solution that enables merchants to accept payments on the Stellar network easily and securely. It leverages Stellar blockchain capabilities to offer fast, cost-effective, and reliable transactions.

## 🚀 Features

- Secure and scalable API for payment processing
- Real-time transaction monitoring
- Support for multiple Stellar assets
- Integration with frontend and admin dashboard
- Minimal transaction fees
- Robust data validation and error handling
- Integration with local and online payment systems

## ⚙️ Project Structure

```
paystell-backend/
├── src/ # Project source code
│ ├── config/ # Project configurations
│ ├── controllers/ # Controllers to handle requests
│ ├── entities/ # Database entities
│ ├── middlewares/ # Middlewares to process requests
│ ├── models/ # Data models
│ ├── routes/ # API routes
│ ├── services/ # Business logic and services
│ ├── tests/ # Project tests
│ ├── types/ # TypeScript types and interfaces
│ ├── utils/ # Utility functions and helpers
│ ├── validators/ # Data validators
│ ├── app.ts # Application configuration
│ └── index.ts # Application entry point
├── .env # Environment variables
├── .gitignore # File to ignore files in Git
├── jest.config.js # Jest configuration for testing
├── LICENSE # Project license
├── package-lock.json # Dependency version lock
├── package.json # Project metadata and dependencies
└── tsconfig.json # TypeScript configuration
```

## 🛠️ Technologies

- Backend: Node.js, TypeScript, Express
- Database: PostgreSQL
- Testing: Jest
- API Documentation: Swagger/OpenAPI

## 🏁 Quick Start

```bash
# Clone the repository
git clone https://github.com/PayStell/paystell-backend.git

# Install dependencies
cd paystell-backend
npm install

# Set up environment variables
cp .env.example .env

# Start the development server
npm start
```

## 📬 How to Import the Postman Collection

To import the Postman collection (in .json or .postman_collection format), follow these steps:

1. Open Postman.
2. Click on "Import" in the top left corner of the Postman window.
3. Select the file you want to import from your computer. You can drag and drop the `.json` file or search for it on your system.
4. Postman will load your file and add it to your collection, displaying the configured endpoints.

## 🤝 Contributing

Contributions are welcome! Please read our [CONTRIBUTING GUIDE](https://github.com/PayStell/paystell-website/blob/main/CONTRIBUTORS_GUIDE.md) before submitting PRs.

1. Fork the project
2. Create your feature branch (`git checkout -b feat/AmazingFeature`)
3. Commit your changes (`git commit -m 'feat: some amazing feature'`)
4. Push to the branch (`git push origin feat/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💬 Community

- [Telegram](https://t.me/paystelldev)
- [x.com](https://x.com/paystell)

## 🧑‍💻 Authors
- [MPSxDev](https://github.com/MPSxDev)
- Contributions from the open-source community and OnlyDust

## ⭐ Support the Project

If you find PayStell Backend useful, please consider:
- Starring the repository
- Sharing the project
