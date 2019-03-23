# AlzHelp

<h1 align="center">
  <br>
  <img src="https://i.ibb.co/LZVRb3z/logo.png" alt="AlzHelp">
  <br>
  AlzHelp
  <br>
</h1>

<h4 align="center">AlzHelp - Localization & Pill Reminder</h4>
<br>
<div align="center">
  <img src="https://i.ibb.co/M8dDS3q/50236730-2249243415335729-4926195100440068096-n.jpg" alt="AlzHelp" width=200>
  <img src="https://i.ibb.co/CB8kJ71/50456939-218728859073494-5509460794632306688-n.jpg" alt="AlzHelp" width=200>
</div>

## Description

  AlzHelp is an application specifically designed to help people with Alzheimer's. remind them when it's time to take some pills. An extra utility is background tracking of the patient's device.

  The patient caregiver (called administrator in the application) will need to associate their account with the patient's account and then be able to send scheduled or real-time notifications to the patient. These notifications contain the name of the medicine you will need to administer. The administrator also has access to the patient's location.
   eg: This function is useful if the patient is lost in a city.
  
## How it works?

  The app is created in react-native and expo. The app is cross-platform.
  API for the app: https://github.com/laurentiutibea/alzhelp_api
  
  How to run the app:
  * Install API's node modules
  ```
  # >cd alzhelp_api
  $ npm install
  ```
  * Run the API
  ```
  # >cd alzhelp_api
  # Set a private key for the authentication JWT.
  $ set alzhelp_jwtPrivateKey=jwtPrivateKey
  $ node index.js
  ```
  * Install app's node modules
   ```
  # >cd alzhelp
  $ npm install
  ```
  * Run the app
  ```
  # >cd alzhelp
  $ expo start
  ```
  * < Extra > Create standalone app
  ```
  # >cd alzhelp
  # For android:
  $ expo build:android
  # For iOS:
  $ expo build:ios
  ```
## Known bugs

  - Scheduled notifications are not yet implemented in expo. They work only with the app opened.
  - Background localization is not yet implemented in expo. Localization work only with the app opened.

## Contact

> Email: [laurentiutibea@gmail.com] &middot;
> GitHub [@laurentiutibea](https://github.com/laurentiutibea)
