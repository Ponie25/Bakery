# 🥖 Bakery Website

A modern full-stack web application for a bakery business, featuring a beautiful frontend interface and a robust backend API for managing products and orders.

## 🌟 Features

### Frontend
- **Responsive Design** - Mobile-first approach with beautiful UI
- **Interactive Sections**:
  - Hero Section with compelling visuals
  - Bakery Products showcase
  - Beverage menu
  - About Us section
  - Location information
  - Newsletter subscription
  - Press coverage
- **User Authentication** - Login and Sign-up modals
- **Modern Navigation** - Intuitive header and footer
- **Menu Display** - Dedicated menu page for products

### Backend
- **RESTful API** - Clean and organized API endpoints
- **Product Management** - CRUD operations for bakery items
- **Order Processing** - Handle customer orders efficiently
- **Modular Architecture** - Well-organized controllers, models, and routes

## 🛠️ Tech Stack

### Frontend
- **Vue.js 3** - Progressive JavaScript framework
- **Vue Router** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **PostCSS** - CSS processing tool

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **RESTful API** - Standard API architecture

## 📁 Project Structure

```
bakery/
├── client/                 # Frontend Vue.js application
│   ├── src/
│   │   ├── components/
│   │   │   ├── common/     # Reusable components (Login, SignUp)
│   │   │   ├── layout/     # Layout components (Navbar, Footer)
│   │   │   └── sections/   # Page sections (Hero, About, etc.)
│   │   ├── views/          # Page components
│   │   ├── App.vue         # Main application component
│   │   ├── main.js         # Application entry point
│   │   └── router.js       # Route configuration
│   ├── helpers/            # Utility functions
│   └── package.json        # Frontend dependencies
├── server/                 # Backend Node.js application
│   ├── api/
│   │   ├── controllers/    # Business logic
│   │   ├── models/         # Data models
│   │   └── routes/         # API routes
│   ├── app.js             # Server entry point
│   └── package.json       # Backend dependencies
└── README.md              # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/bakery.git
   cd bakery
   ```

2. **Install Backend Dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../client
   npm install
   ```

### Running the Application

1. **Start the Backend Server**
   ```bash
   cd server
   npm start
   ```
   The server will run on `http://localhost:3000` (or your configured port)

2. **Start the Frontend Development Server**
   ```bash
   cd client
   npm run dev
   ```
   The client will run on `http://localhost:5173` (Vite default)

## 📡 API Endpoints

### Products
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get product by ID
- `POST /api/products` - Create new product
- `PUT /api/products/:id` - Update product
- `DELETE /api/products/:id` - Delete product

### Orders
- `GET /api/orders` - Get all orders
- `GET /api/orders/:id` - Get order by ID
- `POST /api/orders` - Create new order
- `PUT /api/orders/:id` - Update order
- `DELETE /api/orders/:id` - Delete order

## 🎨 Frontend Components

### Layout Components
- **Navbar** - Navigation header with menu items
- **Footer** - Site footer with links and information

### Common Components
- **LoginModal** - User authentication modal
- **SignUpModal** - User registration modal

### Section Components
- **HeroSection** - Landing page hero with call-to-action
- **AboutSection** - Information about the bakery
- **BakerySection** - Showcase of bakery products
- **BeverageSection** - Drinks and beverages menu
- **LocationSection** - Store location and contact info
- **NewsletterSection** - Email subscription form
- **PressSection** - Media coverage and testimonials

## 🔧 Development

### Frontend Development
```bash
cd client
npm run serve          # Start development server
```

### Backend Development
```bash
cd server
npm start           # Start server
npm run dev         # Start with nodemon 
```
**Happy Baking! 🥐🍰**
