# Zenqo

Zenqo is a modern full-stack furniture commerce platform built around premium CNC-manufactured furniture, custom room styling, and luxury interior shopping workflows.

**Live Demo:** https://zenqo-furniture.vercel.app/  
**Source Code:** Private  
**Preview Repository:** Documentation and project showcase only

---

# Project Overview

Zenqo is designed as a modern furniture commerce experience where users can explore premium furniture collections, customize room moods, configure furniture aesthetics, manage carts, and complete a streamlined checkout workflow.

The platform focuses on combining luxury furniture branding with a clean ecommerce-style user experience for modern homes and made-to-order CNC furniture businesses.

The project was intentionally built using a React + Vite frontend with a Node.js, Express, and PostgreSQL backend architecture without using Next.js.

---

# Key Features

- Responsive luxury furniture storefront
- Product catalog for beds, seating, tables, and storage
- Collection filtering, sorting, ratings, and stock indicators
- Design Studio for curated room moods and layouts
- Furniture finish, fabric, and size customization
- Smart furniture recommendation workflow
- Cart management with quantity updates and persistence
- GST summary and checkout flow
- UPI, card, and cash-on-delivery UI support
- Custom furniture consultation request system
- Newsletter subscription support
- Express API health endpoint
- PostgreSQL-ready backend structure
- Modern responsive UI and ecommerce workflow

---

# User Workflow

```text
User enters Zenqo platform
        |
User explores furniture collections
        |
Filters and customizes products
        |
Opens Design Studio experience
        |
Creates preferred room mood
        |
Adds products to cart
        |
Reviews checkout details
        |
Places order through checkout UI
        |
Optional consultation request submission
```

---

# Main Pages

- Home Page
- Furniture Collections
- Design Studio
- About Page
- Login Page
- Signup Page
- Cart and Checkout Page

---

# Demo Workflow

1. Open the live deployment
2. Explore the furniture storefront
3. Browse collections and apply filters
4. Open the Design Studio
5. Configure room styles and furniture combinations
6. Add products to the cart
7. Continue through the checkout UI
8. Submit a custom consultation request if needed

---

# Tech Stack

## Frontend

- React 19
- Vite
- JavaScript
- CSS3
- Lucide React

## Backend

- Node.js
- Express.js
- PostgreSQL
- pg
- cors
- dotenv

## Deployment And Tools

- Vercel
- npm
- Git
- Web3Forms

---

# Backend API Surface

| Area | Endpoints |
|---|---|
| Health | `GET /api/health` |
| Products | `GET /api/products` |
| Product Details | `GET /api/products/:id` |
| Orders | `POST /api/orders` |
| Consultation | `POST /api/consultation` |

---

# Database Design

The backend architecture is structured around:

- `products`
- `orders`
- `consultation_requests`
- `customers`

The schema is designed for future production-ready ecommerce expansion and order persistence.

---

# Validation And Testing

Verified checks include:

- Frontend production deployment validation
- Responsive UI testing
- Product browsing workflow testing
- Design Studio interaction testing
- Cart and checkout validation
- Consultation form workflow testing
- API health endpoint verification
- Frontend build validation

---

# Current Limitations

- Payment gateways are not yet production integrated
- Public deployment focuses on frontend workflow demonstration
- Database-backed production order persistence is planned for future versions
- Full production source code remains private

This repository exists for recruiter showcase, workflow explanation, and technical project presentation.

---

# What This Project Demonstrates

- Full-stack ecommerce architecture
- Modern React frontend development
- Ecommerce UI and UX workflows
- Furniture customization interface design
- Backend API integration
- PostgreSQL-ready backend structuring
- Production deployment using Vercel
- Real-world product and checkout workflows

---

# Screenshots

Screenshots are included in this repository to showcase the deployed UI, workflow, and overall project experience.

---

# Current Status

Zenqo is deployed and functioning as a modern furniture commerce prototype and portfolio project.

The public repository is intended for project showcase, architecture overview, and technical demonstration purposes.

---

# Author

Rayan Qamar
