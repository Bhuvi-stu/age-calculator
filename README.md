# Age Calculator

A simple and responsive web application that calculates a user's age in years, months, and days based on their date of birth.

## Features

- User-friendly date input.
- Accurate calculation of age in years, months, and days.
- Real-time results after entering the date.
- Input validation to prevent future dates.
- Fully responsive design for desktop and mobile.
- Uses JavaScript Date object for precise age calculation.

## How to Use

1. Open the website (index.html) in any modern browser
2. Enter your Date of Birth using the input field
3. Click the Calculate button
4. Your age will be displayed in years, months, and days

## How It Works

This website:
- The user inputs their date of birth through an HTML date input field
- When the button is clicked:
    - JavaScript calculates the difference between the current date and the entered date
    - It then converts the difference into years, months, and days using the Date object
    - The result is shown dynamically on the webpage

## Limitations

- Does not support time of birth (only date)
- Only works with valid date formats supported by the browser
- No storage of previously entered data
- Does not handle calendar anomalies (like leap seconds)

## Technologies Used

- HTML5
- CSS3
- JavaScript (Logic for age calculation)

## Future Improvements

- Save recent calculations using browser localStorage
- Add dark mode for better accessibility
- Add support for calculating age from a specific past/future date (not just today)
- Add unit tests to validate age calculations
- Add multilingual support for different regions
