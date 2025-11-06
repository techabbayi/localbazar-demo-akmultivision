# LocalBazar - Modern E-Commerce Platform

![LocalBazar](https://img.shields.io/badge/LocalBazar-E--Commerce-0d9488?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-10b981?style=for-the-badge)
![Design](https://img.shields.io/badge/Design-AKMutiVision-f97316?style=for-the-badge)

## 🌟 Overview

**LocalBazar** is a modern, feature-rich e-commerce platform designed to support local businesses and connect communities with fresh, locally-sourced products. This project showcases professional web design and development capabilities by **AKMutiVision Web Design**.

### 🎨 Design Philosophy

- **Modern UI/UX**: Clean, intuitive interface with smooth animations
- **Local Focus**: Emphasis on supporting local businesses and communities
- **Responsive Design**: Fully optimized for all devices
- **Professional Branding**: Custom color scheme with teal/emerald primary and orange accents

## ✨ Features

### Customer Features
- 🛍️ **Product Browsing**: Easy-to-navigate product catalog with categories
- 🔍 **Advanced Search**: Quick product search functionality
- ❤️ **Wishlist**: Save favorite items for later
- 🛒 **Shopping Cart**: Seamless cart management
- 💳 **Checkout**: Streamlined checkout process
- 📱 **Responsive Design**: Works perfectly on mobile, tablet, and desktop
- 📝 **Blog**: Engaging content about local products and businesses

### Admin Features (Demo)
- 📊 **Dashboard**: Overview of sales, orders, and statistics
- 📦 **Product Management**: Add, edit, and delete products
- 📋 **Order Management**: Track and manage customer orders
- 👥 **Customer Management**: View customer information
- 📈 **Analytics**: Sales trends and performance metrics
- ⚡ **Quick Actions**: Fast access to common tasks

## 🎨 Design & Branding

### Color Palette
```css
Primary Color:   #0d9488 (Teal/Emerald)
Secondary Color: #14b8a6 (Light Teal)
Accent Color:    #f97316 (Orange)
Dark Color:      #1e293b (Dark Slate)
Light BG:        #f0fdfa (Very Light Teal)
```

### Typography
- **Primary Font**: Poppins (Modern, clean sans-serif)
- **Display Font**: Playfair Display (Elegant headings)

### Key Design Elements
- Gradient backgrounds for headers and buttons
- Smooth hover effects and transitions
- Card-based layouts with subtle shadows
- Modern rounded corners (15px border-radius)
- Icon integration with FontAwesome

## 📁 Project Structure

```
estore-master/
├── index.html              # Homepage
├── admin.html              # Admin dashboard (NEW)
├── about.html              # About page
├── blog.html               # Blog listing
├── cart.html               # Shopping cart
├── Catagori.html          # Categories page
├── checkout.html           # Checkout process
├── contact.html            # Contact form
├── login.html              # User login
├── product_list.html       # Product catalog
├── single-product.html     # Product details
├── assets/
│   ├── css/
│   │   ├── style.css           # Main styles
│   │   └── localbazar-custom.css  # Custom theme (NEW)
│   ├── js/                 # JavaScript files
│   ├── img/                # Images and icons
│   └── fonts/              # Custom fonts
└── README.md               # This file
```

## 🚀 Getting Started

### Installation

1. **Clone or Download** the project:
   ```bash
   git clone https://github.com/techabbayi/localbazar-demo-akmultivision
   cd localbazar-demo-akmultivision
   ```

2. **Open in Browser**:
   Simply open `index.html` in your web browser

3. **Or Use Local Server** (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the Site**:
   - Main Site: `http://localhost:8000`
   - Admin Panel: `http://localhost:8000/admin.html`

## 🔧 Customization

### Updating Colors

Edit `assets/css/localbazar-custom.css`:

```css
:root {
    --primary-color: #0d9488;      /* Your primary color */
    --secondary-color: #14b8a6;    /* Your secondary color */
    --accent-color: #f97316;       /* Your accent color */
}
```

### Changing Logo

Replace the logo text in HTML files:

```html
<span class="logo-text">Local<span class="bazar">Bazar</span></span>
```

Or add an image:

```html
<img src="assets/img/logo/your-logo.png" alt="LocalBazar">
```

### Adding Products

1. Navigate to the admin panel (`admin.html`)
2. Click "Add Product" (demo mode)
3. In production, connect to backend API

## 🎯 Pages Overview

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Landing page with hero slider |
| Shop | `product_list.html` | Product catalog |
| Product | `single-product.html` | Product details |
| Categories | `Catagori.html` | Product categories |
| Cart | `cart.html` | Shopping cart |
| Checkout | `checkout.html` | Checkout process |
| Blog | `blog.html` | Blog posts |
| About | `about.html` | About LocalBazar |
| Contact | `contact.html` | Contact form |
| Login | `login.html` | User authentication |
| **Admin** | `admin.html` | **Admin dashboard (NEW)** |

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox & Grid
- **Bootstrap 4**: Responsive framework
- **JavaScript/jQuery**: Interactive functionality
- **FontAwesome**: Icon library
- **Owl Carousel**: Image sliders
- **Slick Slider**: Product carousels
- **AOS**: Scroll animations

## 📱 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔐 Admin Panel

### Access
- URL: `admin.html`
- Demo Mode: All actions are simulated
- Features: Product management, order tracking, analytics

### Demo Credentials
```
Username: admin
Password: demo123
(Not functional in demo mode)
```

## 📊 Admin Features

### Dashboard
- Real-time statistics
- Sales overview charts
- Recent orders table
- Quick action buttons

### Product Management
- Add/Edit/Delete products
- Inventory tracking
- Category management
- Price updates

### Order Management
- Order status tracking
- Customer information
- Delivery management
- Order history

## 🎓 Learn More

### About AKMutiVision Web Design

This project is a showcase of professional web design and development services offered by **AKMutiVision Web Design**.

**Services Include:**
- 🎨 Custom Web Design
- 💻 E-Commerce Development
- 📱 Responsive Design
- 🔧 Website Maintenance
- 🚀 Performance Optimization
- 🎯 SEO Services

**Contact:**
- Website: [Your Website]
- Email: [Your Email]
- Phone: [Your Phone]
- Social Media: [Links]

## 📝 Customization Guide

### For Developers

1. **Adding New Pages**: Follow the existing HTML structure
2. **Styling**: Use `localbazar-custom.css` for custom styles
3. **JavaScript**: Add custom JS to `assets/js/main.js`
4. **Images**: Place in `assets/img/` directory

### For Designers

1. **Colors**: Update CSS variables in `localbazar-custom.css`
2. **Fonts**: Add new fonts in `assets/fonts/`
3. **Layout**: Modify Bootstrap grid classes
4. **Components**: Use existing card/button styles

## 🐛 Known Issues

- Admin panel is demo-only (no backend integration)
- Some images are placeholders
- Contact form needs backend integration
- Payment gateway not integrated

## 🚧 Future Enhancements

- [ ] Backend API integration
- [ ] User authentication system
- [ ] Real-time order tracking
- [ ] Payment gateway integration
- [ ] Email notifications
- [ ] Advanced search filters
- [ ] Customer reviews system
- [ ] Inventory management
- [ ] Multi-language support
- [ ] Dark mode theme

## 📄 License

This project is created for demonstration purposes by **AKMutiVision Web Design**.

## 🤝 Contributing

This is a showcase project. For customization requests or to build a similar project, please contact AKMutiVision Web Design.

## 💬 Support

For support, questions, or custom development:
- Email: support@akmutivision.com
- Website: www.akmutivision.com
- Phone: [Your Contact Number]

## 🙏 Acknowledgments

- Bootstrap team for the responsive framework
- FontAwesome for the icon library
- All open-source contributors

---

<div align="center">

### 🎨 Designed & Developed by **AKMutiVision Web Design**

**Professional Web Solutions for Modern Businesses**

[Website](#) | [Portfolio](#) | [Contact](#)

⭐ **Star this project if you like it!** ⭐

</div>

---

## 📸 Screenshots

### Homepage
![Homepage](screenshots/home.png)

### Admin Dashboard
![Admin Dashboard](screenshots/admin.png)

### Product Catalog
![Products](screenshots/products.png)

---

**Last Updated:** November 6, 2025  
**Version:** 2.0  
**Status:** Active Development

