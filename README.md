# Silk-Connect 🧵

**Silk-Connect** is a multilingual web application designed to bring silk-related products and supporting services together on a single platform. It aims to make silk saree information, Chawki centre availability, and medicine-related services more accessible to users.

## 🌟 Features

- **Silk Saree Marketplace:** Browse silk sarees with product names, prices, seller details, and contact information.
- **Chawki Centre Availability:** View and share information about Chawki centres, including locations, available quantities, and dates.
- **Medicine Availability:** Access medicine-related information and provide availability updates through the store-owner interface.
- **Multilingual Support:** Supports six languages—Kannada, Telugu, Tamil, Hindi, English, and Malayalam.
- **OTP-Based Login:** Includes a phone-number verification flow designed to integrate with an SMS OTP service.
- **User-Friendly Interface:** Provides a simple web interface for navigating the application's features.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Web page structure |
| CSS | Styling and responsive layout |
| JavaScript | Frontend functionality |
| Node.js | Backend runtime |
| Express.js | Backend API development |
| MSG91 | Planned SMS OTP integration |

## 🎯 Project Objective

The main objective of Silk-Connect is to provide a unified digital platform for silk-related products and services. It aims to help users access relevant information while allowing sellers and service providers to share product and availability details.

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed
- A web browser
- MSG91 credentials and an approved SMS template for real OTP delivery

### Installation

1. Clone or download the project repository.
2. Open the project folder in your terminal.
3. Navigate to the backend directory:

   ```bash
   cd backend
   ```

4. Install the backend dependencies:

   ```bash
   npm install
   ```

5. Configure the required environment variables in the backend `.env` file.
6. Start the backend server:

   ```bash
   node server.js
   ```

7. Open the frontend HTML file in your browser.

## 🔐 OTP Configuration

The application includes an OTP login flow intended to communicate with the backend API. Real SMS delivery requires valid SMS provider credentials and the appropriate approved template configuration.

For development and demonstrations, a clearly labelled demo authentication mode may be used if implemented and tested. Demo mode should not be used as real phone-number verification in production.

## 🔮 Future Enhancements

- Complete production-ready OTP authentication
- Integrate a database for persistent product and user data
- Improve seller and service-provider management
- Add search and filtering capabilities
- Deploy the application for public access

## 👩‍💻 Project Status

**Status:** Under Development

Silk-Connect is being developed as a web application to improve access to silk-related products and services through a unified, multilingual interface.

---

*Silk-Connect — Connecting silk products, services, and people through technology.*
