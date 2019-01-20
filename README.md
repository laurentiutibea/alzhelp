# AlzHelp

<h1 align="center">
  <br>
  <img src="https://i.ibb.co/LZVRb3z/logo.png" alt="AlzHelp">
  <br>
  AlzHelp
  <br>
</h1>

<h4 align="center">AlzHelp - Localiztion & Pill Reminder</h4>

## Descriere

  AlzHelp este o aplicatie creata special pentru a ajuta persoanele cu Alzheimer amintindu-le printr-o notificare cand e momentul sa ia anumite pastile, iar in background este monitorizata locatia dispozitivului celui bolnav.

  Persoana care are grija de bolnav (denumita administrator in aplicatie) va trebui sa isi asocieze contul cu contul pacientului apoi va putea sa trimita notificari programate sau in timp real persoanei bolnave. Aceste notificari contin denumirea medicamentului ce va trebui sa si-l administreze. Administratorul va avea acces si la locatia pacientului.
  ex: Aceasta functie este utila in cazul in care pacientul s-a pierdut intr-un oras.
  
## Cum functioneaza?

  Aplicatia este creata in react-native si expo. Avantajul aplicatiei este acela ca este cross-platform.
  Aplicatia este dependenta de API-ul: https://github.com/laurentiutibea/alzhelp_api
  
  Rularea aplicatiei:
  * 1) Instalarea modulelor API-ului
  ```
  # >cd alzhelp_api
  $ npm install
  ```
  * 2) Pornirea API-ului
  ```
  # >cd alzhelp_api
  # Setarea unui cod privat pentru criptarea JWT-ului generat la autentificare.
  $ set alzhelp_jwtPrivateKey=jwtPrivateKey
  $ node index.js
  ```
  * 3) Instalarea modulelor aplicatiei
   ```
  # >cd alzhelp
  $ npm install
  ```
  * 4) Pornirea aplicatiei
  ```
  # >cd alzhelp
  $ expo start
  ```
  * 5) < Optional > Crearea aplicatiei standalone
  ```
  # >cd alzhelp
  # Pentru android:
  $ expo build:android
  # Pentru iOS:
  $ expo build:ios
  ```
  
