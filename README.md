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
GitHub Pages allows you to host static websites directly from your GitHub repository. Follow these steps to host your To-Do App:

1. **Create a GitHub Repository:**
   - Go to [GitHub](https://github.com/) and log in or sign up.
   - Click on the "+" sign in the top right corner and choose "New repository."
   - Name your repository (e.g., todo-app) and add a brief description.
   - Initialize the repository with a README if you haven't already.

2. **Upload Your To-Do App Files:**
   - Upload all your To-Do App files (HTML, CSS, JavaScript, etc.) to the GitHub repository.
   - Commit the changes to the repository.

3. **Enable GitHub Pages:**
   - In your repository, go to the "Settings" tab.
   - Scroll down to the "GitHub Pages" section.
   - In the "Source" drop-down menu, select the branch where your main To-Do App files are located (usually, it's the `main` branch).
   - Click "Save."

4. **Access Your Hosted To-Do App:**
   - After saving, GitHub Pages will provide a link to your hosted To-Do App. It may take a few minutes for the changes to take effect.
   - You can find the link under the "GitHub Pages" section in the repository settings.

5. **Share Your To-Do App:**
   - Copy the provided link and share it with others. Now, your To-Do App is accessible online.

**Note:**
- GitHub Pages hosts static websites, so if your To-Do App relies on server-side logic (e.g., Node.js with Express), you may need to explore alternative hosting options.
- Ensure that your repository structure is suitable for GitHub Pages, and all necessary files (HTML, CSS, JavaScript) are in the main branch.

By following these steps, students can easily host their To-Do Apps on GitHub Pages and share their work with others.
