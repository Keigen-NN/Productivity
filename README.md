# Productivity Tasks

A simple, clean, and minimalist task management Android application built with **Kotlin** and **Jetpack Compose**. It helps you organize your goals into short-term, medium-term, and long-term categories using an intuitive folder-style tab interface.

---

## Key Features

- 📁 **Folder-Style Tab Layout**: Manage tasks across three default categories (*Short-term*, *Medium-term*, *Long-term*).
- ✏️ **Customizable Folder Names**: Long-press any tab to rename it to fit your personal workflow.
- ⚙️ **Dynamic Notification Reminders**: A built-in background alarm system (`AlarmManager`) sends push notifications if tasks remain incomplete past their customizable deadlines.
- 🎨 **Theme Color Customization**: Sleek dark mode design with 5 selectable vibrant accent colors (Purple (default), Teal, Blue, Orange, Green) adjustable on-the-fly.
- 🌐 **Bilingual Support**: Switch the interface language between English (default) and Russian seamlessly inside the settings menu.
- 📊 **Progress Statistics**: Monitor your accomplishments with counters displaying completed tasks for the current and previous months.
- 🗑️ **Task History Database**: Restore accidentally completed tasks back to active status or delete them permanently from the history menu.
- 💾 **Persistent Storage**: All tasks, custom folder names, theme selections, and notification timers are saved securely on your device.

---

## Tech Stack

- **Language**: Kotlin
- **UI Toolkit**: Jetpack Compose (Material 3)
- **Architecture**: Single Activity (configured for reliable layout performance)
- **Persistence**: Android SharedPreferences (zero-configuration local saving)
- **Background Reminders**: `AlarmManager` & `BroadcastReceiver`
- **Permissions**: `POST_NOTIFICATIONS` (Android 13+)

---

## Getting Started

### Prerequisites

- Android Studio (Ladybug / Koala or newer recommended)
- JDK 17 or higher
- An Android device running Android 7.0 (API Level 24) or higher
- 
### Installation & Build

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Keigen-NN/Productivity.git
