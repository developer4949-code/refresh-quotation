
# Refresh Quotation

A motivational quote-sharing Android application with daily refresh, offline support, and seamless media sharing—designed with Java, Android SDK, Firebase, Retrofit, and Glide.

---

## 🎯 Overview

Refresh Quotation helps users discover, save, and share inspiring quotes effortlessly:

- Pulls daily quotes from the ZenQuotes API and accompanying images from the Unsplash API.  
- Offers offline capabilities so users can browse previously fetched quotes even without internet connectivity.  
- Leverages Firebase Authentication for secure user login.  
- Allows media-sharing via Android’s MediaStore.  
- Built with clean architecture, Material Design, and modern image loading/caching for optimal UX and performance.

---

## 🛠️ Features

### Core Features  
- Daily quote refresh and display of a new motivational quote each day.  
- Integration with **ZenQuotes API** for quotes and **Unsplash API** for imagery via Retrofit and Glide.  
- Offline support: previously loaded quotes and images cached for offline browsing.  
- Firebase Authentication for user login and profile management.  
- Media sharing: users can share their favourite quotes as images to social platforms or contacts via Android’s native MediaStore APIs.  
- Material Design UI with smooth animations and intuitive navigation.

### Tech Stack  
- **Java** – Primary programming language.  
- **Android SDK** – Native Android UI & functionality.  
- **Firebase** – Authentication + optional real-time or other Firebase services.  
- **Retrofit** – For REST API consumption (ZenQuotes, Unsplash).  
- **Glide** – For image loading and caching.  
- **Material Design** – UI/UX consistency and modern look & feel.  
- Offline storage/cache – Ensures usage even when connectivity is limited.

---

## 🧭 Getting Started

### Prerequisites  
- Android Studio (latest stable)  
- Android SDK and emulator or physical device  
- A free account for **Unsplash API** and **ZenQuotes API** (or similar quote API)  
- Firebase console project for Authentication  

### Setup  
1. Clone this repository:  
   ```bash
   git clone https://github.com/developer4949-code/refresh-quotation.git
   cd refresh-quotation
