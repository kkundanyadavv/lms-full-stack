# Full-Stack Learning Management System

A scalable full-stack LMS where instructors can create and sell courses, 
and students can browse, purchase, and consume content — all in one platform.

## Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Auth:** Clerk
- **Payments:** Stripe
- **Deployment:** Vercel

## Features
- Role-based dashboards for students and instructors
- Secure course purchases via Stripe payments
- Clerk authentication and user session management
- RESTful APIs for course management, enrollment, and content delivery
- Modular and responsive UI with React + Tailwind

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- Stripe account
- Clerk account

### Installation
```bash
# Clone the repo
git clone <your-repo-url>

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

### Environment Variables
Create a `.env` file in the server folder:
MONGODB_URI=your_mongodb_uri
STRIPE_SECRET_KEY=your_stripe_key
CLERK_SECRET_KEY=your_clerk_key
