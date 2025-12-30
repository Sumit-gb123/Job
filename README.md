 live preview == https://prodigy-portal.vercel.app/


Prodigy Job Portal is a full-stack MERN web application where companies can post jobs and job seekers can search and apply easily.
It provides separate dashboards for recruiters and applicants with secure login and a modern user interface.


## Screenshots

![Startup Website Screenshot](./Prodigy.gif)
✨ Features
👔 Recruiters / Companies

Post new job openings

Edit and manage job listings

View applications from candidates

Recruiter dashboard for job management

Company profile setup

👨‍💼 Applicants

Search jobs with filters

Apply to jobs by uploading resume

Track applied job status

Manage personal profile

⚙️ Common Features

Secure login and signup

File upload support (resume)

Error tracking

Mobile-friendly responsive design

REST API based backend




**Frontend:**
- React (Vite)
- Tailwind CSS
- React Router
- Axios
- Chart.js (for dashboards)

**Backend:**
- Express.js
- Mongoose (MongoDB ODM)
- JSON Web Tokens (JWT)
- Bcrypt (password hashing)
- CORS
- Svix (webhooks)

**Third-Party Services:**
- Clerk (Authentication)
- Sentry (Error Tracking)
- Cloudinary (File Storage)
## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas account
- Clerk, Sentry, and Cloudinary accounts

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/prodigy-job-portal.git
   cd prodigy-job-portal

2.  **Client**

    * cd client

    * npm install

 **Server**

    * cd ../server
    * npm install

3. **Environment Setup**

Create .env files in both client/ and server/ directories:

* Server (.env):

    MONGODB_URI=your_mongodb_uri
    CLERK_SECRET_KEY=your_clerk_secret_key
    JWT_SECRET=your_jwt_secret
    CLOUDINARY_CLOUD_NAME=your_cloud_name
    CLOUDINARY_API_KEY=your_api_key
    CLOUDINARY_API_SECRET=your_api_secret
    SENTRY_DSN=your_sentry_dsn
    CLERK_WEBHOOK_SECRET=your_svix_webhook_secret
    PORT=5000

* Client (.env):

    VITE_CLERK_PUBLISHABLE_KEY=your_clerk_pub_key
    VITE_API_BASE_URL=http://localhost:5000/api


# Start backend server
* cd server

* npm run dev

# Start frontend (in separate terminal)
* cd client

* npm run dev


## 🚀 Contributions

Contributions are welcome! Please follow these steps:

**Fork the repository**

* Create your feature branch (git checkout -b feature/AmazingFeature)

* Commit your changes (git commit -m 'Add some AmazingFeature')

* Push to the branch (git push origin feature/AmazingFeature)

* Open a Pull Request.


