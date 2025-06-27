## 🚀 30-Day Coding Challenge: Day 18

This project is the eighteenth entry in my 30-day coding challenge. Today's goal was to build a real-time data-driven application using React. This Crypto Tracker fetches live data from a public API and displays it in a clean, professional interface, demonstrating the standard React pattern for handling external data.

### 📖 Project Overview

This is a sleek, dark-themed cryptocurrency price tracker that displays the top 20 cryptocurrencies by market capitalization. The application fetches live data from the CoinGecko API when it first loads and presents the information in a clear, easy-to-read table. It includes key metrics like price, 24-hour change, and market cap, with a "Refresh" button to fetch the latest data on demand.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jun-26-2025 20-12-58](https://github.com/user-attachments/assets/315af14e-71f0-4b74-bef6-c79642dee5fa)


### 🌟 Key Features

* **Live Crypto Data:** Fetches real-time market data for the top 20 cryptocurrencies from the CoinGecko API.
* **Data Fetching with `useEffect`:** Utilizes the `useEffect` hook with an empty dependency array to fetch data once when the component first mounts.
* **Loading and Error States:** Provides a clear loading indicator while data is being fetched and displays a user-friendly error message if the API call fails.
* **Dynamic Table Rendering:** The list of cryptocurrencies is dynamically rendered by mapping over the fetched data array.
* **Conditional Styling:** The 24-hour price change is colored green for positive changes and red for negative changes, providing quick visual insight.
* **Manual Refresh:** Includes a "Refresh" button that allows the user to re-fetch the data at any time.
* **Professional Dark Theme:** A modern UI styled with Tailwind CSS, designed to be easy on the eyes and familiar to a tech-savvy audience.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and layout.
* **CoinGecko API:** The source for all cryptocurrency data.
* **Font Awesome:** For icons.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-crypto-tracker.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd crypto-tracker
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

No API key is required for this version of the project.

### 🎯 Learning Objectives

This project was a crucial exercise for understanding how to work with external data in React:

* **Fetching Data in `useEffect`:** Mastering the standard React pattern for making API calls when a component loads.
* **Managing Loading & Error States:** Learning to handle the different states of an API request to provide a better user experience.
* **Working with API Data:** Mapping over an array of objects fetched from an external source and rendering a component for each item.
* **Conditional Rendering:** Using ternary operators and conditional logic to show/hide UI elements based on state (`loading`, `error`).
* **Asynchronous JavaScript in React:** Writing `async/await` functions within a React component to handle asynchronous operations.
