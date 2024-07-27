Suhani Singh Portfolio
This is the source code for Suhani Singh 's personal portfolio website. The site features a responsive design, skeleton loading effects, and links to social media profiles.

Table of Contents
Installation
Usage
Features
Contributing
License
Installation
Clone the repository:

git clone https://github.com/suhanisingh13/Portfolio.git
Navigate to the project directory:

cd Portfolio
Open index.html in your preferred web browser.

Usage
To view the portfolio website, simply open index.html in any web browser. The skeleton loading effect will be displayed for 2 seconds before the actual content is shown.

Features
Responsive Design: The site is fully responsive and works well on different screen sizes, including desktops, tablets, and mobile devices.
Skeleton Loading Effect: A skeleton screen is shown while the content is being "loaded", enhancing user experience.
Social Media Links: Links to Suhani singh 's  social media profiles are provided at the bottom of the page.
Smooth Animations: Various animations are used to create a smooth and engaging experience.
Code Overview
HTML
The main structure of the website is in the index.html file. It includes:

A header with navigation links.
A section for the main content, including the skeleton loaders.
Links to social media profiles.
CSS
Styling is done in the index.css file. Key styles include:

General styling for text and layout.
Animations for skeleton loading.
Media queries for responsiveness.
JavaScript
The index.js file contains the logic for the skeleton loading effect. It uses setTimeout to simulate a loading delay and then replaces the skeleton elements with the actual content.

Example Skeleton Loader Replacement
Here's how the JavaScript replaces a skeleton loader with actual content:

document.addEventListener('DOMContentLoaded', () => {
    setTimeout(() => {
        document.getElementById('skeleton-title').outerHTML = '<h1>Hi, I am Suhani Singh</h1>';
        document.getElementById('skeleton-subtitle').outerHTML = '<h3>Python, C, C++</h3>';
        document.getElementById('skeleton-description').outerHTML = '<p>Hi, I am Suhani Singh. I am pursuing B.Tech from BN College of Engineering and Technology, which is situated in Bakshi ka Talab, Lucknow and affiliated to AKTU.</p>';
        document.getElementById('skeleton-button1').outerHTML = '<a href="#">Talk to me</a>';
        document.getElementById('skeleton-button2').outerHTML = '<a href="#">Print resume</a>';
    }, 2000); // Simulating a 2-second loading time
});
Contributing
If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch.
Make your changes and commit them.
Push your changes to your fork.
Create a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.
