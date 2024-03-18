# 🤖PromptBook | Next.js CRUD App for Advanced AI Prompts

## 👀[Demo Link](https://promptbook-webapp.netlify.app/)

🦾This project is a full-stack application built with Next.js that allows users to create accounts, share, and read prompts based on specific topics for advanced AI. It provides a platform for users to explore and contribute to the development of AI models.

## 🧰Tech Stack

* **Frontend:** Next.js, Tailwind CSS
* **Backend:** Node.js, Express (implicitly included with Next.js), Mongoose
* **Authentication:** next-auth (using GitHub provider)

## 💡Features

* **User Authentication:** Users can create accounts and sign in securely using their GitHub accounts.
* **Prompt Creation and Sharing:** Users can create prompts for advanced AI, categorize them with topics, and share them with the community.
* **Prompt Reading and Exploration:** Users can browse through prompts based on various filters (username, prompt description, tag name).
* **User Profiles:** Users can view their own profiles and the profiles of other users, showcasing their usernames, and created prompts.
* **Filtering:** Powerful search filters enable users to find specific prompts based on different criteria.

## ⛑️Project Structure

* **`app`:** Contains all Next.js page components for the user interface (UI), such as signup, login, home page, profile pages, etc.
* **`api`**: Contains the reuseable api routes.
* **`components`:** Reusable UI components used throughout the application.
* **`utils`:** Houses utility functions like database.js.
* **`models`:** Defines Mongoose schemas for user and prompt data.
* **`styles`:** Tailwind CSS configuration and custom styles.

## 🎯Deployment

* **`CI/CD Pipeline`:** I continuously deployed this project along with every commit by creating a CI/CD Pipeline between  **Github** and **Netlify**.

## 🧱Getting Started

1. Clone this repository.
2. Install dependencies: `npm install`
3. Configure your database connection (refer to Mongoose documentation).
4. Configure your NextAuth.js provider (GitHub) according to their documentation.
5. Run the development server: `npm run dev`

## ⚡Usage

* Visit `http://localhost:3000` in your browser to access the application.
* Create a new account or sign in using your GitHub account.
* Explore the various features for creating, sharing, and reading prompts.
* Utilize the search filters to find specific prompts.

## ♟️Conclusion

This Next.js application provides a robust platform for users to collaborate and leverage AI technology. By utilizing Mongoose, Tailwind CSS, and NextAuth.js, the application ensures data persistence, a user-friendly interface, and secure authentication.

## ⏭️Further Enhancements

* Implement user roles and permissions for more granular access control.
* Integrate social sharing functionalities for increased community engagement.
* Explore real-time updates for a more dynamic and interactive experience.

