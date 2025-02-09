

# Imagify SaaS - Setup & Run Guide

## 📌 Overview
Imagify SaaS is a full-stack application designed for image-related services. Follow this guide to set up and run the project locally.

## 📋 Prerequisites
Before running this project, ensure you have the following installed:

- **Node.js** (Download: [Node.js Official Site](https://nodejs.org/en/download/))
- **MongoDB Atlas** (Cloud Database) or **MongoDB Compass** (Local Database)
- **VS Code** or any preferred code editor

---

## 🔧 Installation & Setup

### 🖥️ Backend (Server) Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. Open the project folder in VS Code.

3. Navigate to the server folder and open the terminal:
   ```bash
   cd server
   ```

4. Install dependencies:
   ```bash
   npm install
   ```

5. **Setup Environment Variables**:
   - Create a `.env` file inside the `server` folder and add:
     ```
     CLIPDROP_API_KEY=your_api_key
     MONGO_URI=your_mongodb_connection_string
     STRIPE_SECRET_KEY=your_stripe_secret_key (Optional)
     RAZORPAY_KEY_ID=your_razorpay_key_id (Optional)
     RAZORPAY_SECRET_KEY=your_razorpay_secret_key (Optional)
     ```

6. **Run the Server**:
   ```bash
   npm run server
   ```
---

### 🌐 Frontend (Client) Setup
1. Open the terminal in the client folder:
   ```bash
   cd client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the client:
   ```bash
   npm run dev
   ```

4. Open the URL displayed in the terminal (usually `http://localhost:5173`).

---

## 🛠️ Required Skills
To work on this project, you should be familiar with:

- **Frontend**: React.js, Tailwind CSS, Redux
- **Backend**: Node.js, Express.js, MongoDB
- **APIs**: Stripe, Razorpay, Clipdrop API
- **Database Management**: MongoDB Atlas or Compass
- **Version Control**: Git & GitHub

---

## 🎥 Video Tutorial
For a step-by-step guide, watch the tutorial:  
📺 [How to Run Project](https://youtu.be/WKjimM_BlgM)

---

## 💡 Troubleshooting
- Ensure all environment variables are correctly set up.
- Check if the server is running before starting the client.
- If you face issues with database connection, ensure your IP is whitelisted in MongoDB.

---

## 📬 Contact
For any issues, contact: [Instagram](https://instagram.com/greatstackdev)  
Explore more projects: [GreatStack](https://greatstack.dev/source-code)

---

Save this as `README.md` in your GitHub repository, and it will be displayed as the main documentation when someone visits your repo. 🚀
