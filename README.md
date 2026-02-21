# Katar Saree - Premium E-Commerce Platform

Katar Saree is a sophisticated, full-stack e-commerce application designed for an exquisite shopping experience. Specializing in high-quality sarees like Banarasi and Silk, the platform combines traditional heritage with modern technology to provide a seamless user journey from discovery to checkout.

## 🚀 Key Features

- **Rich Product Discovery**: Browse extensive collections including Banarasi, Silk, and New Arrivals.
- **Dynamic User Interface**: Smooth animations using Framer Motion and modern styling with Tailwind CSS.
- **Advanced Cart System**: Comprehensive cart and wishlist management.
- **Secure Checkout**: Integrated with **Razorpay** for safe and reliable payments.
- **Identity & Profiles**: Secure user authentication and personalized user profiles.
- **Interactive Elements**: WhatsApp integration for direct support, video call sections, and customer testimonials.
- **Informational Pages**: Dedicated sections for Heritage, Craftsmanship, Blog, and Policies.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop views.

## 🛠️ Tech Stack

### Frontend
- **Framework**: React.js with Vite
- **Routing**: React Router DOM
- **State Management**: Redux Toolkit & React-Redux
- **Styling**: Tailwind CSS & Framer Motion
- **Icons**: Lucide React
- **Notifications**: React Hot Toast

### Backend
- **Framework**: Node.js & Express
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Gateway**: Razorpay
- **Environment Management**: Dotenv

## 📁 Project Structure

```text
katar-saree/
├── client/                 # React Frontend
│   ├── src/
│   │   ├── components/     # UI Components
│   │   ├── context/        # Context Providers (Auth, Cart, etc.)
│   │   ├── Redux/          # State Management
│   │   ├── pages/          # Main Page Views
│   │   └── App.jsx         # Main Application Entry
├── server/                 # Express Backend
│   ├── controllers/        # Request Handlers
│   ├── models/             # Mongoose Schemas
│   ├── routes/             # API Endpoints
│   ├── config/             # Database & System Configuration
│   └── server.js           # Server Entry Point
```

## ⚙️ Setup & Installation

### Prerequisites
- Node.js (v16+)
- MongoDB Atlas or Local MongoDB instance
- Razorpay API Keys

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shagufta0525/Katar-saree.git
   cd Katar-saree
   ```

2. **Backend Setup**:
   ```bash
   cd server
   npm install
   ```
   Create a `.env` file in the `server` directory and add your credentials:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   RAZORPAY_KEY_ID=your_key_id
   RAZORPAY_KEY_SECRET=your_key_secret
   FRONTEND_URL=http://localhost:5173
   ```
   Start the server:
   ```bash
   npm run dev
   ```

3. **Frontend Setup**:
   ```bash
   cd ../client
   npm install
   ```
   Start the frontend:
   ```bash
   npm run dev
   ```

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License
This project is licensed under the ISC License.
