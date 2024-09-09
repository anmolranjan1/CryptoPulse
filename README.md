# CryptoPulse

**CryptoPulse** is a dynamic cryptocurrency price tracking application built with React JS and the CoinGecko API. It provides real-time price updates, detailed coin information, and intuitive charting features for cryptocurrency enthusiasts and investors.

## Features

- **Real-Time Price Updates:** Get live updates of cryptocurrency prices using the CoinGecko API.
- **Search Functionality:** Easily search for specific cryptocurrencies and view their details.
- **Coin Details Page:** Access comprehensive information about each cryptocurrency.
- **Price Chart:** Visualize historical price trends with interactive charts.
- **Responsive Design:** Accessible and functional across various devices and screen sizes.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/anmolranjan1/CryptoPulse.git
   cd CryptoPulse
   ```
2. **Create a .env File:**
- Go to the [CoinGecko API page](https://www.coingecko.com/en/api) to obtain your API key.
- Create a file named `.env` in the root directory of your project.
- Add your API key to the `.env` file:
  ```plaintext
  COINGECKO_API_KEY=your_api_key_here
  ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Start the Development Server:
    ```
    npm run dev
    ```
Open http://localhost:5173 in your browser to view the application.

## Usage
- **Home Page:** View current prices and trends of various cryptocurrencies.
- **Search Feature:** Use the search bar to find and view details of specific cryptocurrencies.
- **Coin Details Page:** Access detailed information including historical data and price charts.

## API Integration
The app uses the CoinGecko API to fetch real-time cryptocurrency data. Ensure that you adhere to the API usage guidelines and rate limits.

