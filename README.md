# INGCO Mohammedia: online catalog with WhatsApp ordering

A bilingual (French / Arabic) catalog website for INGCO Mohammedia, a tools and equipment store with branches in Mohammedia, Morocco. Customers browse about 600 products, fill a cart, and send the order to the branch of their choice on WhatsApp. Payment happens offline, so the site needs no online payment system and no staff to manage accounts.

**Live site:** https://ingco-mohammedia.company

![Home page screenshot](screenshots/home.png)

## Features

- **Catalog of about 600 products** in 20 categories, each with its reference, name, description and photo (no prices shown, by design)
- **Search** across the whole catalog
- **French and Arabic** interface, switched with one button
- **Cart**: add, remove and change quantities
- **WhatsApp checkout**: the cart becomes a ready-to-send WhatsApp message to the chosen branch
- **Branch section** with a Google map, tap-to-call number, directions and a WhatsApp button for each branch
- **Responsive design** for phones and computers, in the brand's orange and black

## How it was built

- **Front end:** HTML, CSS and JavaScript, as a static site with no server or database
- **Product data:** the 600 products were extracted from the store's PDF price list with a Python script (PyMuPDF), which read each table row and cropped each product photo
- **Hosting:** Netlify (free plan), updated by uploading a new build
- **Marketing:** connected to a Google Ads campaign and the store's Google Business Profile

## What I learned

- Turning a real business need (taking orders without online payment) into a simple, working product
- Extracting structured data from a messy PDF
- Building a bilingual French / Arabic interface
- Deploying and updating a live website, and connecting a domain and ads to it
