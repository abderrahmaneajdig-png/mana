# LuxBeauty - Luxury E-Commerce Website

A modern, premium e-commerce website for luxury cosmetics and skincare products, inspired by high-end beauty brands like Sephora and Dior.

## Features

### Design
- **Premium Dark Theme**: Black, dark brown, nude beige, and soft gold accents
- **Minimalist & Elegant**: Clean design with smooth animations and transitions
- **Glassmorphism Effects**: On buttons and navbar for a modern look
- **Responsive Design**: Optimized for mobile, tablet, and desktop
- **Typography**: Modern sans-serif fonts (Poppins/Montserrat)

### Functionality
- **Product Showcase**: Large product cards with hover animations
- **Shopping Cart**: Local storage-based cart system with quantity management
- **Product Filtering**: By category, price, and rating
- **Search Functionality**: Real-time product search
- **Dark/Light Mode Toggle**: Theme switching capability
- **Swiper.js Integration**: Smooth sliders for best sellers
- **Checkout Process**: Complete order form with multiple payment options
- **Wishlist System**: Save favorite products
- **Loading Animations**: Smooth transitions and effects

## Pages

1. **Homepage (index.html)**: Hero section, featured products, categories, best sellers, testimonials, newsletter
2. **Shop Page (shop.html)**: Product grid with filters and search
3. **Cart Page (cart.html)**: Shopping cart with quantity controls
4. **Checkout Page (checkout.html)**: Complete checkout form

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styles with Tailwind CSS framework
- **JavaScript**: Interactive functionality
- **Tailwind CSS**: Utility-first CSS framework
- **Swiper.js**: Touch slider library
- **Font Awesome**: Icon library
- **Local Storage**: Client-side data persistence

## File Structure

```
luxbeauty/
├── index.html          # Homepage
├── shop.html           # Product listing page
├── cart.html           # Shopping cart page
├── checkout.html       # Checkout page
├── css/
│   └── styles.css      # Custom styles
├── js/
│   ├── script.js       # Main JavaScript
│   ├── shop.js         # Shop page functionality
│   ├── cart.js         # Cart page functionality
│   └── checkout.js     # Checkout page functionality
└── images/             # Image assets (placeholder)
```

## How to Run

1. Clone or download the project files
2. Open `index.html` in a modern web browser
3. Navigate through the site using the menu links

## Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Features in Detail

### Cart System
- Add products to cart from any page
- Persistent cart using localStorage
- Quantity adjustment in cart
- Real-time total calculation

### Product Filtering
- Filter by category (Skincare, Makeup, Perfumes, etc.)
- Price range filtering
- Rating-based filtering
- Real-time search

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimizations
- Touch-friendly interactions

### Animations & Effects
- Smooth hover transitions
- Loading animations
- Scroll-triggered animations
- Glassmorphism effects

## Customization

### Colors
Edit the CSS custom properties in `css/styles.css`:
```css
:root {
    --gold: #D4AF37;
    --dark-brown: #3E2723;
    --beige: #F5F5DC;
}
```

### Products
Add new products in `js/shop.js` by extending the `products` array.

### Styling
Modify Tailwind classes or add custom CSS in `css/styles.css`.

## Future Enhancements

- User authentication system
- Backend integration
- Payment gateway integration
- Product reviews and ratings
- Wishlist persistence
- Order history
- Admin panel

## License

This project is for educational and demonstration purposes.

## Credits

- Images: Unsplash
- Icons: Font Awesome
- Fonts: Google Fonts (via Tailwind)
- Slider: Swiper.js