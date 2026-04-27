#  Flutter News Application (API Based)

A Flutter application that fetches and displays real-time news using a free online API. The app shows news articles in a clean list format with title, image, date, and description.

---

##  API Used

* https://newsapi.org/

---

##  Features

*  Fetch latest news from API
*  Display news images
*  Show news title
*  Display publish date
*  Show news description/details
*  ListView-based structured layout
*  Real-time data loading

---

##  Technologies Used

* Flutter
* Dart
* HTTP package (API calls)
* NewsAPI

---

## Project Structure

```id="news10x"
lib/
 └── main.dart
models/
 └── news_model.dart   (optional)
services/
 └── api_service.dart  (optional)
```

---

##  Getting Started

Follow these steps to run the project locally:

### Prerequisites

* Install Flutter SDK
* Install Android Studio / VS Code
* Get API key from https://newsapi.org/

---

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-news-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flutter-news-app
   ```

3. Get dependencies:

   ```bash
   flutter pub get
   ```

4. Add your API key in the project:

   ```dart
   https://newsapi.org/v2/top-headlines?country=us&apiKey=YOUR_API_KEY
   ```

5. Run the app:

   ```bash
   flutter run
   ```

---

##  Dependency Setup

Add this in `pubspec.yaml`:

```yaml id="httpnews1"
dependencies:
  http: ^0.13.6
```

---

##  How It Works

* Uses **HTTP package** to fetch data from NewsAPI
* JSON response is parsed into Dart objects
* `ListView.builder` displays news articles
* Each news item includes:

  *  Title
  *  Image (`Image.network`)
  *  Published date
  *  Description
* `FutureBuilder` handles asynchronous API loading

---

##  Notes

* You must use a valid API key from NewsAPI
* Internet connection is required to load news

---

##  Future Improvements

* Add category-based news (sports, tech, business)
* Add search functionality
* Implement bookmarking feature
* Add dark mode support
* Improve UI with animations

---

##  Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---


##  Author

Riya Patani

---
