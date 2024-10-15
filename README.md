# RuneScape Trade Assistant 📈🔧

## 📑 Table of Contents

- [🌟 Overview](#-overview)
- [🎯 Why I Built This Project](#-why-i-built-this-project)
- [🎥 Video Walkthrough](#-video-walkthrough)
- [🚀 Key Features](#-key-features)
- [🛠️ Technology Stack](#-technology-stack)
- [⚙️ How It Works](#-how-it-works)
- [🛠️ Future Enhancements](#-future-enhancements)
- [📫 Contact](#-contact)

## 🌟 Overview

The **RuneScape Trade Assistant** is a sophisticated tool designed to help RuneScape traders maximize their in-game profits with minimal manual effort. By leveraging real-time data analysis and proprietary simulation algorithms, the assistant identifies the best items to buy and sell, optimizes trading strategies, and provides real-time updates on active trades.

## 🎯 Why I Built This Project

I built the RuneScape Trade Assistant to create an interesting and challenging project that aligns with my passion for data science. This project serves as a platform to showcase my data science skills, including data collection, processing, algorithm development, and frontend integration. By tackling a real-world problem within the RuneScape economy, I aimed to demonstrate my ability to apply data science techniques to develop practical and impactful solutions.

## 🎥 Video Walkthrough

[![Watch the video](https://img.youtube.com/vi/ByknefPELV4/maxresdefault.jpg)](https://youtu.be/ByknefPELV4)

## 🚀 Key Features

- **Real-Time Data Analysis** 📊
  - Continuously collects and processes data from the latest RuneScape API.
  - Automatically scans all in-game items to identify the most profitable trading opportunities.

- **Proprietary Trading Simulations** 🤖
  - Rule-based algorithms simulate various trading strategies based on user-defined constraints.
  - Calculates expected profits, average margins, and trading efficiency for each item.

- **User-Friendly Frontend** 🎨
  - Interactive dashboard built with React, featuring:
    - **Live Trade Panel**: Manage active trades with real-time updates.
    - **Item Details**: Detailed information and metrics for each selected item.
    - **System Controls**: Customize trading parameters and simulation settings.

- **Customizable User Inputs** 🛠️
  - Set capital constraints, trade window limits, and minimum item price thresholds.
  - Filter and sort items based on expected profit, margin, and value per gold spent.

- **Real-Time Trade Monitoring** 🔄
  - Continuously monitors market changes and updates trade statuses every five seconds.
  - Notifies users of outbid offers and provides recommendations for adjusting trade prices.

## 🛠️ Technology Stack

- **Backend**: Python, FastAPI
- **Frontend**: React
- **Data Collection**: aiohttp for API requests
- **State Management**: Session and state management for handling live updates

## ⚙️ How It Works

1. **Data Collection** 📡
   - Interacts with the RuneScape API, fetching current buy and sell prices along with timestamps.
   - Constructs trade logs by comparing new data with previous entries to track price changes.

2. **Simulation Engine** 🔍
   - Runs rule-based simulations considering user-defined constraints (e.g., capital, trade windows).
   - Analyzes historical data to simulate buying and selling actions, calculating potential profits and margins.

3. **User Interaction** 🖥️
   - Users input their available capital and set preferences for trade constraints.
   - The frontend displays the top recommended items based on the simulation results.
   - Users can add items to the Live Trade Panel, where the system monitors and updates trade statuses in real-time.

## 🛠️ Future Enhancements

- **Online Hosting** ☁️
  - Deploy the application on a cloud platform to make it available 24/7.
  - Move the database online to enable continuous data collection, allowing for storage of multiple days and weeks of data instead of just the last hour.

- **Enhanced Security** 🔒
  - Implement authentication and authorization to secure user data and prevent misuse.
  - Introduce measures to protect against bots and malicious activities.

- **Advanced Simulations** 🧠
  - Integrate machine learning models to analyze long-term and interday price trends.
  - Develop additional trading strategies based on extensive data analysis.

- **User Access and Monetization** 💰
  - Open the platform to users, potentially introducing a paywall to monetize the service.
  - Provide users with access to the trading system, enabling them to optimize their own trading strategies.

- **Automated Testing** 🧪
  - Develop automated testing scripts to ensure the reliability and stability of the application.
  - Implement continuous integration and deployment (CI/CD) pipelines for streamlined updates.

- **Code Optimizations** ⚡
  - Refactor backend processes for improved performance and maintainability.
  - Enhance frontend responsiveness and speed to handle larger datasets efficiently.

## 📫 Contact

For inquiries or feedback, please reach out to [ben.infantino97@gmail.com]
