# Workout frontend

This is a basic MERN (MongoDB, Express, React, Node.js) stack frontend project using React Context and Hooks. It's set up using `npx create-react-app` and includes a simple structure for managing workout data.

## Project Structure

```plaintext
├── README.md
├── package-lock.json
├── package.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.js
    ├── components
    │   ├── Navbar.js
    │   ├── WorkoutDetails.js
    │   └── WorkoutForm.js
    ├── context
    │   └── WorkoutContext.js
    ├── hooks
    │   └── useWorkoutsContext.js
    ├── index.css
    ├── index.js
    └── pages
        └── Home.js
```

## Getting Started
To run this project locally, follow these steps:

1. Clone the repository to your local machine.

```bash
git clone <repository-url>
cd <project-directory>

```

2. Install dependencies using npm:
```bash
npm install

```

3. Start the development server:
```bash
npm start

```

The app should now be running on http://localhost:3000.

## Project Overview

### Context and Hooks
This project uses React Context and custom hooks to manage the state of workout data.

* **WorkoutContext.js**: This context provider manages the state for the workout data and provides functions to update it.

* **useWorkoutsContext.js**: This custom hook allows components to easily access the workout data and related functions.

### Components
* **Navbar.js**: A simple navigation bar component.

* **WorkoutForm.js**: A form component for adding new workouts.

* **WorkoutDetails.js**: A component to display the details of a workout.

### Pages
* **Home.js**: The main page of the application where workouts are displayed and can be added.

### Styling
Styling is done using the default CSS file (`index.css`). You can customize the styling to fit your needs.

### Deployment
To deploy this project to a production environment, you can use platforms like Heroku, Vercel, or Netlify. Make sure to set up environment variables for your production MongoDB connection string.

### Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgments
This project was created as a learning exercise for building a MERN stack application with React Context and Hooks.
Thanks to the open-source community for providing the tools and resources used in this project.
