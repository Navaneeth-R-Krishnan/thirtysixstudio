# Thirtysix Studios Landing Page

This project is a frontend implementation of the landing page for **Thirtysix Studios**, built using JavaScript and React. The page features smooth and interactive animations powered by **GSAP (GreenSock Animation Platform)**.

## Features

- Replication of the **Thirtysix Studios** landing page design.
- Smooth and engaging animations for page elements (powered by GSAP).
- Responsive design to ensure proper rendering across various devices (desktop, tablet, mobile).
- Interactive scrolling effects, including animations triggered by user scroll.
- Clean, modular, and optimized codebase.

## Tech Stack
- **GSAP (GreenSock Animation Platform)**: Library for high-performance, smooth animations.
- **React**: Custom scripts for controlling animation sequences and user interactions.

## Live Demo

You can check out the live demo of the project by visiting [thirtysixstudio-eta.vercel.app](https://thirtysixstudio-eta.vercel.app)

## Installation

### Prerequisites

To get started with the project locally, make sure you have the following installed on your machine:

- A modern web browser (Google Chrome, Firefox, etc.)
- A code editor (VS Code, Sublime Text, etc.)

### Clone the repository

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/thirtysix-studios-landing-page.git
    ```

2. Navigate to the project directory:

    ```bash
    cd thirtysix-studios-landing-page
    ```

3. Open the `index.html` file in your browser to view the project.

### Running the Project

This project doesn't require any backend or build tools. You can simply open the `index.html` file in your browser to see the animations in action. If you prefer to use a local server for development, you can use tools like **Live Server** in VS Code or any other local server solution.

## GSAP Animations

This project uses **GSAP** for animating elements. Some key animations include:

- **Page Load Animations**: Initial fade-in effects and scaling transitions.
- **Scroll-triggered Animations**: Elements animate as the user scrolls through the page.
- **Button Hover Animations**: Interactive hover effects on buttons and links.

### Installation of GSAP

If you want to experiment with or extend the GSAP animations, you can install GSAP using npm or directly link the CDN:

- **CDN**: In the `index.html`, add the following script tag in the `<head>` section:

    ```html
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.1/gsap.min.js"></script>
    ```

- **npm**: Install GSAP via npm:

    ```bash
    npm install gsap
    ```

Then, import GSAP in your JavaScript files:

```javascript
import gsap from 'gsap';
