# Currency Converter

A simple currency converter web application that allows users to convert amounts between different currencies. The application uses a live exchange rate API to fetch the latest conversion rates and displays flags corresponding to the selected currencies.

## Features

- Convert amounts between various currencies.
- Automatically fetches the latest exchange rates.
- Displays country flags for selected currencies.
- User-friendly interface.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Technologies Used](#technologies-used)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/currency-converter.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd currency-converter
    ```

3. **Open the project in your favorite code editor.**

## Usage

1. **Open `index.html` in your web browser:**
    - Double-click the `index.html` file or
    - Right-click and select "Open with" and choose your browser.

2. **Enter the amount to convert:**
    - Enter the amount you wish to convert in the "Enter Amount" field.

3. **Select the currencies:**
    - Choose the currency you want to convert from and the currency you want to convert to from the dropdown menus.

4. **Get the exchange rate:**
    - Click the "Get Exchange Rate" button to see the converted amount and exchange rate.

## Files

- `index.html`: The main HTML file containing the structure of the web application.
- `style.css`: The CSS file for styling the web application.
- `app.js`: The JavaScript file containing the logic for fetching exchange rates and updating the UI.
- `countryList.js`: The JavaScript file containing the mapping of currency codes to country codes.

## Technologies Used

- HTML
- CSS
- JavaScript
- [Exchange Rate API](https://www.exchangerate-api.com/)
- [Font Awesome](https://fontawesome.com/)

## API

The application uses the [Exchange Rate API](https://www.exchangerate-api.com/) to fetch the latest currency conversion rates. The base URL for the API is:
```sh
https://api.exchangerate-api.com/v4/latest/
```

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.
