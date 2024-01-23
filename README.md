# CSE 437s Week 2: Build a To-Do App

This assignment challenges you to design and build a simple to-do application using your chosen programming language. The app should allow users to create, manage, and track their tasks.

## Objectives:

- Apply user interface (UI) design principles to create a clear and intuitive interface.
- Implement effective data storage and retrieval mechanisms.
- Gain experience with testing and debugging your code.

## Required Functionality:

- **Adding tasks:** Users should be able to add new tasks with a title, due date (optional), and priority level (optional).
- **Viewing tasks:** Tasks should be displayed in a list or other suitable format, showing title, due date, and priority (if applicable).
- **Marking tasks complete:** Users should be able to mark tasks as completed, which could visually distinguish them from incomplete tasks.
- **Deleting tasks:** Users should be able to delete tasks they no longer need.
- **Persistence:** Tasks should be stored and retrieved from persistent storage (e.g., file system, database) so they persist even after the app is closed.
- **Hosting:** Use Github Pages (see below for instructions).

## Suggestions:

### Front-End

- **HTML/CSS/JavaScript:** For building the user interface and handling user interactions.
- **React or Vue.js:** Frontend libraries/frameworks to simplify the development of interactive user interfaces.

### Backend

- **Node.js with Express:** A lightweight and flexible backend framework for handling server-side logic and API requests.

### Databases

- **SQLite:** A lightweight, file-based database that's easy to set up for small projects.
- **MongoDB:** A NoSQL database that's simple to use and suitable for quick development.
- **Google Firebase:** Firebase provides a NoSQL database called Firestore, which you can use to store and retrieve your todo data. It also offers authentication services, which can be useful for user management in the future.

## Considerations:

- **User experience:** Choose a framework with a focus on building intuitive and responsive UIs.
- **Development time:** Pick a framework that matches your experience and project timeline.
- **Scalability:** Consider future growth of your app and choose a technology stack that can handle it.

## Hosting with Github Pages:
Certainly! Here are step-by-step instructions for students to host their To-Do App websites on GitHub Pages after accepting the assignment from GitHub Classroom:

### Hosting To-Do App on GitHub Pages
1. **Make sure you've accepted the Github Classroom assignment**
2. **Create a `docs` Folder:**
   - GitHub Pages requires a `docs` folder for projects that don't use the default `gh-pages` branch. Create a `docs` folder at the root of your project:
     ```bash
     mkdir docs
     ```

3. **Configure GitHub Pages in Repository Settings:**
   - Go to your GitHub repository.
   - Click on "Settings" and scroll down to the "GitHub Pages" section.
   - Set the source branch to `main` (or the branch where your code resides) and choose the `docs` folder as the root directory.

4. **Commit and Push:**
   - Commit your changes, including the new `docs` folder, to your local repository:
     ```bash
     git add .
     git commit -m "Add docs folder for GitHub Pages"
     git push origin main
     ```

5. **Check GitHub Pages URL:**
   - After pushing the changes, go back to the "GitHub Pages" section in your repository settings. You should see a link to your hosted To-Do App.

6. **Verify Deployment:**
   - Open the provided GitHub Pages URL in your web browser to verify that your To-Do App is successfully deployed.
