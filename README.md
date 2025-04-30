# Custom CAPTCHA Implementation

A modern, user-friendly CAPTCHA implementation built with vanilla JavaScript, HTML, and CSS. This project demonstrates the creation of a secure and interactive CAPTCHA system that helps protect web forms from automated submissions while maintaining a smooth user experience.

## 🌟 Features

- **Dynamic CAPTCHA Generation**: Generates random 6-character CAPTCHAs using a mix of:

  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)

- **User-Friendly Interface**:

  - Clean and modern design
  - Responsive layout that works on all devices
  - Clear visual feedback for user interactions
  - Instant validation of user input

- **Interactive Elements**:
  - Reload button to generate new CAPTCHA
  - Input field for user verification
  - Status messages with color-coded feedback
  - Automatic reset after successful verification

## 🛠️ Technical Implementation

- **Pure JavaScript**: Built using vanilla JavaScript without any external dependencies
- **Modern CSS**: Utilizes modern CSS features for styling and animations
- **Responsive Design**: Adapts seamlessly to different screen sizes
- **Font Awesome Integration**: Uses Font Awesome icons for enhanced visual elements

## 🚀 How It Works

1. When the page loads, a random 6-character CAPTCHA is generated
2. Users can enter their CAPTCHA attempt in the input field
3. Upon submission:
   - If correct: Shows success message and generates new CAPTCHA after 2 seconds
   - If incorrect: Displays error message and allows retry
4. Users can click the reload button at any time to get a new CAPTCHA

## 💻 Usage

Simply open the `index.html` file in a web browser to run the application. No server or build process required!

## 🔒 Security Features

- Random character generation for unpredictability
- Case-sensitive validation
- Automatic CAPTCHA refresh after successful attempts
- Input length restriction to prevent overflow attacks

## 🎨 Customization

The project is easily customizable through:

- `style.css` for visual modifications
- `script.js` for behavior adjustments
- Character set can be modified in the `allCharacters` array

## 📱 Browser Compatibility

Works on all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements you'd like to add!

## 📄 License

This project is open source and available for personal and commercial use.
