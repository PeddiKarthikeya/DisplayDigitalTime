#Local Time Display Project#
This is a simple web project that displays the user's local time dynamically using HTML, CSS, and JavaScript. The project demonstrates how to create a live clock that updates every second, with minimal design using CSS for layout and styling.
Features:
Live Time Update: The clock displays the user's local time, refreshing every second.
Clean Design: The time is centered on the page with a dark background and an orange-themed clock for better visibility.
Responsive Layout: The page adapts to various screen sizes using basic responsive techniques.

Project Structure:
->HTML is used for the structure of the page.
->CSS is integrated within the same HTML file for styling the layout.
->JavaScript is responsible for fetching the current time and updating the clock every second.

How it Works:
1. The HTML page contains a div for the clock, which is styled using inline CSS.
2. The JavaScript (DigitalClockScript.js) file retrieves the current time using the Date object and updates the content of the clock element.
3. The page continuously updates the displayed time using setInterval, ensuring it refreshes every second.

Usage:
1. Clone this repository.
2. Open the DigitalClockIndexFile.html file in your browser.
3. You will see the local time displayed at the center of the page, which will automatically update every second.

Future Enhancements:
->Option to switch between different time zones.
->Add a light/dark theme toggle for better user experience.
