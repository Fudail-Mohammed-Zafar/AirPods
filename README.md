# AirPods Landing Page

A responsive and animated landing page for **AirPods**, featuring GSAP animations and ScrollMagic for scroll-triggered effects. The page showcases the product's description, specifications, and a sleek, modern design.

## Features

- **Responsive Design**: The page adapts seamlessly to different screen sizes and devices.
- **GSAP Animations**: Smooth and captivating animations for text, images, and navigation elements.
- **ScrollMagic Effects**: Trigger animations on scroll to enhance the user experience.
- **Stylish Navigation Bar**: Includes a toggleable dropdown menu for smaller screens and a Buy button that redirects to the Apple AirPods product page.
- **Interactive Sections**: Dynamic scrolling behavior that reveals the AirPods' details with smooth animations.

## Project Structure

```bash
AirPods-Landing-Page/
│
├── assets/                         # Static assets folder
│   ├── css/
│   │   └── styles.css              # CSS file for page styling
│   ├── icons/                      # Icons used in the page
│   │   └── bx-chevron-down.svg
│   └── img/                        # Images used in the page
│       ├── airpod1.png
│       ├── airpod2.png
│       └── airpods.png
│
├── index.html                      # Main HTML file
├── README.md                       # Project documentation
└── assets/js/main.js               # JavaScript file for animations and interaction
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/username/airpods-landing-page.git
   ```

2. Navigate to the project folder:
   ```bash
   cd airpods-landing-page
   ```

3. Open the `index.html` file in your browser to view the landing page.

## Interactivity

1. **Navigation Menu**: The navigation bar includes links for product description and specifications. On smaller screens, the menu is toggleable by clicking the down-chevron icon.
   
2. **Animations**: GSAP is used for smooth text and image animations when the page loads. ScrollMagic triggers additional animations as you scroll to the details section.

3. **Buying Option**: There is a **Buy** button in the top-right corner of the page that redirects users to the official AirPods buying page on Apple's website.