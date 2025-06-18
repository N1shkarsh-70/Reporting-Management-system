
# 🛠️ Toll Plaza Reporting Management System

## 📌 What is Reporting Management System?

The **Toll Plaza Reporting Management System** is a role-based web application built to streamline issue reporting and management within toll plaza operations. It allows **Site Engineers** to report real-time issues occurring at toll plazas and enables **Admins** to manage projects, assign project incharges, monitor engineer activity, and generate insightful reports.

This system enhances transparency, coordination, and operational efficiency between field engineers and administration.

---

## 🌐 Live Preview

🔗 [Live Demo](#) [ https://reporting-management-system-two.vercel.app/]

🧪 Use the following credentials to test:
```
Admin Login:
Email: nishkarsh12@gmail.com
Password: nishkarsh@123

```

---

## 🚀 Key Features

- 🔐 **Role-Based Access**: Separate dashboards for Admins, Project Incharges, and Site Engineers.
- 🛠 **Issue Reporting**: Site Engineers can log real-time technical issues with detailed descriptions.
- 📁 **Project & Plaza Management**: Admins can add/manage projects and plazas.
- 👷 **Engineer Activity Tracking**: Monitor site engineer submissions and attendance.
- 🗂 **Report Generation**: Generate detailed reports for maintenance and performance evaluation.
- 📊 **User-Friendly UI**: Sidebar navigation for intuitive access to all modules.

---

## 🖼️ Frontend UI Preview

### 🧭 Sidebar Navigation
![Sidebar Navigation](./screenshots/sidebar.png)

*(Add more screenshots as needed in a `screenshots/` folder)*

---

## 🧰 Tech Stack Used

### **Frontend**:
- ⚛️ React.js
- 💨 Tailwind CSS
- 🌐 Axios for API calls
- 🧭 React Router

### **Backend**:
- 🟢 Node.js
- 🌐 Express.js
- 🔐 JWT for Authentication
- 🧾 MongoDB (Mongoose)

---

## 🛠 Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/your-username/toll-reporting-system.git
```

2. Install dependencies for both frontend and backend:
```bash
cd client
npm install

cd ../server
npm install
```

3. Add `.env` files in the backend for:
```
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

4. Run the application:
```bash
# In server/
node server.js

# In client/
npm run dev
```

---

## 📧 Contact

For queries or contributions, reach out at: `Nishkarsh.7078@gmail.com`
