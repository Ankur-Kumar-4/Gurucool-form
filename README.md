# Multi-Step Form with Data Persistence

This project is a multi-step form built using React and Tailwind CSS that includes data validation, local storage persistence, and a responsive design. The form collects user information across multiple steps, ensuring data is saved after each step, even after a page refresh.

## Table of Contents

- [Key Features](#key-features)
- [Live Demo](#live-demo)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Running the Project](#running-the-project)
- [Deploy link](#deploy-link)

## Key Features

- Multi-step form with progress bar
- Data persistence via `localStorage`
- Responsive design using Tailwind CSS
- Data validation for form fields
- Clean and modular React component structure

## Live Demo

Check out the live demo of the project deployed here:  
[Live Demo Link](https://multi-stepform-gurucool.netlify.app/)

## Technologies Used

- React
- Tailwind CSS
- Local Storage for data persistence

## Setup Instructions

Follow the steps below to set up and run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/Ankur-Kumar-4/Gurucool-form
cd multi-step-form
```

### 2. Install Dependencies

Before starting the project, install the necessary dependencies using npm:

```bash
npm install
```

This will install all required Node.js packages, including React and Tailwind CSS.

### 3. Configure Tailwind CSS

Tailwind CSS has already been pre-configured in this project. Ensure that the following files are correctly set up:

tailwind.config.js: Configuration for Tailwind's theme and styles.
postcss.config.js: PostCSS file for processing Tailwind directives.
index.css: Global CSS file that imports Tailwind's styles using the following directives:

css
Copy code
@tailwind base;
@tailwind components;
@tailwind utilities;

### 4. Local Storage Setup

Data entered into the form is stored in localStorage. If you need to clear this data during testing or debugging, you can manually clear localStorage in your browser’s developer console:

javascript
Copy code
localStorage.clear();
This step is optional but useful for ensuring clean data during testing.

### 5. Development Server

To start the development server and see your application in action, run:

```bash
npm run dev
```

Once the server is running, open your browser and navigate to:
http://localhost:5173/
The app will automatically reload when you make changes to the code.

### 6. Building for Production

If you want to build the app for production, run:

bash
Copy code
npm run build
This command will create an optimized production build of the app inside the dist/ folder.

### 7. Running Tests (Optional)

If you have written unit tests for the form components, you can run the tests using:

```bash
npm test
```

Ensure you have the necessary testing frameworks installed, such as Jest, if you plan to run unit tests.

### Running the Project

To run the project after setting it up, use the following command:

```bash
npm run dev
```

This will start the project in development mode. Visit http://localhost:5173/ in your browser to view the app.
