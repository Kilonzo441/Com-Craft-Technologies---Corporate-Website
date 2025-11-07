<!DOCTYPE html>
<html lang="en-KE">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Com-Craft Technologies - Professional IT solutions in Kenya including CCTV installation, computer repair, network setup, and electronics services. Reliable IT support in Nairobi.">
    <meta name="keywords" content="IT solutions Kenya, CCTV installation Nairobi, computer repair Kenya, network installation, IT support services, electronics repair Kenya, business IT services">
    <meta name="author" content="Com-Craft Technologies">
    <meta name="robots" content="index, follow">
    
    <!-- Open Graph Meta Tags -->
    <meta property="og:title" content="Com-Craft Technologies - IT Solutions & Support in Kenya">
    <meta property="og:description" content="Professional IT services in Kenya including CCTV installation, computer maintenance, network solutions, and electronics repair.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://comcraftech.co.ke">
    
    <!-- Structured Data -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "LocalBusiness",
      "name": "Com-Craft Technologies",
      "description": "Professional IT solutions provider in Kenya offering CCTV installation, computer repair, network setup, and electronics services.",
      "url": "https://comcraftech.co.ke",
      "telephone": "+254700311368",
      "email": "info@comcraftech.co.ke",
      "address": {
        "@type": "PostalAddress",
        "addressLocality": "Nairobi",
        "addressCountry": "Kenya"
      },
      "areaServed": "Kenya",
      "serviceType": [
        "CCTV Installation",
        "Computer Repair",
        "Network Installation",
        "IT Support",
        "Software Solutions",
        "Electronics Repair"
      ],
      "openingHours": "Mo-Fr 08:00-18:00, Sa 08:00-18:00"
    }
    </script>
    
    <title>Com-Craft Technologies - IT Solutions & IT Support Services in Kenya</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
    <style>
        /* CSS section*/
        :root {
            --primary: #205d86;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #a1ccef;
            --dark: #205d86;
            --text: #333;
            --text-light: #7f8c8d;
            --success: #2ecc71;
			--warning: #f39c12;
            --jiji-green: #1abc9c; /*Jiji button color */
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: var(--text);
            background-color: #d9ebf9;
        }
        
        a {
            text-decoration: none;
            color: var(--secondary);
            transition: all 0.3s ease;
        }
        
        a:hover {
            color: var(--accent);
			outline: 2px solid var(--secondary);
            outline-offset: 2px;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        .btn {
            display: inline-block;
            padding: 10px 25px;
            background-color: var(--secondary);
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        
        .btn:hover, .btn:focus {
            background-color: var(--primary);
            color: white;
            outline: 2px solid var(--light);
            outline-offset: 2px;
        }
        
        .btn-accent {
            background-color: var(--accent);
        }
        
        .btn-accent:hover, .btn-accent:focus {
            background-color: #c0392b;
        }
        
        /* Jiji button style */
        .btn-jiji {
            background-color: var(--jiji-green);
        }
        
        .btn-jiji:hover, .btn-jiji:focus {
            background-color: #16a085;
        }
        
        .btn:disabled {
            background-color: #95a5a6;
            cursor: not-allowed;
			opacity: 0.7;
        }
        
        section {
            padding: 60px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            position: relative;
        }
        
        .section-title h2 {
            font-size: 2.2rem;
            color: var(--primary);
            margin-bottom: 15px;
        }
        
        .section-title p {
            color: var(--text-light);
            max-width: 700px;
            margin: 0 auto;
        }
        
        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background-color: var(--secondary);
            margin: 15px auto;
        }
        
        /* Header Styles */
        header {
            background-color: #a1ccef;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
        }
        
        .logo img {
            width: 50px;
            height: 50px;
            margin-right: 12px;
        }
        
        .logo h1 {
            font-size: 1.8rem;
            color: var(--primary);
        }
        
        .logo span {
            color: var(--secondary);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 25px;
        }
        
        nav ul li a {
            color: var(--dark);
            font-weight: 500;
            padding: 5px 0;
            position: relative;
        }
        
        nav ul li a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background-color: var(--secondary);
            transition: width 0.3s ease;
        }
        
        nav ul li a:hover::after,
        nav ul li a.active::after 
		nav ul li a:focus::after{
            width: 100%;
        }
        
        .mobile-menu {
            display: none;
            font-size: 1.5rem;
            cursor: pointer;
            background: none;
            border: none;
            color: var(--primary);
            padding: 5px 10px;
            border-radius: 4px;
        }
		 .mobile-menu:hover, .mobile-menu:focus {
            background-color: var(--light);
            outline: 2px solid var(--secondary);
        }
        
        /* Loading Indicator */
        .loading-indicator {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, var(--secondary), var(--accent), var(--success));
            z-index: 9999;
            animation: loading 1.5s infinite;
        }
        
        .loading-indicator.active {
            display: block;
        }
        
        @keyframes loading {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(44, 62, 80, 0.8), rgba(44, 62, 80, 0.8)), url('images/hero-bg.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 120px 0;
        }
        
        .hero h2 {
            font-size: 2.8rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 30px;
        }
        
        /* Services Section */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background-color: #b4d6f2;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
			border-top: 4px solid var(--secondary);
        }
        
        .service-card:hover, .service-card:focus-within {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
        }
        
        .service-icon {
            background-color: var(--secondary);
            color: white;
            font-size: 2.5rem;
            padding: 25px;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .service-content {
            padding: 25px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
        }
        
        .service-content h3 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--primary);
            min-height: 42px;
            display: flex;
            align-items: center;
        }
        
        .service-content p {
            margin-bottom: 20px;
            flex-grow: 1;
            line-height: 1.7;
        }
        
        .service-content .btn {
            align-self: flex-start;
            margin-top: auto;
        }
        
        /* About Section */
        .about {
            background-color: var(--light);
        }
        
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }
        
        .about-text h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: var(--primary);
        }
        
        .about-text p {
            margin-bottom: 20px;
        }
        
        .about-image img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        /* Testimonials */
        .testimonials {
            background-color: white;
        }
        
        .testimonial-slider {
            max-width: 800px;
            margin: 0 auto;
            position: relative;
        }
        
        .testimonial {
            background-color: var(--light);
            padding: 30px;
            border-radius: 8px;
            text-align: center;
            margin: 0 15px;
        }
        
        .testimonial p {
            font-style: italic;
            margin-bottom: 20px;
        }
        
        .client-info {
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .client-info img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            margin-right: 15px;
        }
        
        .client-details h4 {
            margin-bottom: 5px;
            color: var(--primary);
        }
        
        /* CTA Section */
        .cta {
            background: linear-gradient(to right, var(--primary), var(--secondary));
            color: white;
            text-align: center;
            padding: 80px 0;
        }
        
        .cta h2 {
            font-size: 2.2rem;
            margin-bottom: 20px;
        }
        
        .cta p {
            max-width: 700px;
            margin: 0 auto 30px;
            font-size: 1.1rem;
        }
        
        /* Contact Form */
        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
        }
        
        .contact-info {
            background-color: var(--light);
            padding: 30px;
            border-radius: 8px;
			border-left: 4px solid var(--secondary);
        }
        
        .contact-info h3 {
            margin-bottom: 20px;
            color: var(--primary);
        }
        
        .contact-details {
            margin-bottom: 30px;
        }
        
        .contact-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 15px;
        }
        
        .contact-item i {
            margin-right: 15px;
            color: var(--secondary);
            font-size: 1.2rem;
            margin-top: 5px;
        }
        
        .contact-form {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }
        
        .form-control {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
            transition: border-color 0.3s ease;
        }
        
        .form-control:focus {
            border-color: var(--secondary);
            outline: none;
            box-shadow: 0 0 0 2px rgba(45, 90, 160, 0.2);
        }
        
        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }
        
        .form-status {
            padding: 10px;
            border-radius: 4px;
            margin-bottom: 15px;
            text-align: center;
            display: none;
        }
        
        .form-status.success {
            background-color: rgba(46, 204, 113, 0.2);
            color: var(--success);
            border: 1px solid var(--success);
            display: block;
        }
        
        .form-status.error {
            background-color: rgba(231, 76, 60, 0.2);
            color: var(--accent);
            border: 1px solid var(--accent);
            display: block;
        }
		 .form-status.warning {
            background-color: rgba(243, 156, 18, 0.2);
            color: var(--warning);
            border: 1px solid var(--warning);
            display: block;
        }
        
        /* Downloads Section */
        .downloads-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .download-card {
            background-color: #b4d6f2;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
			border-top: 4px solid var(--secondary);
        }
        
        .download-card:hover, .download-card:focus-within {
            transform: translateY(-5px);
        }
        
        .download-icon {
            background-color: var(--primary);
            color: white;
            font-size: 2rem;
            padding: 20px;
            text-align: center;
        }
        
        .download-content {
            padding: 25px;
        }
        
        .download-content h3 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--primary);
        }
        
        .download-meta {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            color: var(--text-light);
            font-size: 0.9rem;
        }
        
        /* Footer */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 40px 0 20px;
        }
        
        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            margin-bottom: 30px;
        }
        
        .social-links {
            display: flex;
            gap: 20px;
            margin-bottom: 25px;
        }
        
        .social-links a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 45px;
            height: 45px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            color: white;
            font-size: 1.2rem;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover, .social-links a:focus {
            background-color: var(--secondary);
            transform: translateY(-5px);
            outline: 2px solid white;
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #bdc3c7;
            font-size: 0.9rem;
        }
        
        /* Page-specific styles */
        .page-hero {
            background: linear-gradient(rgba(44, 62, 80, 0.8), rgba(44, 62, 80, 0.8)), url('images/hero-bg.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 80px 0;
        }
        
        .page-hero h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }
        
        .breadcrumb {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        .breadcrumb li {
            margin: 0 5px;
        }
        
        .breadcrumb li:not(:last-child)::after {
            content: '/';
            margin-left: 10px;
            color: #bdc3c7;
        }
        
        .breadcrumb a {
            color: #bdc3c7;
        }
        
        .breadcrumb a:hover, .breadcrumb a:focus {
            color: white;
        }
        
        /* Service Detail Page */
        .service-detail {
            margin-bottom: 50px;
            background: #b4d6f2;
            border-radius: 8px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
			border-left: 4px solid var(--secondary);
        }
        
        .service-detail-header {
            display: flex;
            align-items: center;
            margin-bottom: 25px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }
        
        .service-detail-icon {
            background-color: var(--secondary);
            color: white;
            width: 70px;
            height: 70px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 25px;
            font-size: 1.8rem;
            flex-shrink: 0;
        }
        
        .service-detail-content h2 {
            color: var(--primary);
            margin-bottom: 10px;
            font-size: 1.8rem;
        }
        
        .service-detail-content p {
            color: var(--text-light);
            font-size: 1.1rem;
        }
        
        .service-features {
            margin: 30px 0;
        }
        
        .service-features h3 {
            margin-bottom: 20px;
            color: var(--primary);
            font-size: 1.4rem;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--light);
        }
        
        .service-features ul {
            list-style: none;
            padding-left: 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 15px;
        }
        
        .service-features li {
            margin-bottom: 12px;
            position: relative;
            padding-left: 30px;
            line-height: 1.6;
        }
        
        .service-features li::before {
            content: '✓';
            color: var(--secondary);
            font-weight: bold;
            position: absolute;
            left: 0;
            font-size: 1.2rem;
        }
        
        /* Products Section */
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }
        
        .product-card {
            background-color: #b4d6f2;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
			border-top: 4px solid var(--secondary);
        }
        
        .product-card:hover, .product-card:focus-within {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }
        
        .product-image {
            height: 200px;
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: white;
        }
        
        .product-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .product-card:hover .product-image img,
        .product-card:focus-within .product-image img {
            transform: scale(1.05);
        }
        
        .product-content {
            padding: 25px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
        }
        
        .product-content h3 {
            font-size: 1.3rem;
            margin-bottom: 10px;
            color: var(--primary);
        }
        
        .product-content p {
            margin-bottom: 15px;
            flex-grow: 1;
            line-height: 1.6;
        }
        
        .product-price {
            font-size: 1.2rem;
            font-weight: bold;
            color: var(--accent);
            margin-bottom: 15px;
        }
        
        .product-links {
            display: flex;
            gap: 10px;
            margin-top: auto;
        }
        
        .product-links .btn {
            flex: 1;
            text-align: center;
            padding: 8px 15px;
            font-size: 0.9rem;
        }
        
        /* Responsive Styles */
        @media (max-width: 992px) {
            .about-content,
            .contact-container {
                grid-template-columns: 1fr;
            }
            
            .about-image {
                order: -1;
            }
            
            .service-features ul {
                grid-template-columns: 1fr;
            }
        }
        
        @media (max-width: 768px) {
            .mobile-menu {
                display: block;
            }
            
            nav {
                position: fixed;
                top: 70px;
                left: -100%;
                width: 80%;
                height: calc(100vh - 70px);
                background-color: white;
                transition: all 0.3s ease;
                box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
                z-index: 999;
            }
            
            nav.active {
                left: 0;
            }
            
            nav ul {
                flex-direction: column;
                padding: 20px;
            }
            
            nav ul li {
                margin: 0 0 15px 0;
            }
            
            .hero h2,
            .page-hero h1 {
                font-size: 2.2rem;
            }
            
            .section-title h2 {
                font-size: 1.8rem;
            }
            
            .service-detail-header {
                flex-direction: column;
                text-align: center;
            }
            
            .service-detail-icon {
                margin-right: 0;
                margin-bottom: 15px;
            }
            
            .product-links {
                flex-direction: column;
            }
        }
        
        @media (max-width: 576px) {
            .hero,
            .page-hero {
                padding: 60px 0;
            }
            
            .hero h2,
            .page-hero h1 {
                font-size: 1.8rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .services-grid,
            .downloads-grid,
            .products-grid {
                grid-template-columns: 1fr;
            }
            
            .social-links {
                gap: 15px;
            }
            
            .social-links a {
                width: 40px;
                height: 40px;
                font-size: 1.1rem;
            }
            
            .service-detail {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
	<!-- Loading Indicator -->
    <div class="loading-indicator" id="loadingIndicator"></div>
	
    <!-- Header -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <img src="icon.png" alt="Com-Craft Technologies - IT Solutions Company Logo">
                <h1>Com-<span>Craft</span> Tech</h1>
           </div>
            <button class="mobile-menu" id="mobileMenu" aria-label="Toggle navigation menu" aria-expanded="false" aria-controls="mainNav">
                ☰
            </button>
            <nav id="mainNav" role="navigation" aria-label="Main navigation">
                <ul>
                    <li><a href="index.html" class="active">Home</a></li>
                    <li><a href="services.html">IT Services</a></li>
                    <li><a href="products.html">IT Products</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                    <li><a href="downloads.html">Downloads</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Page-specific content will be inserted here by JavaScript -->
	<main id="page-content" role="main">
        <!-- This will be replaced with the actual page content -->
    </main>
    
    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="social-links">
                    <a href="https://facebook.com" target="_blank" aria-label="Follow us on Facebook"><i class="fab fa-facebook-f"></i></a>
                    <a href="https://twitter.com" target="_blank" aria-label="Follow us on Twitter"><i class="fab fa-twitter"></i></a>
                    <a href="https://linkedin.com" target="_blank" aria-label="Follow us on LinkedIn"><i class="fab fa-linkedin-in"></i></a>
                    <a href="https://youtube.com" target="_blank" aria-label="Subscribe to our YouTube channel"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2023 Com-Craft Technologies. All Rights Reserved. | Professional IT Solutions in Kenya</p>
            </div>
        </div>
    </footer>
    
    <script>
        // Initialize EmailJS when the page loads
        document.addEventListener('DOMContentLoaded', function() {
            emailjs.init("tYyX6qrOm4tG0OWHI");
            console.log('EmailJS initialized successfully');
        });

        // Enhanced Navigation System
        class PageNavigator {
            constructor() {
                this.pages = {
                    'index.html': this.getHomePage(),
                    'services.html': this.getServicesPage(),
                    'products.html': this.getProductsPage(),
                    'contact.html': this.getContactPage(),
                    'downloads.html': this.getDownloadsPage()
                };
                
                this.init();
            }
            
            init() {
                // Set up mobile menu
                this.setupMobileMenu();
                
                // Set up navigation for static elements
                this.setupStaticNavigation();
                
                // Load initial page
                this.loadPage(this.getCurrentPage());
            }
            
                        setupMobileMenu() {
                const mobileMenu = document.getElementById('mobileMenu');
                const nav = document.getElementById('mainNav');
                
                if (mobileMenu && nav) {
                    mobileMenu.addEventListener('click', () => {
                        const isExpanded = nav.classList.toggle('active');
                        mobileMenu.setAttribute('aria-expanded', isExpanded);
                    });
                    
                    // Add keyboard support for mobile menu
                    mobileMenu.addEventListener('keydown', (e) => {
                        if (e.key === 'Enter' || e.key === ' ') {
                            e.preventDefault();
                            mobileMenu.click();
                        }
                    });
                    
                    // Close mobile menu when clicking on a link
                    document.querySelectorAll('nav a').forEach(link => {
                        link.addEventListener('click', () => {
                            nav.classList.remove('active');
                            mobileMenu.setAttribute('aria-expanded', 'false');
                        });
                    });
                    
                    // Close mobile menu when clicking outside
                    document.addEventListener('click', (e) => {
                        if (!nav.contains(e.target) && !mobileMenu.contains(e.target)) {
                            nav.classList.remove('active');
                            mobileMenu.setAttribute('aria-expanded', 'false');
                        }
                    });
                }
            }
            
            setupStaticNavigation() {
                // Handle navigation clicks for static elements (header nav)
                document.querySelectorAll('nav a').forEach(link => {
                    link.addEventListener('click', (e) => {
                        const href = link.getAttribute('href');
                        
                        if (href.endsWith('.html')) {
                            // Page navigation
                            e.preventDefault();
                            this.navigateTo(href);
                        }
                    });
                });
                
                // Handle browser back/forward buttons
                window.addEventListener('popstate', () => {
                    this.loadPage(this.getCurrentPage());
                });
            }
            
            setupDynamicNavigation() {
                // Handle navigation for dynamically created buttons and links
                const pageContent = document.getElementById('page-content');
                if (pageContent) {
                    // Use event delegation for dynamic content
                    pageContent.addEventListener('click', (e) => {
                        const target = e.target;
                        
                        // Check if clicked element is a button or link
                        if (target.matches('.btn, a')) {
                            const href = target.getAttribute('href');
                            
                            if (href && href.startsWith('#')) {
                                // Internal page anchor
                                e.preventDefault();
                                this.scrollToSection(href);
                            } else if (href && href.endsWith('.html')) {
                                // Page navigation
                                e.preventDefault();
                                this.navigateTo(href);
                            } else if (href && href.includes('.html#')) {
                                // Cross-page navigation with hash (Learn More buttons)
                                e.preventDefault();
                                this.handleCrossPageNavigation(href);
                            }
                        }
                    });
                }
            }
            
            handleCrossPageNavigation(url) {
                // Split the URL into page and hash parts
                const [page, hash] = url.split('#');
                
                // Navigate to the page first
                this.navigateTo(page);
                
                // Store the hash to scroll to after page loads
                setTimeout(() => {
                    if (hash) {
                        this.scrollToSection('#' + hash);
                    }
                }, 300); // Small delay to allow page to render
            }
            
            setupForms() {
                // Wait a bit for DOM to be fully ready
                setTimeout(() => {
                    const contactForm = document.getElementById('contactForm');
                    if (contactForm) {
                        console.log('Setting up contact form');
                        
                        contactForm.addEventListener('submit', (e) => {
                            e.preventDefault();
                            this.handleFormSubmission(contactForm);
                        });
                    } else {
                        console.log('Contact form not found on this page');
                    }
                }, 100);
            }
            
             getCurrentPage() {
                return window.location.pathname.split('/').pop() || 'index.html';
            }
            
            navigateTo(page) {
                this.showLoadingIndicator();
                setTimeout(() => {
                    this.loadPage(page);
                    window.history.pushState({}, '', page);
                    document.title = this.getPageTitle(page);
                    this.hideLoadingIndicator();
                }, 300); // Simulate loading delay
            }
            
            showLoadingIndicator() {
                const loadingIndicator = document.getElementById('loadingIndicator');
                if (loadingIndicator) {
                    loadingIndicator.classList.add('active');
                }
            }
            
            hideLoadingIndicator() {
                const loadingIndicator = document.getElementById('loadingIndicator');
                if (loadingIndicator) {
                    loadingIndicator.classList.remove('active');
                }
            }
            
            loadPage(page) {
                const content = this.pages[page] || this.pages['index.html'];
                const pageContent = document.getElementById('page-content');
                
                if (pageContent) {
                    pageContent.innerHTML = content;
                    this.updateActiveNavLink(page);
                    
                    // Set up navigation for dynamic content AFTER loading
                    this.setupDynamicNavigation();
                    
                    // Set up forms AFTER loading
                    this.setupForms();
                    
                    // Scroll to section if URL has hash
                    if (window.location.hash) {
                        setTimeout(() => {
                            this.scrollToSection(window.location.hash);
                        }, 100);
                    }
                }
            }
            
            updateActiveNavLink(page) {
                document.querySelectorAll('nav a').forEach(link => {
                    link.classList.remove('active');
                    if (link.getAttribute('href') === page) {
                        link.classList.add('active');
                    }
                });
            }
            
            scrollToSection(sectionId) {
                const targetSection = document.querySelector(sectionId);
                if (targetSection) {
                    // Add a small offset for fixed header
                    const offsetTop = targetSection.offsetTop - 80;
                    
                    window.scrollTo({
                        top: offsetTop,
                        behavior: 'smooth'
                    });
                }
            }
            
            getPageTitle(page) {
                const titles = {
                    'index.html': 'Com-Craft Technologies - IT Solutions & IT Support Services in Kenya',
                    'services.html': 'IT Services in Kenya - CCTV Installation, Computer Repair & IT Support',
                    'products.html': 'IT Products & Hardware Solutions - Com-Craft Technologies Kenya',
                    'contact.html': 'Contact Us - IT Support Services in Nairobi, Kenya',
                    'downloads.html': 'IT Resources & Downloads - Com-Craft Technologies Kenya'
                };
                return titles[page] || 'Com-Craft Technologies - IT Solutions in Kenya';
            }
            
            handleFormSubmission(form) {
                console.log('Form submission started');
				
				// Enhanced error handling: Check if EmailJS is available
                if (typeof emailjs === 'undefined') {
                    this.showFormStatus(form, 'Email service is currently unavailable. Please contact us directly at info@comcraftech.co.ke or call +254 700 311 368', 'error');
                    return;
                }
                
                // Prevent multiple submissions
                const submitBtn = form.querySelector('button[type="submit"]');
                const originalText = submitBtn.textContent;
                
                // Show loading state
                submitBtn.textContent = 'Sending...';
                submitBtn.disabled = true;
                
                // Clear any previous status messages
                const existingStatus = form.querySelector('.form-status');
                if (existingStatus) {
                    existingStatus.remove();
                }
                
                const formData = new FormData(form);
                const data = Object.fromEntries(formData);
                
                console.log('Form data:', data);
				
				// Enhanced validation
                const validationErrors = this.validateFormData(data);
                if (validationErrors.length > 0) {
                    this.showFormStatus(form, validationErrors.join(' '), 'error');
                    submitBtn.textContent = originalText;
                    submitBtn.disabled = false;
                    return;
                }
                
                // EmailJS parameters
                const serviceId = 'service_zrdy92j';
                const templateId = 'template_2oqb8qh';
                
                // Send email using EmailJS with enhanced error handling
                emailjs.send(serviceId, templateId, {
                    from_name: data.name,
                    from_email: data.email,
                    phone: data.phone || 'Not provided',
                    service: data.service || 'General Inquiry',
                    message: data.message,
                    to_email: 'kilonzostephen441@gmail.com'
                })
                .then((response) => {
                    console.log('Email sent successfully!', response.status, response.text);
                    this.showFormStatus(form, 'Thank you for your message! We will get back to you within 24 hours.', 'success');
                    form.reset();
                }, (error) => {
                    console.error('Failed to send email:', error);
                    let errorMessage = 'Sorry, there was an error sending your message. ';
                    
                    if (error.text) {
                        errorMessage += `Error: ${error.text}. `;
                    }
                    
                    errorMessage += 'Please try again later or contact us directly at info@comcraftech.co.ke';
                    this.showFormStatus(form, errorMessage, 'error');
                })
                .finally(() => {
                    // Reset button state
                    submitBtn.textContent = originalText;
                    submitBtn.disabled = false;
                });
            }
            
            validateFormData(data) {
                const errors = [];
                
                // Name validation
                if (!data.name || data.name.trim().length < 2) {
                    errors.push('Please enter a valid name (at least 2 characters).');
                }
                
                // Email validation
                const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
                if (!data.email || !emailRegex.test(data.email)) {
                    errors.push('Please enter a valid email address.');
                }
                
                // Message validation
                if (!data.message || data.message.trim().length < 10) {
                    errors.push('Please enter a message with at least 10 characters.');
                }
                
                return errors;
            }
            
            showFormStatus(form, message, type) {
                // Remove any existing status messages
                const existingStatus = form.querySelector('.form-status');
                if (existingStatus) {
                    existingStatus.remove();
                }
                
                // Create status element
                const statusEl = document.createElement('div');
                statusEl.className = `form-status ${type}`;
                statusEl.textContent = message;
                statusEl.setAttribute('role', 'alert');
                statusEl.setAttribute('aria-live', 'polite');
                
                // Insert at the top of the form
                form.insertBefore(statusEl, form.firstChild);
                
                // Focus on the status message for screen readers
                statusEl.focus();
                
                // Auto-remove success messages after 5 seconds
                if (type === 'success') {
                    setTimeout(() => {
                        if (statusEl.parentNode) {
                            statusEl.remove();
                        }
                    }, 5000);
                }
            }
            
            // Page content generators
            getHomePage() {
                return `
                    <!-- Hero Section -->
                    <section class="hero">
                        <div class="container">
                            <h1>Professional IT Solutions & IT Support Services</h1>
                            <p>Com-Craft Technologies provides comprehensive IT services in Kenya including CCTV installation, computer maintenance, network solutions, and electronics repair for businesses and individuals in Nairobi and beyond.</p>
                            <a href="contact.html" class="btn btn-accent">Get IT Support Now</a>
                        </div>
                    </section>

                    <!-- Services Section -->
                    <section id="services">
                        <div class="container">
                            <div class="section-title">
                                <h2>Our IT Services in Kenya</h2>
                                <p>We offer a wide range of IT and electronics services to meet all your technology needs in Nairobi and throughout Kenya</p>
                            </div>
                            <div class="services-grid">
                                ${this.generateServiceCards()}
                            </div>
                        </div>
                    </section>

                    <!-- Products Preview Section -->
                    <section class="about">
                        <div class="container">
                            <div class="section-title">
                                <h2>IT Products & Hardware Solutions</h2>
                                <p>Quality IT hardware and software solutions for your business in Kenya</p>
                            </div>
                            <div class="products-grid">
                                ${this.generateProductCards().slice(0, 3)}
                            </div>
                            <div style="text-align: center; margin-top: 30px;">
                                <a href="products.html" class="btn">View All IT Products</a>
                            </div>
                        </div>
                    </section>

                    <!-- About Section -->
                    <section class="about">
                        <div class="container">
                            <div class="about-content">
                                <div class="about-text">
                                    <h2>About Com-Craft Technologies - IT Solutions Provider in Kenya</h2>
                                    <p>Com-Craft Technologies is a trusted provider of comprehensive IT solutions in Kenya, serving both residential and commercial clients in Nairobi and beyond. With years of experience in the IT industry, we have built a reputation for reliability, expertise, and exceptional customer service.</p>
                                    <p>Our team of certified IT professionals is dedicated to delivering cutting-edge technology solutions that meet the unique needs of each client in Kenya. We stay current with the latest industry trends and technologies to ensure we provide the most effective and efficient IT services.</p>
                                    <p>At Com-Craft Technologies, we believe in building long-term relationships with our clients by providing reliable IT support and innovative solutions that help businesses thrive in today's digital landscape in Kenya.</p>
                                    <a href="contact.html" class="btn">Contact Our IT Team</a>
                                </div>
                                <div class="about-image">
                                    <img src="images/about-team.jpg" alt="Com-Craft Technologies IT Support Team in Kenya">
                                </div>
                            </div>
                        </div>
                    </section>

                    <!-- Testimonials Section -->
                    <section class="testimonials">
                        <div class="container">
                            <div class="section-title">
                                <h2>What Our Kenyan Clients Say</h2>
                                <p>We take pride in the positive feedback we receive from our satisfied customers across Kenya</p>
                            </div>
                            <div class="testimonial-slider">
                                <div class="testimonial">
                                    <p>"Com-Craft Technologies installed a comprehensive CCTV system for our retail store in Nairobi. Their professionalism and attention to detail were impressive. The system has significantly improved our security."</p>
                                    <div class="client-info">
                                        <img src="images/client1.jpg" alt="John Mwangi - Retail Business Owner in Kenya">
                                        <div class="client-details">
                                            <h4>John Mwangi</h4>
                                            <p>Retail Business Owner, Nairobi</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>

                    <!-- CTA Section -->
                    <section class="cta">
                        <div class="container">
                            <h2>Ready to Enhance Your IT Infrastructure in Kenya?</h2>
                            <p>Contact Com-Craft Technologies today for reliable IT solutions tailored to your specific needs in Kenya. Our IT team is ready to assist you with all your technology requirements.</p>
                            <a href="contact.html" class="btn btn-accent">Get A Free IT Consultation</a>
                        </div>
                    </section>
                `;
            }
            
            generateServiceCards() {
                const services = [
                    { icon: 'video', title: 'CCTV Installation', desc: 'Professional CCTV and surveillance network installation for homes and businesses in Nairobi and throughout Kenya.', link: 'services.html#cctv' },
                    { icon: 'laptop', title: 'Computer Repair', desc: 'Comprehensive computer repair and maintenance services to keep your systems running smoothly across Kenya.', link: 'services.html#maintenance' },
                    { icon: 'code', title: 'Software Solutions', desc: 'Custom software development and installation services to enhance your business operations in Kenya.', link: 'services.html#software' },
                    { icon: 'network-wired', title: 'Network Installation', desc: 'Professional computer network installations and reliable internet provision services throughout Kenya.', link: 'services.html#network' },
                    { icon: 'headset', title: 'IT Support', desc: 'Comprehensive IT support services to resolve your technical issues quickly and efficiently across Kenya.', link: 'services.html#support' },
                    { icon: 'bolt', title: 'Electronics Repair', desc: 'Expert electrical and electronics repair and maintenance services for all your devices in Kenya.', link: 'services.html#electronics' }
                ];
                
                return services.map(service => `
                    <div class="service-card">
                        <div class="service-icon">
                            <i class="fas fa-${service.icon}"></i>
                        </div>
                        <div class="service-content">
                            <h3>${service.title}</h3>
                            <p>${service.desc}</p>
                            <a href="${service.link}" class="btn">Learn More</a>
                        </div>
                    </div>
                `).join('');
            }
            
            getServicesPage() {
                return `
                    <!-- Page Hero -->
                    <section class="page-hero">
                        <div class="container">
                            <h1>IT Services in Kenya - Professional IT Solutions</h1>
                            <ul class="breadcrumb">
                                <li><a href="index.html">Home</a></li>
                                <li>IT Services</li>
                            </ul>
                        </div>
                    </section>

                    <!-- Services Detail Section -->
                    <section>
                        <div class="container">
                            <div class="section-title">
                                <h2>Comprehensive IT Solutions</h2>
                                <p>We offer a complete range of IT services to meet all your technology needs in Nairobi and throughout Kenya</p>
                            </div>
                            ${this.generateServiceDetails()}
                        </div>
                    </section>
                `;
            }

            generateServiceDetails() {
                const services = [
                    { 
                        id: 'cctv', 
                        icon: 'video', 
                        title: 'CCTV Installation', 
                        subtitle: 'Professional surveillance solutions for enhanced securit',
                        description: 'Our CCTV installation service provides comprehensive security solutions for both residential and commercial properties across Kenya. We design, install, and maintain surveillance systems that meet your specific security needs in Nairobi and throughout the country.',
                        featuresTitle: 'What We Offer in Kenya:',
                        features: [
                            'High-definition CCTV camera installation in Kenya',
                            'Surveillance network setup and configuration',
                            'Remote monitoring solutions for Kenyan businesses',
                            'Motion detection and alert systems',
                            'Night vision capabilities',
                            'Cloud and local storage options',
                            'Regular maintenance and support across Kenya'
                        ]
                    },
                    { 
                        id: 'maintenance', 
                        icon: 'laptop', 
                        title: 'Computer Maintenance & Repair', 
                        subtitle: 'Keep your systems running at peak performance',
                        description: 'Our computer maintenance and repair services ensure your systems operate efficiently and reliably across Kenya. We offer both on-site and remote support to address any IT issues promptly in Nairobi and throughout the country.',
                        featuresTitle: 'Our Computer Services in Kenya Include:',
                        features: [
                            'Hardware diagnostics and repair',
                            'Virus and malware removal for Kenyan businesses',
                            'OS installation and optimization',
                            'Data backup and recovery services in Kenya',
                            'Performance tuning',
                            'Component upgrades',
                            'Preventive maintenance programs for Kenyan organizations'
                        ]
                    },
                    { 
                        id: 'software', 
                        icon: 'code', 
                        title: 'Software Solutions', 
                        subtitle: 'Custom and off-the-shelf software to meet your needs',
                        description: 'We provide software solutions tailored to your business requirements in Kenya, from installation and configuration to custom development and integration for businesses in Nairobi and beyond.',
                        featuresTitle: 'Our Software Services:',
                        features: [
                            'Custom software development for Kenyan businesses',
                            'Business application installation',
                            'Database design and management',
                            'Software integration services in Kenya',
                            'Mobile app development',
                            'Web application development for Kenyan companies',
                            'Software training and support'
                        ]
                    },
                    { 
                        id: 'network', 
                        icon: 'network-wired', 
                        title: 'Network Installation & Internet', 
                        subtitle: 'Reliable connectivity solutions for your business',
                        description: 'We design and implement robust network infrastructures that ensure seamless connectivity and optimal performance for your business operations across Kenya, with a focus on reliable solutions for Nairobi businesses.',
                        featuresTitle: 'Network Services in Kenya:',
                        features: [
                            'Local Area Network (LAN) setup in Kenya',
                            'Wireless network installation',
                            'Network security implementation for Kenyan businesses',
                            'Internet connectivity solutions',
                            'VPN setup and configuration',
                            'Network monitoring and management',
                            'Cloud network integration services in Kenya'
                        ]
                    },
                    { 
                        id: 'support', 
                        icon: 'headset', 
                        title: 'IT Support', 
                        subtitle: 'Comprehensive technical support when you need it',
                        description: 'Our IT support services provide timely assistance for all your technology issues across Kenya, ensuring minimal downtime and maximum productivity for your business in Nairobi and throughout the country.',
                        featuresTitle: 'IT Support Options:',
                        features: [
                            '24/7 Helpdesk support for Kenyan businesses',
                            'On-site technical assistance in Nairobi',
                            'Remote troubleshooting',
                            'IT consulting and planning for Kenyan organizations',
                            'System audits and assessments',
                            'Disaster recovery planning',
                            'Managed IT services in Kenya'
                        ]
                    },
                    { 
                        id: 'electronics', 
                        icon: 'bolt', 
                        title: 'Electrical & Electronics Repair', 
                        subtitle: 'Expert repair services for all your electronic devices',
                        description: 'We offer comprehensive repair and maintenance services for a wide range of electrical and electronic equipment across Kenya, from office devices to specialized industrial equipment in Nairobi and beyond.',
                        featuresTitle: 'Electronics Repair Services:',
                        features: [
                            'Printer and scanner repair in Kenya',
                            'Power supply unit servicing',
                            'UPS system maintenance for Kenyan businesses',
                            'Electronic circuit board repair',
                            'Office equipment servicing in Nairobi',
                            'Industrial electronics maintenance',
                            'Warranty and non-warranty repairs across Kenya'
                        ]
                    }
                ];
                
                return services.map(service => `
                    <div class="service-detail" id="${service.id}">
                        <div class="service-detail-header">
                            <div class="service-detail-icon">
                                <i class="fas fa-${service.icon}"></i>
                            </div>
                            <div class="service-detail-content">
                                <h2>${service.title}</h2>
                                <p>${service.subtitle}</p>
                            </div>
                        </div>
                        <p>${service.description}</p>
                        
                        <div class="service-features">
                            <h3>${service.featuresTitle}</h3>
                            <ul>
                                ${service.features.map(feature => `<li>${feature}</li>`).join('')}
                            </ul>
                        </div>
                    </div>
                `).join('');
            }
            
            getProductsPage() {
                return `
                    <!-- Page Hero -->
                    <section class="page-hero">
                        <div class="container">
                            <h1>IT Products & Hardware Solutions in Kenya</h1>
                            <ul class="breadcrumb">
                                <li><a href="index.html">Home</a></li>
                                <li>IT Products</li>
                            </ul>
                        </div>
                    </section>

                    <!-- Products Section -->
                    <section>
                        <div class="container">
                            <div class="section-title">
                                <h2>IT Hardware & Software Solutions in Kenya</h2>
                                <p>We offer a wide range of quality IT products to meet your business needs in Kenya</p>
                            </div>
                            
                            <div class="products-grid">
                                ${this.generateProductCards()}
                            </div>
                        </div>
                    </section>
                `;
            }
            
            generateProductCards() {
                const products = [
                    { 
                        id: 'cctv-camera', 
                        image: 'images/cctv-camera.jpg',
                        title: 'HD CCTV Camera System Kenya', 
                        desc: 'High-definition security camera system with night vision and remote monitoring capabilities for Kenyan homes and businesses.',
                        price: 'KSh 25,000',
                        jiji: 'https://Jiji.co.ke',
                        jumia: 'https://jumia.co.ke'
                    },
                    { 
                        id: 'laptop', 
                        image: 'images/laptop.jpg',
                        title: 'Business Laptop Kenya', 
                        desc: 'High-performance laptop with latest processor, perfect for business and professional use in Kenya.',
                        price: 'KSh 65,000',
                        jiji: 'https://Jiji.co.ke',
                        jumia: 'https://jumia.co.ke'
                    },
                    { 
                        id: 'router', 
                        image: 'images/router.jpg',
                        title: 'Wireless Router Kenya', 
                        desc: 'High-speed dual-band wireless router for reliable home or office networking in Kenya.',
                        price: 'KSh 8,500',
                        jiji: 'https://Jiji.co.ke',
                        jumia: 'https://jumia.co.ke'
                    },
                    { 
                        id: 'software', 
                        image: 'images/software.jpg',
                        title: 'Business Software Suite Kenya', 
                        desc: 'Comprehensive business software package including accounting, inventory, and CRM modules for Kenyan businesses.',
                        price: 'KSh 15,000',
                        jiji: 'https://Jiji.co.ke',
                        jumia: 'https://jumia.co.ke'
                    },
                    { 
                        id: 'ups', 
                        image: 'images/ups.jpg',
                        title: 'UPS System Kenya', 
                        desc: 'Uninterruptible Power Supply system to protect your equipment from power fluctuations in Kenya.',
                        price: 'KSh 12,000',
                        jiji: 'https://Jiji.co.ke',
                        jumia: 'https://jumia.co.ke'
                    },
                    { 
                        id: 'printer', 
                        image: 'images/printer.jpg',
                        title: 'All-in-One Printer Kenya', 
                        desc: 'Multifunction printer with printing, scanning, and copying capabilities for office use in Kenya.',
                        price: 'KSh 18,500',
                        jiji: 'https://Jiji.co.ke',
                        jumia: 'https://jumia.co.ke'
                    }
                ];
                
                return products.map(product => `
                    <div class="product-card" id="${product.id}">
                        <div class="product-image">
                            <img src="${product.image}" alt="${product.title}">
                        </div>
                        <div class="product-content">
                            <h3>${product.title}</h3>
                            <p>${product.desc}</p>
                            <div class="product-price">${product.price}</div>
                            <div class="product-links">
                                <a href="${product.jiji}" target="_blank" class="btn btn-jiji">Buy on Jiji</a>
                                <a href="${product.jumia}" target="_blank" class="btn btn-accent">Buy on Jumia</a>
                            </div>
                        </div>
                    </div>
                `).join('');
            }
            
            getContactPage() {
                return `
                    <!-- Page Hero -->
                    <section class="page-hero">
                        <div class="container">
                            <h1>Contact Us - IT Support Services in Kenya</h1>
                            <ul class="breadcrumb">
                                <li><a href="index.html">Home</a></li>
                                <li>Contact</li>
                            </ul>
                        </div>
                    </section>

                    <!-- Contact Section -->
                    <section>
                        <div class="container">
                            <div class="section-title">
                                <h2>Get IT Support in Kenya</h2>
                                <p>We're here to help with all your IT needs in Kenya. Contact us today for an IT consultation.</p>
                            </div>
                            
                            <div class="contact-container">
                                <div class="contact-info">
                                    <h3>Contact Information - Kenya</h3>
                                    <div class="contact-details">
                                        <div class="contact-item">
                                            <i class="fas fa-map-marker-alt"></i>
                                            <div>
                                                <h4>Our Location in Kenya</h4>
                                                <p>Nairobi, Kenya</p>
                                            </div>
                                        </div>
                                        <div class="contact-item">
                                            <i class="fas fa-phone"></i>
                                            <div>
                                                <h4>Phone Number Kenya</h4>
                                                <p>+254 700 311 368</p>
                                            </div>
                                        </div>
                                        <div class="contact-item">
                                            <i class="fas fa-envelope"></i>
                                            <div>
                                                <h4>Email Address Kenya</h4>
                                                <p>info@comcraftech.co.ke</p>
                                            </div>
                                        </div>
                                        <div class="contact-item">
                                            <i class="fas fa-clock"></i>
                                            <div>
                                                <h4>Working Hours Kenya</h4>
                                                <p>Monday - Friday: 8:00 AM - 6:00 PM</p>
                                                <p>Saturday: 8:00 AM - 6:00 PM</p>
                                            </div>
                                        </div>
                                    </div>
                                    
                                    <h3>Why Choose Our IT Services in Kenya?</h3>
                                    <ul class="service-features">
                                        <li>Experienced and certified IT technicians in Kenya</li>
                                        <li>Quick response times across Kenya</li>
                                        <li>Competitive pricing for Kenyan businesses</li>
                                        <li>Quality IT service guarantee</li>
                                        <li>24/7 emergency IT support available in Kenya</li>
                                    </ul>
                                </div>
                                
                                <div class="contact-form">
                                    <h3>Send Us a Message - Kenya</h3>
                                    <form id="contactForm">
                                        <div class="form-group">
                                            <label for="name">Your Name *</label>
                                            <input type="text" id="name" name="name" class="form-control" required>
                                        </div>
                                        <div class="form-group">
                                            <label for="email">Email Address *</label>
                                            <input type="email" id="email" name="email" class="form-control" required>
                                        </div>
                                        <div class="form-group">
                                            <label for="phone">Phone Number Kenya</label>
                                            <input type="tel" id="phone" name="phone" class="form-control">
                                        </div>
                                        <div class="form-group">
                                            <label for="service">IT Service Interested In</label>
                                            <select id="service" name="service" class="form-control">
                                                <option value="">Select an IT service</option>
                                                <option value="cctv">CCTV Installation Kenya</option>
                                                <option value="maintenance">Computer Repair Kenya</option>
                                                <option value="software">Software Solutions Kenya</option>
                                                <option value="network">Network Installation Kenya</option>
                                                <option value="support">IT Support Kenya</option>
                                                <option value="electronics">Electronics Repair Kenya</option>
                                            </select>
                                        </div>
                                        <div class="form-group">
                                            <label for="message">Your IT Requirements *</label>
                                            <textarea id="message" name="message" class="form-control" required></textarea>
                                        </div>
                                        <button type="submit" class="btn btn-accent">Send Message to Our IT Team</button>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </section>
                `;
            }
            
            getDownloadsPage() {
                return `
                    <!-- Page Hero -->
                    <section class="page-hero">
                        <div class="container">
                            <h1>IT Resources & Downloads</h1>
                            <ul class="breadcrumb">
                                <li><a href="index.html">Home</a></li>
                                <li>IT Resources</li>
                            </ul>
                        </div>
                    </section>

                    <!-- Downloads Section -->
                    <section>
                        <div class="container">
                            <div class="section-title">
                                <h2>IT Resources & Downloads</h2>
                                <p>Access useful IT resources, software tools, and documentation for our services</p>
                            </div>
                            
                            <div class="downloads-grid">
                                ${this.generateDownloadCards()}
                            </div>
                        </div>
                    </section>
                `;
            }
            
            generateDownloadCards() {
                const downloads = [
                    { 
                        icon: 'file-pdf', 
                        title: 'IT Service Catalog Kenya', 
                        desc: 'Complete catalog of all our IT services in Kenya with detailed descriptions and pricing information.', 
                        meta: 'PDF, 370.9 KB',
                        link: 'downloads/IT_Service_Catalog_Kenya.pdf'
                    },
                    { 
                        icon: 'tools', 
                        title: 'Network Diagnostic Tool', 
                        desc: 'Our proprietary tool for diagnosing network issues and optimizing performance in Kenya.', 
                        meta: 'EXE, 1.59 GB',
                        link: 'https://icedrive.net/s/FfuhGh2GZAB9VZF7Cjz6VVt14iND'
                    },
                    { 
                        icon: 'book', 
                        title: 'CCTV Setup Guide Kenya', 
                        desc: 'Step-by-step guide for setting up and maintaining your CCTV surveillance system in Kenya.', 
                        meta: 'PDF, 207.4 KB',
                        link: 'downloads/CCTV_Setup_Guide_Kenya.pdf'
                    },
                    { 
                        icon: 'shield-alt', 
                        title: 'Security Best Practices Kenya', 
                        desc: 'Comprehensive guide to cybersecurity best practices for Kenyan businesses and individuals.', 
                        meta: 'PDF, 208.9 KB',
                        link: 'downloads/Security_Best_Practices_Kenya.pdf'
                    },
                    { 
                        icon: 'desktop', 
                        title: 'PC Maintenance Toolkit', 
                        desc: 'Collection of essential tools for computer maintenance and optimization in Kenya.', 
                        meta: 'ZIP, 245.5 MB',
                        link: 'https://icedrive.net/s/Wjk27gixxBiGR4agPx8vS23XSg14'
                    },
                    { 
                        icon: 'file-contract', 
                        title: 'IT Service Agreement Kenya', 
                        desc: 'Standard service agreement template for our IT support and maintenance services in Kenya.', 
                        meta: 'DOCX, 21.9 KB',
                        link: 'downloads/IT_Service_Agreement_Kenya.docx'
                    }
                ];
                
                return downloads.map(download => `
                    <div class="download-card">
                        <div class="download-icon">
                            <i class="fas fa-${download.icon}"></i>
                        </div>
                        <div class="download-content">
                            <h3>${download.title}</h3>
                            <p>${download.desc}</p>
                            <div class="download-meta">
                                <span>${download.meta}</span>
                                <a href="${download.link}" class="btn btn-jiji">Download IT Resource</a>
                            </div>
                        </div>
                    </div>
                `).join('');
            }
        }

        // Initialize the navigation system when the page loads
        document.addEventListener('DOMContentLoaded', () => {
            new PageNavigator();
        });
    </script>
</body>
</html>
