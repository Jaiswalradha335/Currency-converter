Overview
This Currency Converter is a simple web application developed using HTML, CSS, and JavaScript. It allows users to convert between different currencies based on the latest exchange rates.

Features
User-friendly interface
Real-time exchange rate updates
Support for multiple currencies
Responsive design for a seamless user experience on various devices
Technologies Used
HTML
CSS
JavaScript

How to Use
Clone the repository to your local machine.

git clone https://github.com/your-jaiswalradha/currency-converter.git
Open the project folder in your preferred code editor.

Run the index.html file in a web browser to launch the Currency Converter.

Enter the amount you want to convert in the enter amount field.

Select the source currency from the dropdown menu.

Choose the target currency from the second  To dropdown menu.

Click the "Exchange Rate" button to see the converted amount.

The application will display the result below the conversion button.

Customization
You can customize the list of supported currencies by modifying the currencies array in the script.js file.
javascript
const currencies = [
    { code: 'USD', name: 'US Dollar' },
    { code: 'EUR', name: 'Euro' },
    // Add or remove currencies as needed
];
Dependencies
No external libraries or frameworks are used in this project. The exchange rates are fetched from a free and public API.

Credits
Exchange rates are fetched from ExchangeRate-API.
