
# Frappe Dev Hiring Test


## Shelf Ease Application


Created a user-friendly application for a local library to simplify daily tasks. Librarians can manage books, members, and transactions effortlessly. The system allows CRUD operations on books and members, allows book issuance and returns, searches by all parameters, applies rental fees, and enforces a Rs.500 debt limit for members. Integrated Frappe API enables easy book imports, supporting parameters like title and author. Made simple code structure and clean. Abstracted functions ensure code reusability, with concise SQL queries for efficient data handling. Deployment on Vercel.



## Contents
- Description
- Features 
- Tech Stack
- Screenshots
- How to Run ?
- DB Structure
- API Docs
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



| Login Page  | Home Page | Search Books | Dashboard |
| ------------- | ------------- | ------------- |  ------------- |
| <img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/546fa23d-270b-402a-bbac-4a600353914a.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/b0ed4a9d-7c37-4743-b4cb-0f444c5f1414.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/3eb82318-c0e7-4084-899b-7675e456c7ee.jpg" width="180" height="400"> |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/fdd2eb87-fac0-417f-a932-183ec7e2a0cc.jpg" width="180" height="400"> 

| Profile  | Import Books | Add Books | Import Confirm Screen |
| ------------- | ------------- | ------------- |  ------------- |
| <img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/4da885f3-a161-417d-87fb-79524cfa3d0a.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/d7209e1d-d07a-478b-b265-a0f6b835985e.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/4115f611-b987-4bf7-842a-df8925039796.jpg" width="180" height="400"> |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/5983d1dc-12bf-4457-acba-152181e03d3a.jpg" width="180" height="400"> 

| Issue Books  | Book Detail | Select Member for Issuing | Book Search Result with filters |
| ------------- | ------------- | ------------- |  ------------- |
| <img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/8c941164-b4b3-41ff-bcd5-8ff4411dd667.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/e32f31f7-0ed4-4544-ab27-269e0d2f16b7.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/6e4d88b3-6bd5-4420-9263-d6748bb9dfc2.jpg" width="180" height="400"> |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/d0226286-415b-456a-8d2e-c1e4d702f6d9.jpg" width="180" height="400"> 

| All Members  | Add Members | Report | Members respective books issued |
| ------------- | ------------- | ------------- |  ------------- |
| <img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/7aad5513-8440-4a9b-afba-1ff134c555e5.jpg" width="180" height="400">  |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/b19bb2f0-ce3f-412e-842d-365be8b68d21.jpg" width="180" height="400"> |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/e6f20dbc-7f75-43c6-955c-06f0dd892ddf.jpg" width="180" height="400"> |<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/2f1b0bf7-d0e2-4997-8007-de0ed0d5f2d1.jpg" width="180" height="400">  
## How to Run ?

Download the App's APK file from here: https://drive.google.com/drive/folders/1oqIPQqbu8Rf9z_MVq1O87sr23w7G9uce?usp=sharing

Login Credentials:

username: admin
password: admin_123
## DB Structure & Schemas

<img src="https://github.com/khchoudhary8/KumarHarshFrappeApiDevHiringTest/assets/76583677/4e472df2-318c-417c-859a-ad047a1ba686.png" width="780" height="400"> 
