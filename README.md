# Book-Search-Engine

Welcome to the Book Search Engine

## Introduction

The Book Search Engine, a feature-rich platform designed for avid readers and book enthusiasts. This application allows users to search the extensive Google Books API for any book title, author, or keyword, providing access to detailed information about each book, including the title, authors, description, and a link to view more details on Google Books. Registered users can create an account, log in securely, and save books they find interesting to their profile. This way, they can build a personal library of saved books, which can be viewed, managed, or removed at any time.

Built on a full-stack MERN architecture (MongoDB, Express, React, and Node.js), the Book Search Engine leverages GraphQL through Apollo Server to efficiently manage data queries and mutations, replacing the traditional RESTful API approach. This use of GraphQL provides a streamlined and scalable method for handling user interactions and database communications, ensuring a responsive and modern user experience.

## :ledger: Index

- [About](#beginner-about)
  - [File Structure](#file_folder-file-structure)
  - [Build](#hammer-build)
  - [Deployment](#rocket-deployment)
- [Community](#cherry_blossom-community)
  - [Contribution](#fire-contribution)
- [Resources](#page_facing_up-resources)
- [Gallery](#camera-gallery)
- [Credit/Acknowledgment](#star2-creditacknowledgment)
- [License](#lock-license)

## :beginner: About

The Book Search Engine leverages modern web technologies to enable users to explore books and manage their reading interests. Users can register, log in, search for books via the Google Books API, and save books to their profile. The application includes user authentication, book-saving functionality, and a polished UI.

### Features include:

- **GraphQL API**: Uses Apollo Server to handle GraphQL queries and mutations, enabling efficient data handling.
- **User Authentication**: Users can securely sign up, log in, and manage their sessions with JWT-based authentication.
- **Search & Save Books**: Integrated with Google Books API to enable search functionality. Users can save books and manage their saved list.
- **Responsive Design**: Built with React for an intuitive and responsive front-end experience.
- **Environment Variables**: dotenv for secure management of sensitive data such as database credentials.

### :file_folder: File Structure

Below is a view of the file structure deployed to GitHub.

```plaintext
BOOK-SEARCH-ENGINE/
│
├── client/                     # React front-end for the application
│   ├── src/
│   │   ├── assets/             # Static assets
│   │   ├── components/         # React components (LoginForm, Navbar, etc.)
│   │   ├── pages/              # Pages (SavedBooks, SearchBooks)
│   │   ├── utils/              # GraphQL queries, mutations, auth utilities
│   │   ├── App.js              # Main application component
│   │   └── index.js            # Entry point for React
│   ├── public/                 # Public files
│   └── package.json            # Front-end dependencies and scripts
│
├── server/                     # Backend files
│   ├── config/                 # Configuration files
│   │   └── connection.js       # MongoDB connection setup
│   ├── controllers/            # Backend controllers
│   ├── models/                 # Mongoose models for MongoDB
│   ├── routes/                 # Express routes for handling requests
│   ├── schemas/                # GraphQL typeDefs and resolvers
│   ├── utils/                  # Authentication utilities
│   └── server.js               # Main server file
│
├── .gitignore                  # Ignored files for version control
├── package.json                # Root dependencies and scripts
└── README.md                   # Project documentation (this file)
```

### :hammer: Build

**MVC Structure**:
- **Models**: Managed by Mongoose, defining database entities for Users and Books.
- **Views**: React components provide a responsive and interactive UI.
- **Controllers**: GraphQL resolvers handle queries and mutations, streamlining data flow.

**Authentication**:
- Secure user sessions through JWT tokens and bcrypt for password hashing.

**Database**:
- **MongoDB** with Mongoose for scalable and flexible data storage.

**GraphQL API**:
- **Apollo Server**: Handles GraphQL requests, allowing efficient data retrieval and manipulation.

**Environment Management**:
- **dotenv**: Protects sensitive data, managing environment variables securely.

**Deployment**:
- **Render**: Hosted on Render for a reliable and scalable deployment.

**Version Control**:
- Git and GitHub for project tracking, with regular commits and collaborative development.

### :rocket: Deployment

- Application is deployed on Render: [View live app](https://book-search-engine-backend-hwm2.onrender.com)

## :fire: Contribution

Your contributions are welcome and appreciated. Here's how you can contribute:

### 1. **Report a bug**
If you come across a bug, please let me know by creating an issue [here](https://github.com/ProjectAdam95/Book-Search-Engine/issues).

### 2. **Request a feature**
If you have an idea that you think would improve the project, feel free to request it [here](https://github.com/ProjectAdam95/Book-Search-Engine/issues). 

### 3. **Create a pull request**
If you want to contribute code:
- Fork the repository.
- Create a new branch.
- Submit a pull request with your proposed changes.


## :page_facing_up: Resources

- **Software**: 
  - **VS Code**: Development environment for efficient coding and debugging.
  - **Git Bash**: Command-line interface for version control and repository management.

- **Libraries**: 
  - **Express.js**: Handles server-side routing and middleware.
  - **Mongoose**: Manages MongoDB interactions for a flexible and scalable database.
  - **Apollo Server**: Provides GraphQL API functionalities for efficient data queries and mutations.
  - **GraphQL**: Enables seamless data fetching and manipulation.
  - **React**: Powers the responsive and interactive front end.

- **APIs**: 
  - **Google Books API**: Provides book data to support search and save features within the app.

  ## :camera: Gallery

Here’s the preview photos of the deployed page!:

- [Screenshots](https://imgur.com/a/EHFy65u)

## :star2: Credit/Acknowledgment

Developed by [Adam Todorovic](https://github.com/ProjectAdam95).

## :lock: License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
