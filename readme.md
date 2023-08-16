# CSS Animated Stopwatch

This project demonstrates creating a functioning, animated stopwatch primarily using CSS animations. The stopwatch, displayed at the center of the page, includes both a minute and second hand, a set of clock indicators and numbers.

## Design
The design is flexible and customizable based on css variable values. Currently, the clock displays with several elements such as hands, indicators, a center dot and numbers, all aligned at absolute positions within the clock circle.

## Implementation
The implementation utilizes SCSS with a BEM naming strategy for the CSS classes. Animation for the hands of the stopwatch was created using `@keyframes` for a smooth motion around the clock face. 

The project's file structure is divided into individual parts for clean and maintainable code, easy to follow for developers. 

Variable mixins, such as `circle($radius)` and `rectangle($length, $width)`, were used to ensure modularity and reusability and reduce repetitive code.

## Features
* Animated second and minute hands with precise timing
* Design flexibility: Easy customization based on SCSS variables
* BEM naming strategy for organized and easy-to-understand CSS
* Use of mixins for code efficiency 

This project is a great example of the power of CSS animations and the kind of interactivity that can be achieved with pure CSS.

# Getting Started

Here are the instructions for downloading and running this project locally on your system. This project assumes that Node.js is installed in your environment.

## Prerequisites

* Node.js

## Steps

1. **Clone the Repository**

   In your terminal, navigate to your preferred directory and run the following command:

   ```bash
   git clone https://github.com/zynkd/layout_stop-watch.git
   ```
    
2. **Navigate into the Project Directory**

    ```bash
    cd layout_stop-watch
    ```
   
3. **Install the Dependencies**

   Now run the following command to install the project dependencies:

   ```bash
   npm install
   ```
   
4. **Starting the Project**

   Start the project by running the following command:

   ```bash
   npm start
   ```
   
   This command will start a local development server. You can now view the project in your browser at `http://localhost:3000` (or the specified port displayed in your terminal).

Please note: any changes to the source code will automatically refresh the page in your browser while the development server is running.

## Notes

* If Node.js is not installed in your system, download it from [the official site](https://nodejs.org/) and follow the instructions to install it.
* If you run into any issues related to missing dependencies or project setup, make sure to check the project’s `package.json` file to verify it's properly set up.
