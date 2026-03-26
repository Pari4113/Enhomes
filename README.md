# 🏠 Enhomes — Frontend (Android)

A **Java-based Android application** for property browsing and home management. This is the frontend client for the Enhomes platform — the backend API lives in a separate repository.

> 🔗 **Backend Repo:** [Enhomes-Backend](https://github.com/Pari4113/Enhomes-Backend)

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Platform | Android |
| Language | Java |
| Build Tool | Gradle |
| Backend API | [Enhomes-Backend](https://github.com/Pari4113/Enhomes-Backend) (Node.js / Express) |

## Features

- Property listing and browsing interface
- Integration with RESTful backend API for real-time property data
- Clean, modular Android architecture
- *(Add more: search filters, favorites, map view, user auth, etc.)*

## Getting Started

### Prerequisites
- Android Studio (latest stable)
- JDK 11+
- Android SDK
- [Enhomes-Backend](https://github.com/Pari4113/Enhomes-Backend) running locally or deployed

### Run the App
1. Clone the repository
2. Open in Android Studio
3. Sync Gradle dependencies
4. Update the API base URL to point to your backend instance
5. Run on emulator or physical device

```bash
git clone https://github.com/Pari4113/Enhomes.git
```

## Project Structure
```
Enhomes/
├── app/               # Main Android application module
├── gradle/            # Gradle wrapper
├── build.gradle       # Project-level build config
└── settings.gradle    # Project settings
```

## Related Repositories

| Repo | Description |
|------|------------|
| [Enhomes-Backend](https://github.com/Pari4113/Enhomes-Backend) | Node.js + Express REST API powering the Enhomes platform |

## License

This project is for educational and portfolio purposes.
