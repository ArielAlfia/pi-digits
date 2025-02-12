# Pi-Digits

Pi-Digits is a React application that fetches and displays the first \( n \) digits of pi using an API. This project includes several features and tasks for candidates to complete, including bug fixes, error handling, and new feature implementations.

## Features

- Fetch and display the first \( n \) digits of pi.
- Input validation to ensure only digits are accepted.
- Light/Dark theme toggle.
- Search functionality to find occurrences of a sequence within the first 1000 digits of pi.

## Bugs to Fix

1. **Login Issue**: After pressing submit, the screen turns white instead of navigating into the app.
2. **Input Validation**: Ensure the input field only accepts digits.
3. **Incomplete Translations**: Complete all missing labels for Hebrew and Romanian.
4. **Digit Rendering Bug**: The spinner remains on the screen, and if the user chooses to render 3 digits, it only renders 1.

## Error Handling

1. **Numbers > 1000**: Handle cases where the input number is greater than 1000.
2. **Negative Numbers**: Handle cases where the input number is negative.

## New Features to Implement

1. **Logout**: Implement a logout functionality.
2. **Long Press on +,- Buttons**: Add functionality to handle long press actions on the increment and decrement buttons.
3. **Highlight Occurrence of Digit X**: Highlight all occurrences of a specific digit (0-9).
4. **Copy Button**: Add a button to copy the displayed digits to the clipboard.
5. **Light/Dark Theme**: Implement a toggle for switching between light and dark themes.
6. **Search Functionality**: Add a search feature to find the occurrence of a sequence like "12345" within the first 1000 digits of pi.

## Getting Started

install yarn

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pi-digits.git
   cd pi-digits
   ```
   yarn install
   yarn start
