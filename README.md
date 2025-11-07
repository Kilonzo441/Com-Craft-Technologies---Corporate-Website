Com-Craft Technologies - IT Solutions Kenya
A professional, responsive website for Com-Craft Technologies - a leading IT solutions provider in Kenya offering comprehensive technology services including CCTV installation, computer repair, network setup, and electronics services.

https://img.shields.io/badge/Com--Craft-Tech-blue https://img.shields.io/badge/Kenya-IT%2520Solutions-green https://img.shields.io/badge/Responsive-Yes-brightgreen

Live Demo
View Live Website

Table of Contents
Overview

Features

Services

Installation

Configuration

Project Structure

Design System

Browser Support

Contact

Troubleshooting

Overview
Com-Craft Technologies is a modern, single-page application website built to showcase IT services and products for the Kenyan market. The platform provides a seamless user experience for businesses and individuals seeking professional IT support in Nairobi and throughout Kenya.

Features
Core Functionality
Single-Page Application (SPA) - Smooth navigation without page reloads

Mobile-First Responsive Design - Optimized for all devices

Professional Service Showcase - Comprehensive IT services display

E-commerce Integration - Direct links to Jiji and Jumia marketplaces

Lead Generation System - Contact forms with EmailJS integration

Resource Hub - Downloadable IT resources and tools

Technical Features
SEO Optimized - Meta tags, structured data, and semantic HTML

Accessibility (A11y) - ARIA labels, keyboard navigation, screen reader support

Performance Optimized - Loading indicators and efficient asset management

Cross-browser Compatible - Works on all modern browsers

Services Offered
IT Services in Kenya
CCTV Installation - Professional surveillance solutions

Computer Repair & Maintenance - Hardware and software support

Network Installation - LAN/WAN setup and internet solutions

Software Solutions - Custom development and installation

IT Support - 24/7 technical assistance

Electronics Repair - Comprehensive device maintenance

IT Products
CCTV Camera Systems

Business Laptops & Computers

Networking Equipment

Software Suites

UPS Systems

Printers & Office Equipment

Prooject Structure
text
com-craft-technologies/
├── index.html                 # Main HTML file with embedded CSS/JS
├── icon.png                  # Company logo
├── images/                   # Image assets
│   ├── hero-bg.jpg
│   ├── about-team.jpg
│   ├── client1.jpg
│   ├── cctv-camera.jpg
│   ├── laptop.jpg
│   ├── router.jpg
│   ├── software.jpg
│   ├── ups.jpg
│   └── printer.jpg
└── downloads/                # Resource files
    ├── IT_Service_Catalog_Kenya.pdf
    ├── Network_Diagnostic_Tool_Kenya.exe
    ├── CCTV_Setup_Guide_Kenya.pdf
    ├── Security_Best_Practices_Kenya.pdf
    ├── IT_Service_Agreement_Kenya.docx
    └── PC_Maintenance_Toolkit.zip
Installation & Setup
Prerequisites
Web browser (Chrome, Firefox, Safari, Edge)

Web server for deployment (Apache, Nginx, or any static hosting)

Local Development
Clone or Download the project files

Set up a local server (optional but recommended):

bash
Using Python
python -m http.server 8000

Using Node.js
npx http-server

Using PHP
php -S localhost:8000
Open in browser: Navigate to http://localhost:8000

Production Deployment
Upload files to your web hosting service

Configure EmailJS for form functionality (see Configuration section)

Update contact information in the JavaScript configuration

Test all functionality across different devices

Configuration
EmailJS Setup
The contact form uses EmailJS for email delivery:

Create EmailJS Account at https://www.emailjs.com/

Update Service ID and Template ID in the JavaScript:

javascript
const serviceId = 'your_service_id';
const templateId = 'your_template_id';
Initialize with your Public Key:

javascript
emailjs.init("your_public_key");
Customization
Key areas to customize for your business:

Company Information: Update name, logo, contact details

Services: Modify service offerings and descriptions

Products: Update product catalog and pricing

Color Scheme: Modify CSS custom properties in :root

Images: Replace placeholder images with actual photos

Design System
Color Palette
css
:root {
    --primary: #205d86;     /* Main brand color */
    --secondary: #3498db;   /* Secondary/action color */
    --accent: #e74c3c;      /* Highlight/alert color */
    --light: #a1ccef;       /* Background color */
    --dark: #205d86;        /* Text/dark elements */
    --jiji-green: #1abc9c;  /* Jiji platform color */
}
Typography
Primary Font: Segoe UI, Tahoma, Geneva, Verdana, sans-serif

Clean, readable typography scale

Proper hierarchy for headings and body text

Responsive Breakpoints
Desktop: 1200px+ (Full features)

Tablet: 768px - 1199px (Adaptive layout)

Mobile: 320px - 767px (Mobile-optimized)

Browser Support
Chrome 60+

Firefox 55+

Safari 12+

Edge 79+

Mobile browsers (iOS Safari, Chrome Mobile)

Contact Information
Com-Craft Technologies

Location: Nairobi, Kenya

Phone: +254 700 311 368

Email: info@comcraftech.co.ke

Hours: Mon-Fri 8:00 AM - 6:00 PM, Sat 8:00 AM - 6:00 PM

Troubleshooting
Common Issues
Contact form not working

Verify EmailJS configuration

Check browser console for errors

Ensure internet connection

Images not loading

Verify image file paths

Check file permissions

Ensure correct file extensions

Mobile menu not working

Check JavaScript console for errors

Verify touch event support

Test different mobile devices

Development Scripts
The project includes a comprehensive navigation system with the following features:

Dynamic page loading

Form validation and submission

Mobile menu handling

Smooth scrolling

Loading indicators

License
All rights reserved © 2023 Com-Craft Technologies. This project is proprietary and intended for business use.

Changelog
Version 1.0.0
Initial release

Complete SPA functionality

Responsive design implementation

EmailJS integration

SEO optimization
