
# Reporting Management System

## What is Reporting Management System?

The **Toll Plaza Reporting Management System** is a role-based web application built to streamline issue reporting and management within toll plaza operations. It allows **Site Engineers** to report real-time issues occurring at toll plazas and enables **Admins** to manage projects, assign project incharges, monitor engineer activity, and generate insightful reports.

This system enhances transparency, coordination, and operational efficiency between field engineers and administration.

---

## 🌐 Live Preview

(https://reporting-management-system-two.vercel.app/)

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


![Screenshot 2025-06-18 234506](https://github.com/user-attachments/assets/a3153d7d-9f08-4124-a3e6-c35bc87ea0ee)
![Screenshot 2025-06-18 234526](https://github.com/user-attachments/assets/a9cc97c3-b4f0-4059-b382-a9f8b8140cf5)
![Screenshot 2025-06-18 234545](https://github.com/user-attachments/assets/63a673de-0c21-4900-a3b5-9b0c22f6ce9c)
![Screenshot 2025-06-18 234643](https://github.com/user-attachments/assets/aa19f220-a679-4d08-9e2e-193b1afc4bef)
![Screenshot 2025-06-18 234600](https://github.com/user-attachments/assets/468ce3b2-3696-41ab-ae82-95e39740d052)
![Screenshot 2025-06-18 234705](https://github.com/user-attachments/assets/68a96d90-755e-4ccc-9d93-14847dc6da2d)
![Screenshot 2025-06-18 234726](https://github.com/user-attachments/assets/72c6465c-31e9-4e25-80d5-fff0aaa156ce)
![Screenshot 2025-06-18 234744](https://github.com/user-attachments/assets/11d12bb2-20c1-4ce6-8661-097257883d03)
![Screenshot 2025-06-18 234800](https://github.com/user-attachments/assets/aafc5b86-d49b-42d3-8061-a9abaf40f912)
![Screenshot 2025-06-18 234824](https://github.com/user-attachments/assets/5b7db65a-a7cf-407f-8b08-5483e3b44969)



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
