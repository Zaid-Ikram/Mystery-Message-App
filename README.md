# Mystery-Message-App

**Mystery-Message-App** is a full-stack web application for sending anonymous messages securely. It enables users to send messages in incognito mode using a unique link, with AI-powered message suggestions and email authentication for added security.

---

## 🚀 Features
- **Anonymous Messaging**: Send messages without revealing your identity.
- **Incognito Mode**: Generate unique links to share messages securely.
- **AI Suggestions**: AI-powered message suggestions for a better experience.
- **Email Authentication**: Secure user verification with email.
- **User Settings**: Manage message visibility and notifications.

---

## 🛠️ Tech Stack
### Frontend
- **React.js**
- **Tailwind CSS**
- **JavaScript/TypeScript**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB** (via **Mongoose**)

### Other Tools
- **Next Auth** for authentication.
- **Nodemailer** for email verification.
- **OpenAI API** (for AI-powered suggestions).

---

## 📦 Installation and Setup

### Prerequisites
1. **Node.js** (v14 or above)
2. **MongoDB** (local or cloud-based, e.g., MongoDB Atlas)
3. **Git**

### Steps to Set Up Locally
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Zaid-Ikram/Mystery-Message-App.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Mystery-Message-App
   ```

3. **Install dependencies**:
   - **Backend**:
     ```bash
     cd backend
     npm install
     ```
   - **Frontend**:
     ```bash
     cd ../frontend
     npm install
     ```

4. **Set up environment variables**:
   - Create a `.env` file in both `frontend` and `backend` folders.
   - Use `.env.example` as a guide for required keys (e.g., `MONGO_URI`, `JWT_SECRET`, `EMAIL_SERVICE`, etc.).

5. **Run the application**:
   - **Backend**:
     ```bash
     cd backend
     npm start
     ```
   - **Frontend**:
     ```bash
     cd frontend
     npm start
     ```

6. **Access the app**:
   - Open your browser and navigate to `http://localhost:3000`.

---

## 🌟 Usage
1. **Sign Up**: Create an account using email authentication.
2. **Generate Links**: Use your unique link to share with others.
3. **Send Messages**: Send anonymous messages via the generated link.
4. **Manage Messages**: View and manage messages in your dashboard.

---

## 🤝 Contributing
We welcome contributions! Follow these steps to contribute:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/your-feature
   ```
3. **Make changes and commit**:
   ```bash
   git commit -m "Add your feature"
   ```
4. **Push to your branch**:
   ```bash
   git push origin feature/your-feature
   ```
5. **Create a pull request**.

---

## 📝 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements
- **React.js** for building the user interface.
- **Node.js** and **Express.js** for backend development.
- **MongoDB** for database management.
- **Nodemailer** for email authentication.
- **OpenAI API** for AI-powered message suggestions.
   ```

Let me know if you need more help! 🚀
