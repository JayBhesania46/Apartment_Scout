# Apartment Scout
The objective of this project is to create a user-friendly platform that caters to the unique needs of international students seeking accommodation near their college campus. The platform will allow students to post apartment listings and communicate with local scouts who can visit and verify the apartments in person.

Apartment Scout is a web application designed to help international students find suitable apartments near their college or university by connecting them with local scouts who can visit, verify, and document the apartments on their behalf. The platform is built using Node.js, HTML, CSS, and JavaScript, and aims to save time and resources for both students and scouts.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Features](#features)
  - [Homepage](#homepage)
  - [User Authentication](#user-authentication)
  - [User Dashboard](#user-dashboard)
  - [Apartment Listing Management](#apartment-listing-management)
  - [Scout Dashboard](#scout-dashboard)
  - [Extra Features](#extra-features)

## Getting Started

These instructions will help you set up a local development environment for Apartment Scout.

### Prerequisites

Ensure that you have the following software installed on your local machine:

- Node.js (version 14.x.x or higher)
- NPM (version 6.x.x or higher)
- axios (version 1.3.4 or higher)
- bcryptjs (version 2.4.3 or higher)
- cookie-parser (version 1.4.6 or higher)
- express (version 4.18.2 or higher)
- express-handlebars (version 7.0.4 or higher)
- express-session (version 1.17.3 or higher)
- handlebars (version 4.7.7 or higher)
- mongodb (version 4.13.0 or higher)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/JayBhesania46/Apartment_Scout.git
```

2. Navigate to the project directory:

```bash
cd ApartmentScouting
```

3. Install the required dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

5. Open your browser and go to `http://localhost:3000` to access the web application.

### Important Note

If you are a Windows user, modify the `Settings.js` file and change the `serverURL` to `'mongodb://127.0.0.1:27017'`.

If you are a macOS user, modify the `Settings.js` file and change the `serverURL` to `'mongodb://localhost:27017/'`.

### Running the Seed File

To populate the database with sample data, run the following command in your terminal:

```bash
npm run seed
```

The password for all users to log in to the application is "Cs546$Password", as provided in the `seed.js` file.

## Features

### Homepage

The homepage serves as the landing page for the application. It provides an overview of the platform, its purpose, and the features offered to international students and local scouts.

### User Authentication

The authentication system allows international students and scouts to sign up and log in using their email and password. 
It ensures secure access to the platform and personalized user experiences.

### User Dashboard

The user dashboard serves as a central hub for international students. It allows them to manage their apartment listings, communicate with subscribed scouts, and view relevant information. The dashboard provides a seamless and efficient experience for users.

### Apartment Listing Management

International students can post, edit, delete, and manage their apartment listings through the platform. This feature enables them to showcase their available accommodations to potential tenants easily.

### Scout Dashboard

The scout dashboard is a dedicated area for local scouts. It provides them with functionalities to search for apartments, subscribe to listings, and manage their tasks efficiently. The dashboard streamlines the scouting process and facilitates effective communication between scouts and students.

### Extra Features

In-app Messaging: ApartmentScouting includes an in-app messaging system that facilitates communication between users and scouts. This feature provides a convenient way to discuss.