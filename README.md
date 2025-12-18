Flux 📰

A Native Android News Application

Overview

Flux is a native Android news application developed using Kotlin.
The app allows users to browse current news articles, read detailed content, save favorite news, and interact with articles through sharing and link copying features. Flux focuses on simplicity, usability, and clear user interaction feedback.

Features

Breaking News Feed – Browse the latest news articles
Search News – Search articles by keyword
Article Detail View – Read full article content
Save Articles – Save news locally using Room Database
Dark Mode – Improved readability in low-light conditions
Share Articles – Share news via Android share sheet
Copy Link – Copy article URL to clipboard
Read Indicator – Visually marks articles that have been opened
Share Counter – Displays total number of share actions

Screens

Breaking News

Saved News

Search News

Article Detail Screen

Technologies Used

Language: Kotlin

IDE: Android Studio

Networking: Retrofit

UI Components: RecyclerView, Material Components

Image Loading: Glide

Local Database: Room

Local Storage: SharedPreferences

Architecture

Flux follows a layered architecture:

UI Layer: Activities / Fragments + RecyclerView Adapter

Repository Layer: Handles API and database operations

Networking Layer: Retrofit API interface

Database Layer: Room Database for saved articles

Preferences Layer: SharedPreferences for read tracking and share counter

Installation & Run

Clone the repository:

git clone https://github.com/your-username/flux.git


Open the project in Android Studio

Sync Gradle files

Run the app on:

Android Emulator

or Real Android Device (USB Debugging enabled)

Demo Highlights

Open an article → return to list → article appears as READ

Share an article → Total shares counter increases

Copy link → “Link copied!” toast message

Save article → “Article saved successfully” confirmation

Switch to Dark Mode for better readability

Testing

The application was tested through manual functional testing using both emulator and real devices. Core features such as news loading, sharing, saving, read tracking, and dark mode were verified successfully.

Future Improvements

Offline reading support

Pull-to-refresh

Personalized news categories

Settings screen (text size, reset read/share data)

Author

Project Name: Flux

Type: Student Mobile Application Project

Platform: Android
