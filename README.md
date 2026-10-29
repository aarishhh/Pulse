# Pulse — Social Community App

Pulse is a modern social community mobile application built with **React Native, Expo, TypeScript, and Zustand**. It aims to provide a smooth social experience with interactive feeds, user profiles, and community engagement features.

## ✨ Features

- **Interactive Feed** — Browse posts from a sample social feed.
- **User Profiles** — View and manage profile information.
- **Create Posts** — Compose posts and select images.
- **Likes & Comments** — Interact with posts.
- **Follow System** — Follow and unfollow users.
- **Explore** — Discover posts and users.
- **State Management** — Manage application state using Zustand.
- **Local Persistence** — Preserve supported user interactions across app restarts.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React Native | Cross-platform mobile development |
| Expo | Development and app tooling |
| TypeScript | Type-safe application development |
| JavaScript | Application logic |
| Zustand | State management |
| Expo Router | Navigation and routing |
| AsyncStorage / SQLite | Local data persistence |

*The listed technologies should reflect the packages actually used in the repository.*

## 📱 Screens

- Home Feed
- Explore
- Create Post
- Notifications
- User Profile
- Login and Registration

## 🚀 Getting Started

### Prerequisites

- Node.js (LTS version)
- npm
- Expo Go on a compatible mobile device, or an Android emulator

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/aarishhh/Pulse.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Pulse
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npx expo start
   ```

5. Scan the QR code with Expo Go or launch the application in an emulator.

## 🏗️ Project Structure

```text
pulse/
├── app/                  # Screens and navigation
├── src/
│   ├── components/       # Reusable UI components
│   ├── features/         # Feature-specific modules
│   ├── hooks/            # Custom React hooks
│   ├── services/         # Data and business logic
│   ├── types/            # TypeScript definitions
│   └── utils/            # Helper functions
├── assets/               # Images, icons, and fonts
├── package.json
└── README.md
```

*The structure may evolve as development progresses.*

## 🔮 Future Improvements

- Backend integration with Supabase.
- Real user authentication and profiles.
- Cloud-based post and image storage.
- Realtime notifications and social interactions.
- Improved feed personalization.
- Reporting, blocking, and moderation tools.

## 🎯 Project Objective

The goal of Pulse is to explore mobile application development, reusable UI architecture, state management, navigation, and local data persistence while building a foundation for a scalable social community platform.

## ⚠️ Current Status

**Status: In Development**

Pulse is intended to begin as a frontend-focused prototype. Features such as real authentication, cross-device synchronization, and server-backed social interactions will require backend integration.

## 👨‍💻 Author

**Aarish**

GitHub: [@aarishhh](https://github.com/aarishhh)

---

If you find this project useful, consider giving the repository a ⭐.
