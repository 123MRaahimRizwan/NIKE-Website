# Nike Website

This repository contains the **Nike Website**, a web application built using HTML, JavaScript, and **Tailwind CSS**. The website is designed to showcase Nike's products with a clean, modern user interface and responsive design.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)

## Overview

The **Nike Website** is a front-end project built using Tailwind CSS to create a responsive and aesthetically pleasing design. It features various sections highlighting Nike's product range, focusing on mobile responsiveness and performance optimization.

## Technologies Used

- **HTML** for structuring the web pages
- **JavaScript** for interactivity
- **Tailwind CSS** for styling and responsiveness
- **Vite** for fast builds and hot module reloading

## Folder Structure

- **public/**: Contains public assets like images, fonts, etc.
- **src/**: This is where the main website code lives (HTML, JS, and Tailwind CSS).
- `.eslintrc.cjs`: ESLint configuration file for maintaining code standards.
- `.gitignore`: Specifies files that Git should ignore.
- `index.html`: The main entry point of the website.
- `package.json`: Contains the list of dependencies and scripts for the project.
- `package-lock.json`: Locks the dependency versions for consistent builds.
- `postcss.config.js`: PostCSS configuration for using Tailwind CSS.
- `tailwind.config.js`: Configuration file for customizing Tailwind CSS.
- `vite.config.js`: Configuration for Vite, the build tool.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/nike-website.git

2. Navigate to the project directory:
    
    ```bash
    cd nike-website

3. Install the dependencies:
    ```bash
    npm install

4. Run the development server:
    ```bash
    npm run dev

This will start a local development server using Vite. The website will be available at `http://localhost:3000`

## Usage
1. After setting up the local environment, you can develop by editing the files in the src/ folder.

2. All styles are managed by Tailwind CSS in a utility-first manner, making it easy to adjust layouts and responsiveness directly in HTML files.

3. To build the website for production:
    ```bash
    npm run build

This will generate the optimized files in the `dist/` folder.

## Customization

You can customize the design by modifying the **Tailwind CSS** configuration file `(tailwind.config.js)` or by directly editing the HTML and JS files. Tailwind allows for extensive customization, from color schemes to spacing and layout.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
    ```bash
    git checkout -b feature/your-feature-name
    
3. Commit your changes and push the branch:
    ```bash
    git push origin feature/your-feature-name

4. Submit a pull request.
