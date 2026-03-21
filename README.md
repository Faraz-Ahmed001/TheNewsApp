# TheNewsApp 📰

TheNewsApp is a modern Android application built to demonstrate Clean Architecture, MVVM, and the latest Jetpack components. It fetches real-time news data and provides a seamless user experience with offline caching.

## 🚀 Features
- **Real-time News:** Fetches the latest articles using the NewsAPI.
- **Offline Caching:** View previously loaded news even without an internet connection via Room Database.
- **Search Functionality:** Search for specific topics or news categories.
- **Save Articles:** Bookmark your favorite articles to read later.
- **Modern UI:** Built with Material Design 3 and a responsive Bottom Navigation layout.

## 🛠 Tech Stack & Architecture
This project follows **Clean Architecture** principles and the **MVVM** design pattern to ensure code maintainability and testability.

- **Kotlin & Coroutines:** For fast, non-blocking asynchronous operations.
- **Retrofit & OkHttp:** For handling REST API network requests with logging.
- **Room Database:** For local data persistence and offline support.
- **ViewModel & LiveData:** To manage UI-related data in a lifecycle-conscious way.
- **Navigation Component:** For fragment-based navigation and safe argument passing.
- **ViewBinding:** To safely interact with XML layouts without `findViewById`.
- **Glide:** For efficient image loading and caching.

## 📁 Project Structure
- `db/`: Room Database configuration and DAOs for local storage.
- `repository/`: The source of truth, managing data flow between API and DB.
- `ui/`: Activities and Fragments along with their respective ViewModels.
- `api/`: Retrofit interfaces and API service definitions.
- `util/`: Generic helper classes like the `Resource` wrapper for network states.

## ⚙️ Setup Instructions
1. Clone the repository: `git clone https://github.com/yourusername/TheNewsApp.git`
2. Get an API Key from [NewsAPI.org](https://newsapi.org/).
3. Create a `Constants` file and add your API Key: `const val API_KEY = "YOUR_KEY_HERE"`.
4. Build and run the app on Android Studio.

## 📸 Screenshots
<img width="569" height="1008" alt="image" src="https://github.com/user-attachments/assets/27247005-ce13-473d-beac-7f71715cfe1d" />
<img width="569" height="1008" alt="image" src="https://github.com/user-attachments/assets/71aec932-6106-426c-bfcf-b921cf1716c3" />
<img width="569" height="1008" alt="image" src="https://github.com/user-attachments/assets/b02fa244-9ab6-497f-bc1a-4da28bd60477" />
<img width="569" height="1008" alt="image" src="https://github.com/user-attachments/assets/b9c82ddb-d60d-4ebf-bca0-225108a5ecba" />




