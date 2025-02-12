# Mapty

Mapty is an interactive web application that allows users to log their workouts on a map. The application uses the Geolocation API to detect the user's location and the Leaflet API for displaying the map and managing markers.

## Live Demo
You can try the live demo of the application here: [Mapty Live Demo](https://orasanuana.github.io/Mapty/)

## Features
- **Add workouts**: Users can enter details about running or cycling workouts.
- **Display on the map**: Workouts are marked on the map using Leaflet.
- **Data persistence**: Data is saved in `localStorage`, ensuring it is not lost upon page reload.
- **Filter and manage workouts**: Users can view and manage their saved workouts.

## Technologies Used
- **HTML, CSS, JavaScript**: Structure, styling, and application logic.
- **Leaflet.js**: For displaying the map and managing markers.
- **Geolocation API**: To detect the user's current location.
- **localStorage**: For storing and persisting user data.

## How to Use the Application
1. Access the application page and allow location access.
2. Add a workout by entering the required details (workout type, distance, duration, etc.).
3. The workout will appear on the map at the current location.
4. Data is automatically saved and can be accessed on the next visit.

## Installation
To run the application locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/OrasanuAna/Mapty.git
   ```
2. Open `index.html` in a browser.

## Mapty Flowchart
Mapty Flowchart
![Mapty Flowchart](https://github.com/OrasanuAna/Mapty/blob/master/Mapty-flowchart.png)

Mapty Architecture
![Mapty Architecture](https://github.com/OrasanuAna/Mapty/blob/master/Mapty-architecture-part-1.png)

Mapty Architecture Final
![Mapty Architecture Final](https://github.com/OrasanuAna/Mapty/blob/master/Mapty-architecture-final.png)


## Author
[Ana-Maria Orășanu](https://github.com/OrasanuAna)

## Credits
This project was developed as part of the **The Complete JavaScript Course: From Zero to Expert!** by **Jonas Schmedtmann**.

