# Wedding Countdown Page

This project is a simple and visually appealing countdown webpage that counts down the days, hours, minutes, and seconds until a special date. It is designed to celebrate and build anticipation for an important event, such as a wedding.

## Features

- **Dynamic Countdown**: The page dynamically updates every second to show the remaining time until the specified date.
- **Custom Styling**: The page includes a beautiful background image (`back3.jpg`) and styled countdown elements with hover effects.
- **Responsive Design**: The layout is designed to look great on various screen sizes.

## File Structure

- `weddong.html`: The main HTML file containing the structure, styles, and JavaScript logic for the countdown.
- `back3.jpg`: The background image used for the webpage.

## How to Use

1. Open the `weddong.html` file in any modern web browser.
2. The countdown will automatically start and display the time remaining until the specified date (`June 8, 2025, 18:30:00`).

## Customization

- **Change the Countdown Date**: To set a different countdown date, modify the following line in the `weddong.html` file:
  ```javascript
  const countDownDate = new Date("Jun 08, 2025 18:30:00").getTime();
  ```
  Replace the date and time with your desired target date.

- **Background Image**: Replace `back3.jpg` with another image of your choice. Ensure the new image is in the same directory as the `weddong.html` file.



## License

This project is free to use and modify for personal or educational purposes.
