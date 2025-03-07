Portfolio Website with Contact Form
This is a personal portfolio website that showcases my skills, projects, education, and experience. It also includes a contact form powered by Web3Forms for easy communication.

Table of Contents
Project Overview

Features

Folder Structure

Technologies Used

Setup Instructions

Usage

Contact Form Integration

License

Project Overview
This project is a responsive portfolio website built using HTML, CSS, and JavaScript. It includes sections for:

Home (Introduction)

About Me

Education

Experience

Skills

Projects

Contact (with a Web3Forms-powered contact form)

The website is designed to be clean, modern, and user-friendly, with smooth animations and a dark mode toggle.

Features
Responsive Design: Works on all devices (desktop, tablet, mobile).

Dark Mode: Toggle between light and dark themes.

Scroll Animations: Smooth scroll animations using ScrollReveal.

Contact Form: Integrated with Web3Forms for email submissions.

Dynamic Content: Skills and projects are dynamically displayed.

Social Links: Links to LinkedIn, GitHub, and email.

Folder Structure
Copy
portfolio-website/
│
├── assets/                # Contains images and icons
│   └── img/
│       └── profile.gif, mahesu.png, etc.
│
├── Contact/               # Contact form files
│   ├── contact.html       # Contact form HTML
│   ├── style.css          # Contact form CSS
│   └── script.js          # Contact form JavaScript
│
├── index.html             # Main HTML file
├── styles.css             # Main CSS file
├── main.js                # Main JavaScript file
├── script.js              # Web3Forms JavaScript
└── README.md              # Project documentation
Technologies Used
HTML5: Structure of the website.

CSS3: Styling and animations.

JavaScript: Dynamic functionality and interactivity.

Web3Forms: For handling contact form submissions.

ScrollReveal: For scroll animations.

Font Awesome: Icons for social links.

Google Fonts: Poppins font for typography.

Setup Instructions
Clone the Repository:

bash
Copy
git clone https://github.com/Mahesu-AMC/portfolio-website.git
cd portfolio-website
Open the Project:

Open the index.html file in your browser to view the website.

Set Up Web3Forms:

Replace the access_key in contact.html with your own Web3Forms access key.

html
Copy
<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
Run HTML
Customize Content:

Update the index.html file with your personal information, skills, projects, etc.

Replace images in the assets/img/ folder with your own.

Usage
Navigation: Use the navigation bar to scroll to different sections of the website.

Dark Mode: Toggle dark mode using the button (if implemented).

Contact Form: Fill out the form in the Contact section to send a message.

Contact Form Integration
The contact form is powered by Web3Forms. Here's how it works:

The form submits data to the Web3Forms API.

Web3Forms processes the data and sends an email to your registered email address.

The JavaScript in script.js handles form submission and displays a success or error message.

Steps to Set Up Web3Forms:
Sign up at Web3Forms.

Create an access key.

Replace the access_key in contact.html with your key.

License
This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as needed.

Contact
For any questions or feedback, feel free to reach out:

Email: mahesu96@gmail.com

LinkedIn: Mahesuwaran

GitHub: Mahesu-AMC

Enjoy using the portfolio website! 🚀

