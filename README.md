## Login & Registration Form UI

-- A sleek and modern login/registration form interface with smooth animated transitions between panels. 
-- This project features a dual-panel design where users can seamlessly switch between login and sign-up forms.

#Demo: https://split-auth.netlify.app/

🌟 Features
-- Animated Panel Transitions: Smooth sliding animation between login and registration forms
-- Responsive Design: Adapts to different screen sizes
-- Form Validation: Visual feedback for input fields
-- Interactive Elements: Hover effects and focus states
-- Modern UI: Clean design with contrasting color scheme
-- Accessibility: Proper form labeling and keyboard navigation support

🎨 Design Elements
# Color Scheme:
-- Dark background with neon green accents (#4bff27)
-- Pink accent for buttons (#ff2770)
-- High contrast text for readability

# Typography:
-- Poppins font family
-- Clear hierarchy with different font weights

# Visual Effects:
-- Rotating background elements on panel switch
-- Blur and fade animations
-- Interactive input field labels
-- Button hover effects with subtle shadow

📁 Project Structure

    project/
    ├── index.html          # Main HTML structure
    ├── style.css           # All styling and animations
    ├── script.js           # Panel switching functionality
    └── README.md           # This file

🚀 Technologies Used
-- HTML5: Semantic structure
-- CSS3: Modern styling with custom properties (CSS variables)
-- JavaScript: Simple DOM manipulation for panel toggling
-- Boxicons: Icon library for form field icons
-- Google Fonts: Poppins font family

📱 Features in Detail
-- Login Form
-- Username field with user icon
-- Password field with lock icon
-- "Sign Up" link to switch to registration
-- Registration Form
-- Username field
-- Email field with envelope icon
-- Password field with lock icon
-- "Login" link to return to login form
-- Interactive Elements
-- Input fields with animated labels
-- Focus states change border color to neon green
-- Submit buttons with hover effects
-- Smooth transitions between panels

🎯 Usage
-- Clone or download the repository
-- Open index.html in your browser
-- Click "Sign Up" link to view registration form
-- Click "Login" link to return to login form

🔧 Customization
-- The design uses CSS custom properties for easy customization:

css
:root {
    --white: black;
    --black: white; 
    --lightBulue: #4bff27;
}
-- Modify these variables to change the color scheme quickly.

📝 Code Highlights
-- CSS Variables: For consistent theming
-- CSS Transitions: For smooth animations
-- Transform Properties: For sliding effects
-- Responsive Units: Flexible sizing
-- BEM-like Naming: For maintainable CSS

👥 Target Audience
-- Developers looking for a ready-to-use login/registration UI
-- Designers interested in modern form interfaces
-- Students learning about CSS animations and transitions
-- Anyone building a web application requiring user authentication

🤝 Contributing
Feel free to fork this project and submit pull requests with improvements. Suggestions for accessibility enhancements, additional features, or design tweaks are welcome!

📄 License
This project is open source and available for personal and commercial use.


    #Note: This is a front-end interface only. Backend integration would be required for actual authentication functionality.

