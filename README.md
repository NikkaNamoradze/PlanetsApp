# Trainers Attendee

**Trainers Attendee** is a mobile application built with React Native to manage attendees for various training sessions. It allows trainers to view, add, and manage participants efficiently.

## Table of Contents
1. [Getting Started](#getting-started)
2. [Prerequisites](#prerequisites)
3. [Environment Setup](#environment-setup)
4. [Dependencies](#key-dependencies)

## Getting Started

Follow these instructions to set up the project on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following tools installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [Yarn](https://yarnpkg.com/) (or npm as an alternative)
- [React Native CLI](https://reactnative.dev/docs/environment-setup)
- Xcode (for iOS development)
- Android Studio (for Android development)

### Environment Setup

1. Clone the project repository:
   ```bash
   git clone https://github.com/MaxinAI/trainers-mobile-attendees.git
   cd trainers-mobile-attendees

2. Install project dependencies:
   ```bash
   yarn install

3. For iOS, navigate to the ios folder and install CocoaPods dependencies:
   ```bash
   cd ios
   pod install
   cd ..

3. Start the development server:
   ```bash
   yarn start

6. To run the app on your chosen platform:
   ```bash
   yarn ios or yarn android

## Key Dependencies

### 1. Navigation

- **`@react-navigation/native`**: ^6.1.9
- **`@react-navigation/bottom-tabs`**: ^6.5.11
- **`@react-navigation/native-stack`**: ^6.9.17
- **`@react-navigation/stack`**: ^6.3.20

### 2. State Management

- **`@reduxjs/toolkit`**: ^1.9.7
- **`react-redux`**: ^8.1.3
- **`redux-persist`**: ^6.0.0

### 3. React Query

- **`@tanstack/react-query`**: ^5.17.19

### 4. Firebase

- **`@react-native-firebase/app`**: ^20.3.0
- **`@react-native-firebase/messaging`**: ^20.3.0

### 5. React Native Libraries

- **`react-native`**: 0.72.6
- **`react`**: 18.2.0
- **`react-native-webview`**: ^13.8.4
- **`react-native-gesture-handler`**: ^2.13.4
- **`react-native-screens`**: ^3.27.0
- **`react-native-safe-area-context`**: ^4.7.4

### 6. Animations

- **`react-native-reanimated`**: 3.5.4

### 7. Utilities

- **`axios`**: ^1.6.2
- **`react-native-config`**: ^1.5.1
- **`react-native-fs`**: ^2.20.0

### 8. UI Libraries

- **`victory-native`**: legacy

### 9. Image and Media Handling

- **`react-native-fast-image`**: ^8.6.3
- **`react-native-image-picker`**: ^7.0.2
- **`react-native-image-to-pdf`**: ^1.2.0
- **`react-native-view-shot`**: ^3.8.0


