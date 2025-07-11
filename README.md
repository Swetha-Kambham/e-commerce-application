# Handmade & Customized Products E-Commerce Platform

A scalable, full-stack web application designed to connect sellers of handmade and custom products with buyers. The platform supports role-based workflows for Buyers, Sellers, and Admins, with secure authentication, dynamic product listings, and Stripe-based checkout integration.

---

## 🔧 Tech Stack

- **Frontend:** React.js
- **Backend:** Spring Boot (Java)
- **Middleware:** GraphQL
- **Authentication:** Spring Security, JWT
- **Database:** MySQL with custom query layer
- **Payments:** Stripe API
- **Media Storage:** AWS S3
- **Deployment:** Docker, AWS EC2

---

## 👥 User Roles & Features

### Buyer
- Register and browse product listings
- Like and purchase items using secure Stripe integration
- Track order history and status

### Seller
- Register and submit profile for verification
- List and manage products (with admin approval)
- Edit inventory and product details (with validation rules)

### Admin
- Verify sellers and approve product listings
- Manage users, products, and categories
- Oversee platform moderation and data workflows

---

## ✅ Key Highlights

- ⚙️ **Modular Microservices:** Clear separation of concerns between UI, GraphQL, and backend services
- 🔐 **Role-Based Access Control:** Secure workflows using JWT and Spring Security
- 💳 **Integrated Payments:** Seamless, PCI-compliant transactions powered by Stripe
- 🗃️ **Optimized Data Access:** Custom query engine on top of MySQL for high performance
- ☁️ **Cloud Storage:** Scalable and secure media handling with AWS S3
- 🚀 **Deployment-Ready:** Dockerized services configured for AWS EC2 environments

---

## 🚀 Setup Instructions

1. **Backend**
   - Configure `application.properties` with MySQL, AWS, and Stripe credentials
   - Build and run with Maven or Spring Boot CLI

2. **Frontend**
   - Navigate to the `frontend` directory
   - Run `npm install` and `npm start`
   - Configure your Stripe public key in the `.env` file

3. **GraphQL Server**
   - Acts as a middleware for optimized data fetching between backend and frontend

---

## 📌 Future Enhancements

- ElasticSearch integration for product search
- Seller dashboards with analytics
- Product reviews and rating system
- Email notifications and order tracking
