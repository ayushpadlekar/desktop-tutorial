# Pedalcity - Bicycle Rental Android App

<div align="left">
    <img src="Imgs/Pedalcity Logo.png" alt="Pedalcity_Logo" width="300">
</div>

Pedalcity is a bicycle sharing app designed to improve urban mobility. It allows people to access bicycle rental services directly from their phones. Users can locate bicycle points, choose bicycles from various options like mtb, cargo, geared, electric and Rent rides in real-time seamlessly.

<p><b> Download Pedalcity App - Pre-release apk 👉</b> https://github.com/ayushpadlekar/Pedalcity_Bicycle-Rental-App/releases/tag/v0.0.1-beta </p>

## Screenshots

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="Imgs/Pedalcity Home.png" width="200"/>
  
  <img src="Imgs/Pedalcity QR code.png" width="200"/>
  
  <img src="Imgs/Pedalcity Wallet.png" width="200"/>
  
  <img src="Imgs/Pedalcity Profile.png" width="200"/>
</div>

## Features

• Designed UI/UX with Figma, including logos, icons and animations. Implemented splash screens, onboardings, and bottom navigation bar to navigate between various fragments smoothly.

• Implemented Google Sign-In with Firebase Authentication for secure and fast user login with their details.

• Integrated Google Maps to display bicycle points. Displayed live weather information using Open Weather API.

• Developed a rental flow with options to scan QR code, enter bicycle number or choose from multiple bicycles options.

• Managed bicycle availability and rental initiation. Enabled Real-Time ride tracking with Chronometer timer for duration, live amount calculation, and ride details. Users can end ride, see ride summary and give feedback.

• Managed Wallet features for balance, deposits, and transactions with Firebase. Enabled profile picture uploads and user details management, allowing users to edit and save their personal details.


## Utilized Technologies 🔧
 - **Programming:** XML, Java & Kotlin

 - **Frameworks/Libraries:**
   - **OK-HTTP**: For making **REST API** calls.
   - **Picasso**: For efficient image loading and caching.
   - **SharedPreferences**: For storing and retrieving user's cities list.

 - **Development Tools:** Figma, Lottie Animations, Android Studio.

 - **APIs:**
   - [Google Maps API](https://developers.google.com/maps/documentation/android-sdk) : For Location, Maps, Markers, Info window & Satellite views.
   - [Open Weather API](https://openweathermap.org/api) : For current weather updates in a particular area (in this, Mumbai).
