Currency Converter

This is a simple React Native application for converting currency amounts between different currencies using locally defined exchange rates. The app uses a `Picker` for selecting currencies and a `TextInput` for entering the amount to be converted.

Features

- Convert amounts between USD, EUR, GBP, and LKR.
- Locally defined exchange rates for offline functionality.
- Simple and user-friendly interface.
Prerequisites

Before running this application, ensure that you have the following installed:

- Node.js and npm
- React Native CLI
- A code editor, such as Visual Studio Code

Installation

1. Clone the repository:
   ```bash
   git clone <Day10-Currency-covert-app>
   ```

2. Navigate to the project directory:
   ```bash
   cd currency-converter
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

File Structure

- `App.js`: Main entry point of the application.
- `CurrencyConverter.js`: Contains the main currency converter component and logic.
- `styles`: Includes styles for the app.

 Exchange Rates

Exchange rates are defined locally within the application as a JavaScript object:

javascript
const exchangeRates = {
    USD: { USD: 1, EUR: 0.85, GBP: 0.75, LKR: 320 },
    EUR: { USD: 1.18, EUR: 1, GBP: 0.88, LKR: 375 },
    GBP: { USD: 1.33, EUR: 1.14, GBP: 1, LKR: 425 },
    LKR: { USD: 0.0031, EUR: 0.0027, GBP: 0.0024, LKR: 1 },
};

 Customization

- To add new currencies, update the `exchangeRates` object in `CurrencyConverter.js`.
- Modify styles in the `StyleSheet` section to customize the appearance.


