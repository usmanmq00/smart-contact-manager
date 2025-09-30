# smart-contact-manager
This project manages and stores contacts on cloud.

## Features of SCM
1. User Signup with email and password [OAuth2 standard]
2. Verify account using email verification link [By default, account will be deactivate after signup] ⇒ both ways handled using OTP or link
3. User Signup with Google and Github  [OAuth2 standard]
4. Add the contact with picture 
5. Contact picture is uploaded to cloud [AWS, Cloudinary]
6. User can view all the contacts or Search specific contact
7. Can view the contact details
8. Compose and send email directly from SCM
9. Email contains text and attachment
10. Update, Delete and Search contact
11. Pagination
12. Export the contact data to excel/pdf/csv
13. Mark favorite contact
14. See and edit Profile details
15. Dark and Light theme
16. Provide Feedback

## Technologies Used
1. Latest Spring Boot [Spring Security is updated]
2. Spring Framework
3. Spring MVC ⇒ Handle requests and responses
4. Spring Data JPA [ORM] ⇒ Database Independent → mysql/postgres/etc
5. OAuth for social login - for google and github login 
6. Thymleaf template engine ⇒ Generate HTML from backend to handle dynamic data
7. Validation ⇒ Spring Boot Form Validator
8. Spring Security ⇒ for securing routes
9. Mysql / postgressql database
10. Java email service/api ⇒ for sending and receiving emails
11. AWS/Cloudinary SDK ⇒ for storing files
12. JavaScript [Dark and Light theme]
13. Tailwind CSS ⇒ Front End UI
14. Flowbite components ⇒ already made components
15. pdf / excel tools for generating reports
