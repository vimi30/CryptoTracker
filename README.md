Crypto Tracker

Crypto Tracker is an Android application that provides real-time market trends for various cryptocurrencies. Users can explore a list of cryptocurrencies, view detailed statistics, and track their price history using interactive line charts.

Features

	•	Cryptocurrency List
Displays a list of popular cryptocurrencies along with their current prices and market trends.
	•	Detail Page
For each cryptocurrency, the detail page shows:
	•	Market Cap
	•	Current Price
	•	Percentage Change in the Last 24 Hours
	•	Price History
Interactive line chart visualizing the cryptocurrency’s price history over time.

Architecture

The app follows the MVI (Model-View-Intent) architecture pattern, ensuring unidirectional data flow for maintainability and scalability.

Tech Stack

	•	Programming Languages: Kotlin
	•	UI Framework: Android Jetpack + Material Design Theme
	•	Networking: Ktor (for API calls)
	•	Dependency Injection: Koin (for modular dependency injection)
	•	Navigation: Adaptive Navigation API (for seamless, responsive navigation)

API Integration

The app uses the CoinCap API to fetch real-time data on cryptocurrencies, including:

	•	Current Prices
	•	Market Cap
	•	Percentage Changes over 24 Hours
	•	Historical Price Data for generating charts

Learn more about the CoinCap API here.

Installation and Setup

1. Clone the repository:

        git clone https://github.com/yourusername/crypto-tracker.git
        cd crypto-tracker
2.	Open the project in Android Studio and let Gradle sync the dependencies.
3.	Run the app on an emulator or a physical device.

How to Use

	1.	Explore Cryptocurrencies: View a list of cryptocurrencies with their current prices and trends.
	2.	View Details: Click on a cryptocurrency to see its detailed stats, including market cap, price, and 24-hour change.
	3.	Track Price History: Use the interactive line chart on the detail page to view the currency’s price history over time.

Dependencies

	•	Ktor: For making network requests to the CoinCap API
	•	Koin: For dependency injection, promoting modularity and testability
	•	Adaptive Navigation API: Ensures smooth and adaptive navigation between screens
	•	Material Design Theme: Provides a modern, consistent UI

Screenshots

<img src="https://github.com/user-attachments/assets/02df2a0d-614e-4b50-91df-6d757737ffef" width="700" />
<img src="https://github.com/user-attachments/assets/d9380563-83cd-4318-9880-c9f03991e501" width="700" />
<img src="https://github.com/user-attachments/assets/2f6b9d5d-5218-4418-a120-ddd68cba9646" width="700" />
<img src="https://github.com/user-attachments/assets/3ca67d7c-ef65-4855-a246-e0b1229f8bde" width="700" />



https://github.com/user-attachments/assets/83d30510-b439-4138-8c17-55bfd1ddd795  

https://github.com/user-attachments/assets/143b05e6-13dd-4724-b4f6-ac19d31fb275




License

This project is licensed under the MIT License.


