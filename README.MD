# Dessert Clicker App

A simple interactive Android application built with Jetpack Compose that demonstrates the use of state management, UI interaction, and performance optimization techniques.



## Overview

Dessert Clicker is a game-like app where users tap on a dessert to "sell" it. Each click increments a counter, and after selling a certain number of desserts, the displayed dessert changes. The app keeps track of the total number of desserts sold and the total revenue generated.

## Features

- Interactive UI with clickable dessert images
- Dynamic dessert progression based on sales count
- Revenue tracking
- Session persistence through configuration changes
- Share functionality to share your current score

## Implementation Details

### Key Components

- **Dessert Data**: Each dessert has an associated image, price, and a threshold for when it appears
- **State Management**: Uses Jetpack Compose state to track:
  - Current dessert being displayed
  - Number of desserts sold
  - Total revenue

### Technologies Used

- Kotlin
- Jetpack Compose for UI
- Android Activity Lifecycle
- Intent for sharing functionality

### Architecture

The app follows a simple architecture:

- `MainActivity.kt`: Entry point containing the composable UI elements
- `Dessert.kt`: Data class representing dessert objects
- `DessertClickerScreen.kt`: Main composable function that sets up the UI

## Lifecycle Demonstration

This app demonstrates the Android activity lifecycle with logging at each lifecycle stage:
- onCreate
- onStart
- onResume
- onPause
- onStop
- onDestroy
- onRestart

## How to Run

1. Clone the repository
2. Open the project in Android Studio (Arctic Fox or newer recommended)
3. Build and run on an emulator or physical device

## Learning Objectives

This app demonstrates:
- State management in Jetpack Compose
- Handling configuration changes
- Working with Android activity lifecycle
- Creating interactive UI elements
- Implementing sharing functionality

## Requirements

- Android SDK 21+
- Kotlin 1.5+
- Android Studio Arctic Fox or newer

## License

[MIT License](LICENSE)