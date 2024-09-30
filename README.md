# FlickScore

FlickScore is a movie and TV show tracking application designed to enhance the viewing experience by allowing users to rate, review, and organize their watchlists. This app connects users with a vast library of films and TV shows and helps generate personalized recommendations. It also features a streamlined UI with biometric authentication, push notifications, and offline mode for seamless usability.

---

## Features

### Core Features
1. **User Authentication**: 
   - Single Sign-On (SSO) for quick registration and login.
   - Biometric authentication (fingerprint or facial recognition) for secure login.
   
2. **Movie and TV Show Database**:
   - Browse, search, and filter a wide range of films and TV series.
   - Filter by genre, year of release, rating, and more.

3. **Watchlist & Tracking**:
   - Create personalized watchlists and mark movies as "Watched" or "To Watch."
   - Rate and review movies using a predefined scale (1 to 5).

4. **Offline Mode**:
   - Access watchlists and track movies even without an internet connection. Data syncs automatically once reconnected.

5. **Recommendations**:
   - Personalized suggestions based on your watchlist and ratings.
   
6. **Push Notifications**:
   - Receive real-time alerts for new releases and other important updates.

7. **Multi-language Support**:
   - Switch between multiple languages, including English and Afrikaans.

---

## Installation

To run the FlickScore app locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/yourusername/FlickScore.git](https://github.com/VCDN-2024/opsc7312-part-2-Devonation.git)
   ```
   
2. **Open in Android Studio**:
   - Open Android Studio and select the `FlickScore` directory.

3. **Dependencies**:
   - Ensure you have Kotlin and the necessary libraries (e.g., Firebase, OkHttp) installed.
   
4. **API Setup**:
   - The app uses two APIs: IMDb for the movie database and a custom API for user authentication and data management.
   - IMDb API Key: Set your API key for the IMDb API in the appropriate configuration file.
   - Custom API: Ensure your Firebase project is connected.

5. **Run the App**:
   - Connect an Android device or emulator and run the application.

---

## Screenshots
*(Include relevant screenshots of the UI, login screen, watchlist, and more)*

![Uploading MainScreen.png…]()

---

## Usage

### Authentication
- Users can register and log in via SSO. Once logged in, biometric authentication can be enabled for future logins.

### Movie Tracking
- Users can add movies to their watchlist, rate and review them, and track what they’ve already watched.

### Offline Mode
- FlickScore’s offline functionality allows users to view and manage their watchlists without an internet connection. When reconnected, data will automatically sync with the server.

### Push Notifications
- Real-time notifications alert users to new releases and personalized recommendations based on their preferences.

---

## Tech Stack

- **Languages**: Kotlin
- **Libraries**:
  - Firebase Authentication and Firestore for user management and data storage.
  - IMDb API for fetching movie data.
  - OkHttp for API communication.
  - Picasso for image loading.
- **Database**: Firebase Firestore, RoomDB (for offline sync).
- **Build Tools**: Gradle, Android Studio.

---

## Automated Testing

This app includes unit testing via GitHub Actions to ensure functionality. It runs tests automatically on each commit. The CI pipeline checks:
- API connectivity.
- User authentication flow.
- Offline sync functionality.

To run the tests manually:
```bash
./gradlew test
```

---

## Demo Video

A demonstration video showcasing the key features of the app can be found [here](#). 

---

## Future Development

- **Gamification**: Add achievement badges for users based on their movie-watching activity.
- **Social Features**: Enable users to follow friends, compare ratings, and share recommendations.
- **Expanded Recommendation Engine**: Leverage advanced algorithms to offer better movie suggestions based on user preferences.
- **Add additional languanges**: Add more languages to help the app be accesable to more users.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Credits

- Developed by the RDG Inc -  ST10055559 – Renier Coetzer; ST10043202 – Devon Duerholz; ST10145628 – Gareth Atkinson
- APIs: IMDb API, Firebase.

---
