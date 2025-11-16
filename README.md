# Car Dealer Landing Page

A modern, responsive car dealership website built with HTML, CSS, and JavaScript. This landing page provides an intuitive interface for users to browse, search, and explore cars for sale or rent.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Sticky header with smooth scrolling and mobile-friendly hamburger menu
- **Car Search Form**: Dynamic search functionality with filters for make, year, and budget
- **Browse by Type**: Quick access to different car categories (SUV, Sedan, Coupe, Convertible)
- **Popular Cars Section**: Showcases most sold car brands with sales statistics
- **Latest Cars Shop**: Grid layout displaying available cars with pricing and details
- **About Section**: Highlights key features and benefits of choosing the dealership
- **Contact Information**: Footer with business hours and quick links

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript**: Interactive functionality and DOM manipulation
- **Boxicons**: Icon library for UI elements
- **Google Fonts**: Outfit font family for typography

## Project Structure

```
car-dealer-website/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with responsive design
├── script.js           # JavaScript for interactivity
├── Images/             # Image assets folder
│   ├── logo.png
│   ├── home1.png
│   ├── car1.jpg - car6.jpg
│   ├── toyota.png, Honda.png, VW.png, Benz.png
│   └── SUV.png, sedan.png, Coupe.png, Convertible.png
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or build tools required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vivekj0911/car-dealer-website.git
```

2. Navigate to the project directory:
```bash
cd car-dealer-website
```

3. Open `index.html` in your web browser:
```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

Or simply double-click the `index.html` file.

## Usage

### Navigation
- Use the top navigation menu to jump to different sections
- On mobile devices, click the hamburger menu icon to access navigation

### Search for Cars
1. Select a car make from the dropdown
2. Choose the year of manufacture
3. Enter your budget
4. Click the "Search" button

### Browse Cars
- Scroll through the "Browse by Type" section to filter by vehicle type
- View "Popular Cars" to see best-selling brands
- Explore "Latest Cars" for recently added inventory

## Customization

### Colors
The project uses CSS custom properties for easy theming. Edit the `:root` section in `style.css`:

```css
:root{
    --bg-color: #fff;
    --text-color:#22100d;
    --second-color: #eef1fb;
    --main-color: #405ff2;
    --on-hover: #253896;
}
```

### Adding More Cars
To add more car listings, duplicate a `.row` div in the shop section of `index.html`:

```html
<div class="row">
    <img src="Images/your-car.jpg" alt="">
    <div class="shop-text">
        <h5>$Price</h5>
        <h3>Car Name</h3>
        <p>Description</p>
        <a href="#" class="view-details-link">View Details</a>
    </div>
</div>
```

## Responsive Breakpoints

- **Desktop**: 1070px and above
- **Tablet**: 768px - 1070px
- **Mobile**: Below 768px
- **Small Mobile**: Below 462px

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Future Enhancements

- Backend integration for dynamic car listings
- User authentication and account management
- Advanced search filters (color, mileage, transmission)
- Car comparison feature
- Wishlist/favorites functionality
- Contact form with email integration
- Image gallery for individual cars
- Test drive booking system

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or feedback, please reach out through the contact section on the website.

## Acknowledgments

- Icons provided by [Boxicons](https://boxicons.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)
- Images are for demonstration purposes only
