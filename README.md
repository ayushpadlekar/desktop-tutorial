# Pedalcity - Bicycle Rental Android App

<div align="left">
    <img src="Imgs/Pedalcity Logo.png" alt="Pedalcity_Logo" width="300">
</div>

Pedalcity is a bicycle sharing app designed to improve urban mobility. It allows people to access bicycle rental services directly from their phones. Users can locate bicycle points, choose bicycles from various options like mtb, cargo, geared, electric and Rent rides in real-time seamlessly.

<p><b> Download Pedalcity App - Pre-release APK 👉</b> https://github.com/ayushpadlekar/Pedalcity_Bicycle-Rental-App/releases/tag/v0.0.1-beta </p>

<p><b> Read the Project Report Documentation 👉</b> https://drive.google.com/file/d/13twZB3d7uodcgboyUEBO2sZjBUnu2GJ9/view?usp=sharing </p>

</br>

## Screenshots 📸

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="Imgs/Pedalcity Home.png" width="185"/>
  
  <img src="Imgs/Pedalcity QR code.png" width="185"/>
  
  <img src="Imgs/Pedalcity Wallet.png" width="185"/>
  
  <img src="Imgs/Pedalcity Profile.png" width="185"/>
</div>

</br>

## Features 💡

1. **User Interface**
    - Thematic Colors, Fonts & Backgrounds
    - Splash Screen Animations & Onboarding Screens
    - Bottom Navigation Bar to navigate between various fragments smoothly

2. **User Authentication and Details**
    - Google Sign-In with Firebase Authentication for secure and fast user login
    - Getting details of user like - Name, Phone, Birth date, Photo and storing it in Firebase Database

3. **Map & Nearby Bicycle Points**
    - Integrated Google Map with Satellite view and GPS locations
    - Added custom markers on map as Bicycle Points
    - Info Window showing information of each bicycle point (showed on clicking any marker)
    - 'Get Directions' Button redirecting to Gmaps app showing route from user location to Bicycle point

4. **Current Weather Info**
    - Displayed live weather information in a small view on the top right corner
    - Current Temperature, current condition and it's weather icon is showed

5. **Bicycle Options**
    - Sponsored Bicycles category with options from many different bicyle brands
    - Multiple bicycle types like MTB, Geared, Electric, Road or Cargo
    - Card Flip Views to show all the information of each bicycle

6. **Rent A Bicycle**
    - Bottom Sheet with 3 options - Scan QR Code, Enter Bicycle Number & Choose Bicycle Options
    - Bicycle Unlocks and Ride starts only when all the permissions are ON, especially bluetooth
    - The Rental details and bicycle Status is then updated in firebase database

7. **Ride Tracking & Updates**
    - Real-Time ride tracking with Chronometer timer for duration
    - World Time Api for syncing time irrespective of user's device time
    - Live Amount updates on calculation based on ride duration and bicycle rate per min
    - Ending ride updates rental details like start-time, end-time, duration, amount and wallet balance in Firebase

7. **Wallet**
    - Simulated Wallet features with Firebase
    - Add or withdraw money in wallet balance or pay Security deposit
    - Show all transactions with timestamp and details

</br>

## Demo 📲⬇️
</br>

## Utilized Technologies ⚛
 - **Programming:** XML, Java & Kotlin

 - **Frameworks/Libraries:**
   - **OK-HTTP**: For making **REST API** calls.
   - **Picasso**: For efficient image loading and caching.
   - **SharedPreferences**: For storing and retrieving user's cities list.

 - **Development Tools:** Figma, Lottie Animations, Android Studio.

 - **APIs:**
   - [Google Maps API](https://developers.google.com/maps/documentation/android-sdk) : For Location, Maps, Markers, Info window & Satellite views.
   - [Open Weather API](https://openweathermap.org/api) : For current weather updates in a particular area (in this, Mumbai).
