EmployWise Assignment

This is a React-based assignment for EmployWise, which includes user authentication, user listing with pagination, and basic CRUD operations.

Project-structure

/employwise-app
  /src
    /components
      - Login.jsx
      - UserList.jsx
      - EditUser.jsx
      - PrivateRoute.jsx
    - App.jsx
    - index.js
    - styles.css
  - package.json
  - README.md

Features Implemented

1.User Authentication (Login & Logout)

2.Protected Routes (Only logged-in users can access user list)

3.User List with Pagination

5.Edit & Delete User

6.API Calls using Axios

7.React Router for Navigation

Technologies Used

1.React.js (Frontend Framework)

2.Axios (For API Calls)

3.React Router (Navigation)

4.CSS (Styling)

Setup Instructions

Clone the Repository

git clone https://github.com/IndhiraSivasakthi/Employ_wise_assignment
cd employwise-assignment

Install Dependencies

	npm install

Start the Development Server

	npm start

The app will start at http://localhost:3000/.

API Endpoints Used

Method	Endpoint	Description
POST	/api/login	User Login
GET	/api/users?page=1	Fetch User List
PUT	/api/users/{id}	Edit User
DELETE	/api/users/{id}	Delete User


Assumptions & Considerations

•	Login credentials:
o	Email: eve.holt@reqres.in
o	Password: cityslicka
•	LocalStorage is used for authentication state.
•	API doesn't persist delete operations (users reappear on refresh).
•	Pagination is handled dynamically based on API response.

Author

INDHIRA SIVASAKTHI

1.Email: sivasakthiindhira@gmail.com

2.GitHub: https://github.com/IndhiraSivasakthi/

3.LinkedIn: https://www.linkedin.com/in/indhira-siva-sakthi-b50209334/





