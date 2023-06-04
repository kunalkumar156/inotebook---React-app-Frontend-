# 📚 MERN Stack Notebook App

This is a web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) that allows users to create and manage their notes in a cloud-based notebook.

## 🚀 Features

- 🔐 User Registration: Users can create an account by providing a unique username and password.
- 🔒 User Authentication: Users can log in to access their account and manage their notes.
- 📝 Create Notes: Users can create new notes by providing a title and content.
- ✏️ Edit Notes: Users can edit the title and content of their existing notes.
- ❌ Delete Notes: Users can delete unwanted notes from their notebook.
- ☁️ Cloud Storage: The notes are stored in a MongoDB database, allowing users to access them from anywhere at any time.

## 💻 Technologies Used

- Frontend: React.js
- Backend: Express.js
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)

## ⚙️ Prerequisites

Before running the project locally, make sure you have the following installed:

- Node.js
- MongoDB

## 🛠️ Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Install the dependencies for the backend:

```bash
cd backend
npm install
```

3. Install the dependencies for the frontend:

```bash
cd ../frontend
npm install
```

## ⚙️ Configuration

1. Backend Configuration:
   - Create a `.env` file in the `backend` directory.
   - Set the following environment variables in the `.env` file:
     - `MONGODB_URI`: MongoDB connection string.
     - `JWT_SECRET`: Secret key for JSON Web Tokens.

2. Frontend Configuration:
   - Open the `frontend/src/config.js` file.
   - Update the `API_BASE_URL` variable with the backend API base URL.

## 🚀 Running the Application

1. Start the backend server:

```bash
cd backend
npm start
```

2. Start the frontend development server:

```bash
cd frontend
npm start
```

3. Open your browser and navigate to `http://localhost:3000` to access the application.

## 👨‍💻 Further Development

You can further enhance the application by implementing additional features such as:

- 📧 Password reset functionality.
- 📄 Markdown support for note content.
- 🗂️ Note categorization or tagging.
- 👥 Collaborative note sharing.

---


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
