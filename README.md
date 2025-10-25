# 🎮 Mobile Video Gaming App

A cross-platform mobile app built using **Flutter** and **Dart**, designed to help gamers stay informed about upcoming game releases, reviews, and purchase options — all in one user-friendly platform.

---

## 📱 Introduction

The purpose of this project is to design and implement a mobile application that serves the needs of gamers by providing essential information about upcoming game releases, user reviews, and purchase options. 

The app aims to eliminate the inconvenience of searching multiple websites or forums by offering a **centralized, all-in-one solution** where users can:
- Browse new and upcoming games
- Read and write reviews
- Compare prices from multiple retailers before purchasing

Ultimately, the goal is to **build a connected gaming community** where users can interact, share insights, and make better purchasing decisions.

---

## 🧩 App Design

The app combines three primary features:

### 1. Upcoming Game Information
Displays essential details such as release dates, developers, genres, and trailers.

### 2. Review System
Allows gamers to post and read reviews. This community-driven feedback helps users make informed choices.

### 3. Purchase Links
Provides direct purchase links to multiple retailers with **price comparisons** and delivery options.

---

## 🧱 App Structure

| File | Description |
|------|--------------|
| **main.dart** | Entry point of the app; sets up routes and navigation. |
| **game.dart** | Defines the data model for a game (title, description, release date, reviews). |
| **reviews.dart** | Defines the structure of user reviews (ratings, comments, timestamps). |
| **home_screen.dart** | Displays a list of upcoming games with dynamic rendering. |
| **game_details_screen.dart** | Provides detailed info and links to reviews/purchase options. |
| **review_screen.dart** | Displays user reviews and allows posting new ones. |
| **purchase_links_screen.dart** | Shows multiple retailer options for price comparison. |
| **login_screen.dart** | Handles user authentication using Firebase. |
| **register_screen.dart** | Registers new users and stores data via `database_helper.dart`. |
| **upcoming_game.dart** | Represents individual game cards in the list. |
| **messaging_screen.dart** | Enables real-time messaging between users. |
| **database_helper.dart** | Manages local storage using SQLite for offline caching. |
| **api_service.dart** | Handles HTTP requests to fetch game and review data from APIs. |

---

## 🧪 Implementation Process

### 🛠️ Development Environment
- **Framework:** Flutter  
- **Language:** Dart  
- **Database:** SQLite  
- **Backend Integration:** RESTful APIs  
- **IDE:** Visual Studio Code  

### ⚙️ Key Steps
1. Set up Flutter and project structure.  
2. Created data models (`game.dart`, `reviews.dart`).  
3. Developed UI screens and navigation flow.  
4. Integrated Firebase for authentication.  
5. Added SQLite local caching and REST API services.  
6. Conducted testing and collected user feedback.  

---

## 🧍‍♂️ User Flow Example

**Task:** Submitting a game review  
1. Login → `login_screen.dart`  
2. Navigate to Home → `home_screen.dart`  
3. Select a Game → `game_details_screen.dart`  
4. Access Reviews → `review_screen.dart`  
5. Write & Submit Review → `database_helper.dart` handles storage  

---

## 🎨 High-Fidelity Prototypes

### **Version A (Highly Attractive)**
- Vibrant colors, detailed icons, and smooth animations  
- Guided user flow with clarity and visual appeal  

### **Version B (Minimalistic)**
- Simpler design with faster navigation  
- Prioritizes efficiency over aesthetics  

🧩 **User Study Results:**
| Metric | Version A | Version B |
|---------|------------|-----------|
| Visual Appeal (1–5) | 4.8 | 3.2 |
| Avg. Task Completion Time (secs) | 85 | 60 |

➡️ Conclusion: **Version A** is visually superior, while **Version B** enables faster task completion.

---

## 👥 User Testing & Feedback

**Participants:** 5 (Aged 18–35, mixed experience levels)

| Participant | Gender | Time | Feedback |
|--------------|---------|------|-----------|
| User 1 | Male | 4 min | Intuitive design, improve price clarity |
| User 2 | Female | 5 min | Liked reviews, found loading slow |
| User 3 | Male | 7 min | Suggested showing reviews on purchase screen |
| User 4 | Female | 5 min | Loved UI and chat; suggested push notifications |
| User 5 | Male | 4 min | Found ratings useful; requested dark mode |

---

## 💬 Discussion & Future Work

### Planned Enhancements
- 🧭 **Improved Navigation:** Smoother screen transitions  
- 🎯 **Personalization:** Game recommendations based on user preferences  
- ⚡ **Performance:** Optimized API calls and caching for speed  

### Future Goals
- Add a robust recommendation engine  
- Enable real-time multiplayer review chats  
- Launch on both **iOS** and **Android** app stores  

---


