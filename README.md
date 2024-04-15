# Renton Technical College CSI-244
<br />    

<div align="center">  
    <img src="logo.jpg" alt="Logo">
    <h3 align="center">Independent Activity 2</h3>
</div>

This repository is a part of CSI-244 at Renton Technical College.

## Independent Activity 2 - Library Application

You have been asked to build a library application with both a frontend and backend.

### Complete the following:

1. Create two folders frontend and backend.
2. In the backend folder create a new node project and install express as well as any other addons you would like to use.
3. You have been provded a books.json file that your backend will need access to.
4. Inspect the books.json file to gain an understanding of the shape of the data.
5. Your backend project must be able to access books.json (You may need to move the books.json file to accomplish this)
6. In the frontend folder you will be creating the necessary JavaScript and HTML files for the library application.

### Backend Requiresments

1. **Create a server.js file with the following endpoints.**
   - GET /books:
        -Retrieve and return a list of all books inside of books.json.
    - POST /books:
        -Create a new book from a post request. Remember post requests pass information in the body.
   - GET /books/:isbn
        -Retrieve and return one book with a matching ISBN.
   - DELETE /books/:isbn
        -Delete the book with a matching ISBN
     
### Frontend Requirements

#### 1. Books List Page
- **Objective:** Display a list of all books.
- **Key Features:**
  - Fetch and display books from the backend.
  - Show title, author, and a brief description for each book.
  - Implement navigation to the Book Details Page upon clicking a book.

#### 2. Book Details Page
- **Objective:** Show detailed information about a selected book.
- **Key Features:**
  - Fetch and display detailed information using the book's ISBN.
  - Display title, authors, ISBN, page count, published date, descriptions, and thumbnail image.
  - Include a link to navigate to the EDIT Book Page.
  - Include a button to DELETE the book.

#### 3. Create Book Page
- **Objective:** All the user to create a book.
- **Key Features:**
  - Use an html form with the for the user to fill out information about the book.
  - Include fields for creating the title, authors, page count, published date, and descriptions.
  - Implement a submit button to save changes, sending data via a POST request to the backend.

#### Design
- **Requirement:** Use Bootstrap to give these pages a professional appearance.

---

You will be graded on the following Criteria:

### Independent Activity 2 - Library Application Grading Rubric

Total Points: 50

#### Project Structure and Setup (10 Points)
- [ ] Two folders created for frontend and backend (2 points)
- [ ] Backend: Node project initialized, Express and other necessary packages installed (4 points)
- [ ] Frontend: JavaScript and HTML files properly set up for the application (4 points)

#### Backend Functionality (15 Points)
- [ ] **GET /books** endpoint correctly retrieves and returns all books (3 points)
- [ ] **GET /books/:isbn** endpoint correctly retrieves a book by ISBN (3 points)
- [ ] **POST /books/** endpoint correctly creates a new book (3 points)
- [ ] **DELETE /books/:isbn** endpoint correctly deletes a book (3 points)
- [ ] Proper error handling and response formatting (3 points)

#### Frontend Functionality (15 Points)
1. **Books List Page (5 Points)**
   - [ ] Correctly fetches and displays books from the backend (2 points)
   - [ ] Displays title, author, and brief description for each book (2 points)
   - [ ] Implements navigation to the Book Details Page (1 point)

2. **Book Details Page (5 Points)**
   - [ ] Correctly fetches and displays detailed information using the book's ISBN (2 points)
   - [ ] Displays all required book information including thumbnail image (2 points)
   - [ ] Includes link to EDIT and button to DELETE the book (1 point)

3. **Create Book Page (5 Points)**
   - [ ] Form to create a new book (2 points)
   - [ ] Includes all required fields and a submit button to save changes (2 points)
   - [ ] Uses a post request to send the data (1 point)

#### Design and Usability (5 Points)
- [ ] Use of Bootstrap or similar framework for a professional appearance (2 points)
- [ ] Consistent and user-friendly interface design (2 points)
- [ ] Responsive design that works on different devices and screen sizes (1 point)

#### Code Quality and Documentation (5 Points)
- [ ] Code is well-organized and properly commented (2 points)
- [ ] README.md file with clear project description, setup, and usage instructions (2 points)
- [ ] Adherence to standard coding conventions and best practices (1 point)

**Total Points: __ / 50**

#### Additional Notes:
- Extra credit may be awarded for additional features, creativity, or particularly efficient solutions.
- Students are encouraged to ask questions and seek clarification if any aspect of the assignment is unclear.


If you have any questions about this assignment please reach out to myself or our TA for this course.
