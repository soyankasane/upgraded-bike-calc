BIKEABLE KENYA - Offline Bike Fit Calculator
This repository contains a standalone, offline-first web application for calculating bicycle fit. It's designed for BIKEABLE KENYA to help customers get accurate bike size recommendations for Road, Mountain, and Gravel bikes. The calculator is built with vanilla HTML, Tailwind CSS, and JavaScript, ensuring it's lightweight, portable, and requires no internet connection to function.

🚲 Key Features
Offline First: The entire application is contained in a single index.html file. It can be downloaded and run directly in any modern web browser without needing a server or internet access.

Multiple Bike Types: Users can select from Road, Mountain, or Gravel bikes to get tailored sizing recommendations.

Dual Calculation Modes:

Quick Estimate: Provides a fast and easy bike size recommendation based solely on the user's height.

Detailed Fit: Delivers a more precise calculation using inseam, torso, and arm length for a comprehensive fit analysis.

User-Friendly Interface: A clean, responsive layout that works seamlessly on desktops, tablets, and mobile devices.

Interactive Measurement Guide: Includes inline SVG diagrams that visually explain how to take accurate body measurements (inseam, torso, and arm length), reducing user error.

Branded for BIKEABLE KENYA: The UI is styled with the brand's signature ocean blue, black, and white color scheme.

🛠️ How It Works
The calculator uses established anthropometric formulas to recommend bike frame sizes and other key measurements.

Select Bike Type: The user first chooses the type of bike they are interested in.

Enter Measurements:

For a quick estimate, only height is required. The app uses a height-based chart to suggest a general frame size (e.g., Small, Medium, Large, or cm range).

For a detailed fit, the user can also input their inseam, torso, and arm length. The application then uses specific multipliers for the selected bike type to calculate a more precise frame size, saddle height, and effective top tube length.

Calculate & View Results: The results are instantly displayed in clear, easy-to-read cards. The app provides a note clarifying whether the result is a quick estimate or a detailed recommendation.

🚀 Getting Started
Download the index.html file from this repository.

Open the file in any modern web browser (like Chrome, Firefox, Safari, or Edge).

The bike fit calculator is ready to use immediately.

There are no dependencies, build steps, or server configurations required.

🎨 Brand Integration & Customization
The application is fully branded for BIKEABLE KENYA. Key brand elements are defined in the <style> section of the HTML file, making them easy to modify:

Colors: The primary brand color (ocean-blue) can be changed by updating the corresponding CSS classes (.bg-ocean-blue, .text-ocean-blue, etc.).

Logo/Brand Name: The brand name is present in the header and footer and can be easily updated.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to contact us at [bikeableke@gmail.com/@bikeableke on socials] for any questions or feedback!
