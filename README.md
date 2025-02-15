# Orlenalycious Project

## 📌 Overview
Orlenalycious is a web-based platform designed to showcase and manage delicious brownie and pastry products. This project consists of a **React.js frontend** and an **Express.js backend** with email functionality.

## 🚀 Features
- Beautiful user interface built with **React.js**
- Backend powered by **Express.js**
- Email functionality using **Nodemailer**
- Concurrent execution for seamless development
- Environment variable validation for security

## 📂 Project Structure
```
Orlenalycious/
├── client/          # React frontend
├── server/          # Express backend
├── package.json     # Dependencies and scripts
├── .env.example     # Environment variables template
└── README.md        # Documentation
```

## 🔧 Installation
### Prerequisites
Ensure you have the following installed:
- **Node.js** (>= 14.x)
- **NPM** or **Yarn**

### Setup Steps
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/orlenalycious.git
   cd orlenalycious
   ```
2. **Install dependencies**
   ```sh
   npm install
   cd client && npm install
   ```
3. **Setup environment variables**
   - Copy `.env.example` and rename it to `.env`
   - Fill in your email credentials

4. **Run the application**
   ```sh
   npm run dev
   ```
   This will start both the **client** and **server** concurrently.

## 📫 API Endpoints
| Method | Endpoint      | Description               |
|--------|-------------|---------------------------|
| POST   | /send-email  | Send a contact form email |

## 🛠 Technologies Used
- **Frontend:** React.js, React Router
- **Backend:** Express.js, Nodemailer
- **Database:** MongoDB (if applicable in the future)
- **Styling:** CSS & Styled Components

## 👨‍💻 Contributing
1. **Fork the repository**
2. **Create a new branch** (`feature/new-feature`)
3. **Commit your changes**
4. **Push to the branch**
5. **Submit a Pull Request**

## 📜 License
This project is licensed under the **MIT License**.

## 📞 Contact
For any inquiries, reach out via email: **dsahousecompany@gmail.com**

