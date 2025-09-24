CashConverter – Currency Converter Web App
Overview

CashConverter is a simple, user-friendly web application that allows users to convert a specified quantity of money from one currency to various other currencies. The application fetches real-time exchange rates from a public API and displays the converted values in a clear tabular format.

Features

Input any quantity of money for conversion.

Select a base currency (Indian Rupee, US Dollar, Euro, etc.).

Display converted values for multiple currencies.

Real-time currency exchange rates using an external API.

Responsive design for mobile and desktop devices.

Interactive and dynamic output table.

Smooth animations for form and output table.

Modern gradients and styled buttons for an engaging UI.

Demo

Users can:

Enter a quantity in the input field.

Select the base currency from a dropdown.

Click Submit to see the converted values in a table.

Technologies Used

HTML – Structure and layout of the web page.

CSS – Styling for a modern, responsive, and animated interface.

JavaScript – Dynamic fetching of currency data and rendering results.

Currency API – Provides real-time exchange rates.
Usage

Open the web app in any modern browser.

Enter the amount to convert in the input field.

Select the base currency from the dropdown.

Click Submit.

View the converted values in the table below the form.

API Integration

The project uses the Currency API
 to fetch live currency exchange rates.

Make sure to replace the API key in main.js with your own valid API key:

url = "https://api.currencyapi.com/v3/latest?apikey=YOUR_API_KEY&base_currency=" + currency

Styling

Fonts: Uses Google Fonts (Poppins) for a modern look.

Layout: Flexbox used for navigation, container, and responsive design.

Forms: Rounded inputs with padding, focus highlights, and compact layout.

Buttons: Gradient backgrounds with hover effects and smooth scaling animations.

Output Table: Responsive, centered, and styled with shadows and alternating colors.

Animations: Fade-in and slide-up effects for the form and output table.

Responsive Design: Mobile-friendly layout with media queries.

Form View:


Enter quantity, select currency, click submit.

Converted Output Table:


Shows converted values in multiple currencies with a clean table layout.

Tip: Add screenshots to a screenshots folder in your project directory.

File Structure
CashConverter/
│
├── index.html      # Main HTML file
├── main.js         # JavaScript logic for fetching and displaying currency data
├── style2.css      # Additional stylesheet 
└── README.md       # Project documentation
