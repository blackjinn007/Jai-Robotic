# Jai-Robotic
- Splash screen with JAI logo - Map with tracked route - AI analysis output

# JAI - Smart Route Tracker

![JAI Logo](app/src/main/res/drawable/jai_logo.png)

**JAI** is an Android app that tracks your route with GPS, maps it in real-time, and delivers smart AI insights—distance, speed, and travel tips. Built on Kali Linux, it features a black-and-blue design with a Mars-inspired logo. Perfect for travelers and tech enthusiasts!

## Features
- **Real-Time GPS Tracking**: Updates every 10 seconds (customizable).
- **Google Maps Integration**: Shows your route with markers and a blue line.
- **Smart AI Analysis**: Calculates distance, speed, and offers tips with travel quotes.
- **Route Management**: Save, load, and share routes.
- **Custom Settings**: Adjust tracking interval.
- **Themed UI**: Black-and-blue with JAI logo.
- **Backend Sync**: (Optional) Sends data to a Flask server.

## Screenshots
- Splash screen with JAI logo
- Map with tracked route
- AI analysis output

## Requirements
- Kali Linux with Android Studio
- Android 5.0+ device
- Google Maps API Key
- (Optional) Flask server

## Setup Instructions
### 1. Install Tools
```bash
sudo apt update
sudo apt install openjdk-11-jdk git
wget https://redirector.gvt1.com/edgedl/android/studio/ide-zips/2023.1.1.28/android-studio-2023.1.1.28-linux.tar.gz
tar -xvzf android-studio-2023.1.1.28-linux.tar.gz
cd android-studio/bin
./studio.sh
