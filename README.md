
# Email Login Form V2

A clean, responsive email login form built with plain HTML, CSS and JavaScript. This project demonstrates semantic markup, accessible form controls, responsive layout, and client-side validation/UX enhancements (show/hide password, inline validation messages).

## Preview
![Project Image](https://github.com/mihaiapostol14/Email-Login-Form-V2/blob/5e27d7c6f7f33203d0195da6ad36234d42acdf38/assets/preview.png)

## Table of contents
- [Email Login Form V2](#email-login-form-v2)
  - [Preview](#preview)
  - [Table of contents](#table-of-contents)
  - [About](#about)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
    - [HTML](#html)
    - [CSS](#css)
    - [JavaScript](#javascript)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [Contributing](#contributing)
  - [License](#license)
  - [Author](#author)

## About
Email Login Form V2 is a lightweight front-end project that focuses on providing a polished login experience using only minimal dependencies (no frameworks). It's suitable as a starting point for authentication UI in small projects or for learning form accessibility and validation patterns.

## Features
- Semantic HTML form markup
- Responsive layout for mobile and desktop
- Client-side email and password validation
- Toggleable password visibility (show/hide)
- Inline validation messages and accessible labels
- Simple, customizable CSS variables for theming

## Technologies Used

### HTML
- Uses semantic elements and accessible form controls (`<form>`, `<label>`, `<input type="email">`, `<input type="password">`, `<button>`).
- Proper use of `aria-` attributes where needed and sensible tab order for keyboard navigation.
- Clean structure to separate content from presentation and behavior.

### CSS
- Modern CSS for layout and styling (flexbox or grid for centering/responsiveness).
- CSS variables for colors and spacing to make theming and customization straightforward.
- Responsive breakpoints to ensure the form looks good on phones, tablets and desktops.
- Focus styles for keyboard accessibility and visual clarity.

### JavaScript
- Client-side form validation (email format, password length/requirements).
- Show/hide password toggle with accessible labels and state updates.
- Prevent default form submission during development; example snippet to hook into an authentication API or mock.
- Small, dependency-free vanilla JS for wide compatibility and easy understanding.

## Installation

Run the following commands to clone the repository and move into the project directory:
```bash
git clone https://github.com/mihaiapostol14/Email-Login-Form-V2.git
cd Email-Login-Form-V2
```

After cloning, you can open the project in your editor and open `index.html` in your browser. For a better local experience, serve the folder with a simple HTTP server (e.g., VS Code Live Server or `python -m http.server`).

## Usage

- Open `index.html` in your browser (or serve the folder).
- Enter an email and password to see inline validation.
- Use the "show/hide" toggle to reveal the password.
- Replace the form submission handler (JS) with your authentication API call when integrating into a real app.

Example (development) flow:
1. Clone the repo (see Installation).
2. Open `index.html` or run a local server.
3. Inspect/modify files in `css/` and `js/` as needed.

## Project Structure
A typical structure for this project:
- index.html — main login form page
- css/
  - styles.css — layout and visual styles
- js/
  - main.js — validation and UI interactions
- assets/
  - images, icons, etc.

(Adjust paths to match the repository layout if different.)

## Contributing
Contributions are welcome. Suggested workflow:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit changes and open a pull request describing your changes.

Please follow accessible markup and keep JavaScript dependency-free unless a strong use-case exists.

## License
Include a license file in the repo (e.g., MIT) or specify the intended license here.

## Author
[Mihai Apostol](https://github.com/mihaiapostol14)