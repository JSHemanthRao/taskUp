# TaskUp - Professional Freelance & Service Marketplace

TaskUp is a robust and scalable freelance marketplace platform built with **Laravel 10** and **Livewire**. It connects Buyers and Sellers in a seamless ecosystem, facilitating project posting, bidding, gig creation, and secure payments. Designed for performance and user experience, TaskUp offers a comprehensive solution for modern service marketplaces.

## Key Features

### For Sellers (Freelancers)
- **Gig Management**: Create and manage service gigs with detailed pricing tiers (Basic, Standard, Premium).
- **Proposal Submission**: Browse projects and submit detailed proposals with milestone-based or fixed pricing.
- **Wallet System**: Integrated wallet for earnings, withdrawals, and transaction history.
- **Profile & Portfolio**: Showcase skills, verified identity, and past work history.
- **Real-time Order Tracking**: Manage ongoing orders with status updates (Pending, In Progress, Delivered, Completed).

### For Buyers (Clients)
- **Project Posting**: Post detailed projects with budget ranges, required skills, and duration.
- **Seller Discovery**: "Browse All Projects" and "Explore Sellers" with advanced filtering (skills, location, rating).
- **Proposal Management**: Review, shortlist, and hire freelancers directly from received proposals.
- **Secure Payments**: Escrow-style payment handling to ensure service delivery before funds release.
- **Gig Purchase**: Direct purchase of defined service gigs from top-rated sellers.

### Core System Features
- **Authentication**: Secure role-based login (Admin, Buyer, Seller) with email verification.
- **Dashboard**: Interactive dashboards for all user roles with statistical insights.
- **Messaging**: Built-in chat system for direct communication between parties.
- **Verification**: Identity and document verification system for trusted user base.
- **Admin Panel**: Comprehensive backend for site management, dispute resolution, and commission settings.

## 🛠 Tech Stack

- **Backend Framework**: Laravel 10.x
- **Frontend Interactivity**: Laravel Livewire
- **Database**: MySQL
- **Styling**: Bootstrap / Custom CSS
- **Payment Gateways**: Stripe (Integrated) & Wallet System
- **Assets Management**: Optimized asset handling via Storage

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/JSHemanthRao/taskUp.git
   cd taskUp
   ```

2. **Install Dependencies**
   ```bash
   composer install
   npm install && npm run dev
   ```

3. **Environment Configuration**
   Copy the example environment file and configure your database and mail credentials.
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Database Setup**
   Run migrations and seed the database with initial data.
   ```bash
   php artisan migrate --seed
   ```

5. **Run the Application**
   ```bash
   php artisan serve
   ```
   Visit `http://localhost:8000` in your browser.

##  Contribution

Contributions are welcome! Please fork the repository and create a pull request for any feature enhancements or bug fixes.

---

**TaskUp** - Empowering the Gig Economy.
