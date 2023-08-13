
# Frappe Dev Hiring Test


## Shelf Ease Application


Created a user-friendly application for a local library to simplify daily tasks. Librarians can manage books, members, and transactions effortlessly. The system allows CRUD operations on books and members, allows book issuance and returns, searches by all parameters, applies rental fees, and enforces a Rs.500 debt limit for members. Integrated Frappe API enables easy book imports, supporting parameters like title and author. Made simple code structure and clean. Abstracted functions ensure code reusability, with concise SQL queries for efficient data handling. Deployment on Vercel.



## Contents
- Description
- Features 
- Tech Stack
- Screenshots
## Features
 - Login Authentication and logout
 - Import Books: Librarians can import books into DB (PostGre SQL). Allows Count, Title, Author, Isbn, Publisher, Pages as params.
 - Add / Delete books: Add or Delete books from the postgre SQL. Only unissued books can be deleted.
 - Issue books: Search by title and isbn, allows to list to be produced in front of the librarian, on the detail page, allows the list of members to whom the book can be issued. For issuing, debt must be less that Rs.500
 - Return books:  Showed all the books assigned to members and the librarian can return the book from the member. The dues are recalculated once returned.
 - All penalty: Concisely see the dues on issued books.
 - Montly Report: See the month's report for the amount of transaction and books in stock.
 - Add / Remove members: Add a member to the membership list or delete member if has no pending dues.
 - Search DB: Search the whole DB by 5 params.

 
## Tech Stack

- Flutter
- Dart
- Python
- Flask
- PostgreSQL
- Vercel (For Hosting)
- Supabase (DB hosting)
- Github
## Screenshots



| Login Page  | Home Page | Search Books |
| ------------- | ------------- | ------------- |
| <img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/546fa23d-270b-402a-bbac-4a600353914a.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/b0ed4a9d-7c37-4743-b4cb-0f444c5f1414.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/3eb82318-c0e7-4084-899b-7675e456c7ee.jpg" width="180" height="400"> |
| Content Cell  | Content Cell  | Content Cell  |
