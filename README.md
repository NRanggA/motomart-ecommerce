# 🏍️ MotoMart - Motorcycle Spare Parts E-Commerce Website

A complete, responsive e-commerce website for motorcycle spare parts built with modern web technologies. Features user authentication, shopping cart functionality, admin panel, and a beautiful user interface.

![MotoMart Preview](https://images.unsplash.com/photo-1558618047-3c8c76ca7d13?w=800&h=400&fit=crop)

## 🚀 Live Demo

- **GitHub Repository**: [https://github.com/NRanggA/motomart-ecommerce](https://github.com/NRanggA/motomart-ecommerce)
- **Live Website**: [GitHub Pages URL] (will be available after GitHub Pages setup)

## ✨ Features

### 🛍️ Customer Features
- **Product Catalog**: Browse motorcycle spare parts with advanced filtering and search
- **Categories**: 8 different product categories (Engines, Frames, Electrical, Brakes, etc.)
- **Shopping Cart**: Add/remove items, adjust quantities, real-time total calculation
- **User Authentication**: Secure registration and login system
- **OTP Verification**: Email verification with 6-digit OTP system
- **User Profile**: Manage personal information and view order history
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 🔐 Security Features
- **Password Strength Meter**: Real-time password strength validation
- **Form Validation**: Client-side validation with visual feedback
- **Secure Authentication**: Password-protected user accounts
- **Session Management**: Remember me functionality with localStorage

### 👨‍💼 Admin Panel
- **Dashboard**: Overview of products, users, and inventory statistics
- **Product Management**: Full CRUD operations for products
- **User Management**: View and manage registered users
- **Inventory Tracking**: Low stock alerts and stock management
- **Image Preview**: Real-time image preview for product uploads

### 🛒 E-Commerce Functionality
- **Advanced Filtering**: Filter by category, price range, and search terms
- **Sorting Options**: Sort products by name, price, or stock
- **Pagination**: Navigate through product pages efficiently
- **Stock Management**: Real-time stock tracking and out-of-stock handling
- **Checkout System**: Complete order processing simulation

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Bootstrap 5.3.2
- **Icons**: Bootstrap Icons
- **Storage**: LocalStorage (simulates database)
- **Responsive**: Mobile-first design approach
- **Build Tools**: Vite, TypeScript, Biome (for linting)

## 📱 Responsive Design

The website is fully responsive and tested on:
- 📱 Mobile devices (320px and up)
- 📱 Tablets (768px and up)
- 💻 Desktop computers (1024px and up)
- 🖥️ Large screens (1440px and up)

## 🚀 Quick Start

### Option 1: Direct Use (Recommended)
1. Clone the repository:
   ```bash
   git clone https://github.com/NRanggA/motomart-ecommerce.git
   cd motomart-ecommerce
   ```

2. Open `index.html` in your web browser or serve it using a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js http-server
   npx http-server

   # Using PHP
   php -S localhost:8000
   ```

3. Visit `http://localhost:8000` in your browser

### Option 2: Development Setup
1. Install dependencies:
   ```bash
   bun install
   # or
   npm install
   ```

2. Start development server:
   ```bash
   bun run dev
   # or
   npm run dev
   ```

3. Open your browser to `http://localhost:5173`

## 📖 Usage Guide

### For Customers
1. **Browse Products**: Visit the homepage to see popular products and categories
2. **Search & Filter**: Use the Products page to search and filter items
3. **Register/Login**: Create an account or login to add items to cart
4. **Shopping**: Add products to cart and proceed to checkout
5. **Profile Management**: Update your profile information in the Profile section

### For Administrators
1. **Login**: Use admin credentials to access the admin panel
2. **Dashboard**: View overall statistics and system health
3. **Product Management**: Add, edit, or delete products
4. **User Management**: View registered users and their information

### Default Admin Account
Since this is a demo, the first registered user automatically becomes an admin.

## 🔧 Customization

### Adding New Categories
Edit the `categories` array in the JavaScript section:
```javascript
const categories = [
    { name: 'New Category', icon: 'bi-icon-name', description: 'Category description' },
    // ... existing categories
];
```

### Styling Customization
The CSS uses CSS custom properties for easy theming:
```css
:root {
    --primary-color: #dc3545;
    --secondary-color: #6c757d;
    /* ... other properties */
}
```

### Adding New Features
The modular JavaScript structure makes it easy to add new features:
- Authentication functions
- Product management functions
- UI utility functions
- Admin panel functions

## 📊 Project Structure

```
motomart-ecommerce/
├── index.html          # Main application file
├── package.json        # Project dependencies and scripts
├── README.md          # Project documentation
├── .gitignore         # Git ignore rules
└── other config files # TypeScript, ESLint, Biome configs
```

## 🗄️ Data Storage

The application uses **localStorage** to simulate a database:
- `motomart_products`: Product inventory
- `motomart_users`: User accounts
- `motomart_cart`: Shopping cart items
- `motomart_currentUser`: Current session

## 🎨 Design Features

- **Modern UI**: Clean, professional design with Bootstrap 5
- **Interactive Elements**: Hover effects, transitions, and animations
- **Color Scheme**: Red and gray theme matching motorcycle aesthetics
- **Typography**: Clear, readable fonts with proper hierarchy
- **Icons**: Comprehensive icon usage for better UX

## 🔒 Security Considerations

This is a **frontend-only demo application**. For production use:
- Implement proper backend authentication
- Use secure password hashing (bcrypt, etc.)
- Add HTTPS encryption
- Implement proper session management
- Add CSRF protection
- Validate all inputs server-side

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -am 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Made with ❤️ for motorcycle enthusiasts**
