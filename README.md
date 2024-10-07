Android App - PLANETS APP

App Overview

The Planets View App is an Android application that displays a list of planets in our solar system, along with their names, photos, and number of moons. The app uses a ListView to efficiently display the list of planets.

Technical Requirements

Backend: The app uses Java to create a data model for the planets, which includes the name, photo URL, and number of moons for each planet.

Frontend: The user interface is designed using XML, which includes a ListView to display the list of planets. Each item in the ListView is represented by a custom layout that includes a TextView for the name, an ImageView for the photo, and a TextView for the number of moons.

Data Storage: The app uses a local database (e.g., SQLite) to store the list of planets, which can be pre-populated or fetched from a remote API.

Key Features

Efficient List Display: The ListView is used to efficiently display the list of planets, allowing for smooth scrolling and minimal memory usage.

Customizable Layout: The custom layout for each item in the ListView can be easily modified to include additional information, such as planet size or distance from the sun.

Image Loading: The app uses a library such as Glide or Picasso to efficiently load and display the planet photos.

Planet Data Model

Name: The name of the planet 

Photo URL: The URL of the planet photo 

Number of Moons: The number of moons orbiting the planet

ListView Adapter

getView(): The method that returns the view for each item in the ListView, which includes the planet name, photo, and number of moons.
getCount(): The method that returns the number of items in the ListView.
getItem(): The method that returns the planet data model for each item in the ListView.


![Screenshot 2024-10-07 230338](https://github.com/user-attachments/assets/2a98b4fc-ff91-4ecc-9ad7-939cc51e9b16)


![Screenshot 2024-10-07 230307](https://github.com/user-attachments/assets/3f2962a3-dbf6-4c04-a79c-9a5c929cae84)


![Screenshot 2024-10-07 230351](https://github.com/user-attachments/assets/60e30b4f-0b7c-49b2-a722-740f900c54f0)
