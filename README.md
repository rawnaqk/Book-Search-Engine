# Book Search Engine
  
  ![License](https://img.shields.io/badge/license-MIT-blue.svg)
  
  ## Description
  This is a full-stack application that allows users to search for books using the Google Books API, manage user authentication, and save or remove books from their personal list. The app has been refactored from a RESTful API to a GraphQL API using Apollo Server, providing a more flexible and efficient data handling approach. Users can login, signup, search for books, save their favourites, and view their saved books. 
  
  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)
  
  ## Installation
  1. Clone the Repository; `git clone <repo link>`
  2. Navigate to the Directory; `cd book-search-engine`
  3. Install Dependencies; `npm install`
  4. Set up Environment Variables; `Create a .env file in the root directory and add variables: MONGODB_URI=your_mongodb_uri GOOGLE_BOOKS_API_KEY=your_google_books_api_key JWT_SECRET=your_jwt_secret`
  5. Start the Development Server; `npm start`
  6. Visit `http://localhost:3001` in your browser to view the application

  ## Usage
  Login/Signup: Click on the Login/Signup menu option to open the authentication modal. Toggle between Signup and Login to create a new account or login.
  Search for Books: On the home page, use the search bar to enter a book title or author. Click the submit button to view search results from Google books.
  Save Books: After searching, click the "Save" button on a book to add it to your saved list.
  View and Manage Saved Books: Click on the "Saved Books" from the navigation bar to view your saved books. Remove books from your saved list by clicking on the "Remove" button next to each book.
  Logout: Click the "Logout" button to log out of your account and return to the home page.
  
  ## License
  This project is licensed under the MIT license.
  
  ## Contributing
  N/A
  
  ## Tests
  There are no automated tests set up for this project. You can manually test the application by following the usage instructions above.
  
  ## Questions
  For questions about the project, please contact me via 
  GitHub: [rawnaqk](https://github.com/rawnaqk)  
  or email me at: rawnaq.kabairzad@gmail.com
