# Journi
---
**Journi: A MERN Stack-Based Multiuser Journaling App**

Journi is an advanced multiuser journaling application developed using the MERN stack, which includes MongoDB, Express.js, React.js, and Node.js. This application is designed to provide a seamless and intuitive platform for users to document their thoughts, experiences, and daily activities. Here's a detailed description of Journi:

### Key Features

1. **User Registration and Authentication**:
   - **Sign Up**: Users can create new accounts using a registration form that collects essential information such as username, email, and password.
   - **Login**: Existing users can log in using their credentials. Secure authentication mechanisms ensure user data privacy and security.
   - **Session Management**: While tokens or `express-session` are avoided based on user preferences, robust session management ensures that users remain authenticated during their interaction with the app.

2. **Profile Management**:
   - **Profile Update**: Users can update their profile information, including username, name, email, and age, through a dedicated profile update form.
   - **Profile Picture**: Integration with Multer allows users to upload and update their profile pictures effortlessly.

3. **Journaling**:
   - **Create Entries**: Users can create new journal entries with rich text formatting options. This feature enables users to express themselves fully.
   - **Read Entries**: Users can view their journal entries in a well-organized manner. The entries are displayed with timestamps, allowing users to track their journaling history.
   - **Update Entries**: Users can edit their existing journal entries to make corrections or add additional details.
   - **Delete Entries**: Users have the option to delete their journal entries if they no longer wish to keep them.

4. **User Interface**:
   - **Home Page**: A welcoming home page that provides an overview of the app's features and a prompt to log in or register.
   - **Navigation Bar**: A responsive and intuitive navigation bar allows users to easily access different sections of the app. The navigation bar is not displayed on the login and register pages, providing a clean and focused user experience during authentication.
   - **React and React Bootstrap**: The front end is built using React, with styling and components from React Bootstrap, ensuring a modern and responsive design.

5. **Backend**:
   - **Express.js and Node.js**: The backend server is built with Express.js and Node.js, providing a robust and scalable environment for handling API requests and managing user data.
   - **MongoDB**: MongoDB is used as the database to store user information, journal entries, and other relevant data. It ensures efficient data retrieval and storage.

6. **Security**:
   - **Data Validation**: All user inputs are validated to prevent common security vulnerabilities such as SQL injection and XSS attacks.
   - **Password Hashing**: User passwords are hashed before being stored in the database, ensuring that even in case of a data breach, passwords remain secure.

7. **Performance**:
   - **Efficient Data Handling**: The app is designed to handle multiple users and their journaling activities efficiently, with optimized database queries and server responses.
   - **Responsive Design**: The app is fully responsive, providing an optimal experience across various devices, including desktops, tablets, and smartphones.

### Technical Stack

- **Frontend**: React.js, React Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **File Upload**: Multer
- **Styling**: CSS with a mix of light and dark themes as per user preference

Journi aims to be the go-to platform for individuals who love to document their lives and thoughts. Its user-friendly interface, combined with powerful backend capabilities, makes it a reliable and enjoyable journaling app for users of all ages. Whether you are a daily journaler or someone who writes occasionally, Journi provides the tools and environment to make your journaling experience enriching and satisfying.
