# 📱 Android News Application

### Brief One Line Summary  
A real-time Android news application that fetches and displays the latest news using REST APIs with a clean, fast, and user-friendly interface.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Data Source](#data-source)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Application Architecture](#application-architecture)
- [Key Features](#key-features)
- [Screens / Output](#screens--output)
- [How to Run This Project](#how-to-run-this-project)
- [Results & Conclusion](#results--conclusion)
- [Future Work](#future-work)
- [Team Members](#Team--Members)

---

## Overview
The Android News Application is designed to provide users with up-to-date news from multiple categories such as technology, business, sports, and entertainment.  
The application emphasizes real-time data fetching, performance efficiency, and a clean UI.

---

## Problem Statement
Many existing news applications suffer from cluttered interfaces, excessive ads, and slow performance.  
This project aims to build a lightweight and user-friendly Android news application that provides quick access to relevant news content.

---

## Data Source
- Real-time data fetched from a **REST-based News API**
- Data includes:
  - Latest headlines
  - Category-wise news
  - News images, descriptions, and sources

> No static dataset is used as this is a real-time application.

---

## Tools & Technologies
- Java  
- Android SDK  
- Android Studio  
- REST API  
- RecyclerView  
- XML (UI Design)  
- Windsurf (AI-powered IDE)  
- Gradle Build System  

---

## Project Structure

```text
android-news-app/
│
├── app/
│   ├── src/main/
│   │   ├── java/com/example/newsapp/
│   │   │   ├── activities/
│   │   │   │   ├── MainActivity.java
│   │   │   │   │── NewsDetailActivity.java
│   │   │   ├── adapters/
│   │   │   │   └── NewsAdapter.java
│   │   │   ├── models/
│   │   │   │   └── NewsModel.java
│   │   │   ├── api/
│   │   │   │   └── ApiClient.java
│   │   │   └── utils/
│   │   │       └── Constants.java
│   │   ├── res/
│   │   │   ├── layout/
│   │   │   ├── values/
│   │   │   └── drawable/
│   │   └── AndroidManifest.xml
│   └── build.gradle
│
├── screenshots/
├── README.md
└── build.gradle
```
## Application Architecture

- Follows **MVC (Model–View–Controller)** architecture
- **Model**: Represents news data objects
- **View**: XML layouts for UI components
- **Controller**: Activities manage UI logic and navigation
- **API Layer**: Handles network calls and data parsing
- **RecyclerView**: Manages efficient list rendering

---

## Key Features

- Real-time news updates  
- Category-wise news browsing  
- Clean and responsive user interface  
- Fast loading with smooth scrolling  
- Network error handling and fallback messages  

---

## Screens / Output

- Home screen displaying latest headlines  
- Category-wise news listing screen  
- Detailed news view with image and description  

📷 Screenshots are available in the `screenshots/` folder.

---

## How to Run This Project

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/android-news-app.git
2. Open the project in **Android Studio**

3. Sync Gradle files

4. Add your **News API key** inside `Constants.java`

5. Run the app on:
   - Android Emulator, or  
   - Physical Android device  

---

## Results & Conclusion

The Android News Application successfully delivers real-time news with a clean and smooth user experience.  
The project demonstrates strong Android fundamentals, REST API integration, and structured application design.

---

## Future Work

- Offline news caching  
- Dark mode support  
- Push notifications for breaking news  
- User authentication  
- Multi-language support  

---

## Team Members

- **Bikash Sah** – Android Development, REST API Integration, UI Design, GitHub & Version Control  
- **Sowbhagya Laxmi Das** – Testing, Debugging & Performance Optimization
- **Arijit Pan** – UI/UX Design & XML Layout Development  
- **Abdur Johir Alom** – API Research, Data Handling & JSON Parsing 
- **Supreeti Debnath** – Documentation, Project Report Writing & Presentation  
- **Tanuka Jana** – Requirement Analysis, Feature Planning & Deployment Support
---
