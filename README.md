# Driver License Verification with Selfie

A Bootstrap-based static web page that allows users to take a selfie while holding their driver's license for verification purposes. The submitted photo is saved locally and sent via email. The interface is styled with Bank of America's color palette and theme.

## Features

- Responsive design using Bootstrap
- Webcam integration for selfie capture
- Driver's license upload option
- Email functionality to send verification data
- Local storage of verification data (JSON and images)
- Bank of America themed interface

## Setup

1. Clone this repository
2. Open `index.html` in your web browser
3. Allow camera permissions when prompted

## Technologies Used

- HTML5
- CSS3 (Bootstrap 5)
- JavaScript
- [EmailJS](https://www.emailjs.com/) for email functionality

## Usage

1. Open the verification page
2. Fill in your personal information
3. Upload your driver's license (optional)
4. Take a selfie while holding your driver's license
5. Accept the terms and conditions
6. Submit the form to complete verification

Verification data is saved in the `result` folder as:
- JSON file with personal information
- Selfie image file
- License image file (if uploaded)
