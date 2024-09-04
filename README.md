# Currency Calculator
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=livechat)](https://davishkar.github.io/Currency-Calculator/)
## Overview

Currency Calculator is a simple web application that allows users to convert an amount from one currency to another using live exchange rates. The application fetches exchange rates from an external API and provides the converted value instantly.

## Features

- **Live Currency Conversion**: Converts currency amounts using the latest exchange rates from an external API.
- **Responsive Design**: The user interface is optimized for both desktop and mobile devices.
- **User-Friendly Interface**: Simple and clean design with easy-to-use input fields and buttons.

## Technologies Used

- **HTML5**: Markup language for structuring the web page.
- **CSS3**: For styling the application and creating a responsive layout.
- **JavaScript**: To handle the form submission, fetch exchange rates from an API, and update the DOM with the converted value.
- **Exchange Rate API**: External API for fetching the latest currency exchange rates.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/currency-calculator.git
 ```
2. **Navigate to the project directory:**
   ```bash
   cd currency-calculator
   ```
3. **Open `index.html` in your web browser:**
   ```bash
   open index.html
   ```

## Usage

1. **Enter the amount** you want to convert in the "Amount" field.
2. **Select the currency** you want to convert from in the "From" dropdown.
3. **Select the currency** you want to convert to in the "To" dropdown.
4. **Click "Convert"** to see the converted amount displayed below the form.

## Customization

- **Currencies**: You can add or remove currencies by editing the `<select>` elements in the `index.html` file.
- **Styling**: Modify the `style.css` file to change the look and feel of the application.
- **API**: The current setup uses the Exchange Rate API. You can switch to a different API by modifying the `apiUrl` in the `script.js` file.

## Future Enhancements

- **Error Handling**: Add more detailed error messages for different scenarios (e.g., API down, invalid input).
- **Caching**: Implement caching to reduce the number of API calls.
- **Multiple Conversions**: Allow users to convert between multiple currencies in one go.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
