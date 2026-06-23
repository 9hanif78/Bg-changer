# Currency Converter

A simple, fast, and responsive currency converter built with React and Tailwind CSS. This project uses a real-time exchange rate API to provide accurate and up-to-date currency conversions between different countries.

## Features

- Real-time currency conversion using API data
- Supports multiple global currencies
- Swap currencies instantly
- Clean and minimal UI
- Fully responsive design for all devices
- Fast and lightweight performance

## Tech Stack

- React
- Tailwind CSS
- JavaScript (ES6+)
- REST API (Exchange Rate API or similar)
- Vite (optional but recommended)

## How It Works

The app fetches live exchange rates from an external API and updates conversion values instantly as the user changes input or selects different currencies. This ensures accurate and real-world conversion results.

## Preview

Users can:
- Enter an amount
- Select source currency
- Select target currency
- Get instant converted value

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/currency-converter.git
Navigate to project directory
cd currency-converter
Install dependencies
npm install
Run the development server
npm run dev

Then open:

http://localhost:5173
API Integration

This project uses a third-party exchange rate API to fetch live currency data.

Example flow:

Send request to API
Receive latest exchange rates
Update UI dynamically based on user input
Why This Project?

This project was built to practice:

Working with APIs in React
Handling asynchronous data (fetch / axios)
State management using hooks
Real-time UI updates
Clean UI design with Tailwind CSS

It also simulates a real-world financial tool used for quick currency conversions.

Future Improvements
Add historical exchange rate charts
Add search for currencies
Offline caching for last fetched rates
Dark mode support
Favorite currency pairs
Better error handling for API failures
Learning Outcomes

Through this project, I improved my understanding of:

React hooks (useState, useEffect)
API integration and data fetching
Conditional rendering
Component-based architecture
Responsive UI design with Tailwind CSS
Contributing

Pull requests are welcome. If you have suggestions or improvements, feel free to contribute.

License

This project is open source and available under the MIT License.
