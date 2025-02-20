Razorpay Project
This project is a web application built using Tailwind CSS and Vite. It showcases various features and services offered by Razorpay, including payment solutions, business banking, and more.

Project Structure : -

images/
    api-driven-icon.svg
    autopay-icon.svg
    buisness-banking.png
    capital-credit-icon.svg
    comanies.png
    core-features-sectionBg.svg
    CTABg.svg
    ctaImg.svg
    current-icon.svg
    dashboard-reporting-icon.svg
    easy-integration.svg
    facebook-icon.svg
    fake-company-logo.png
    favicon.png
    feature-section-2BG.svg
    feature-section1-dottedrows.png
    features-wave.svg
    features2-wave.svg
    footer-certificate-1.png
    ...
index.html
main.css
package.json
postcss.config.js
tailwind.config.js



Getting Started : -

Prerequisites
Node.js
npm


Installation
Clone the repository: - 

git clone https://github.com/your-username/razorpay-project.git

Navigate to the project directory: - 

cd razorpay-project


Install the dependencies: - 

npm install

Running the Project

To start the development server, run:

npm start



Project Configuration
Tailwind CSS
The Tailwind CSS configuration is defined in tailwind.config.js:
module.exports = {
  content: ["*"],
  theme: {
    extend: {
      fontFamily: {
        mullish: ["Mulish", "sans-serif"],
      },
      colors: {
        deepBlue: "#02042a",
        lightBlue: "#2b84ea",
        lightBlue300: "#4b94ed",
        lightBlue500: "#0b72e7",
        greenLight: "#61cea6",
        grayText: "#818597",
        lightGray: "#e2e2e2",
        grayBlue: "#344a6c",
        deepBlueHead: "#162f56",
        gray2: "#525a76",
      },
    },
  },
  plugins: [],
}


PostCSS
The PostCSS configuration is defined in postcss.config.js:

module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
}


Main CSS
The main CSS file main.css includes Tailwind CSS directives:


@tailwind base;
@tailwind components;
@tailwind utilities;




License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Tailwind CSS
Vite
Feather Icons


