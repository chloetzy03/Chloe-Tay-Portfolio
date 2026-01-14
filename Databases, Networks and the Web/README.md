## Databases, Networks and the Web
This coursework project is a dynamic event management web application developed using Node.js, Express, EJS, and SQLite. It allows organisers to register, log in, publish events, customise event sites, and manage ticket types and availability. Attendees can browse published events, view event details, and book tickets.

Key features include:
- Organiser authentication with hashed passwords using bcrypt and session handling.
- Event creation with support for full-priced and concession tickets.
- Custom site configuration per organiser (event branding and info).
- Attendee-facing event pages with real-time ticket availability and booking.
- Secure booking system with validation and error handling.
- Clear site structure following MVC pattern with separation of concerns (routes, views, database).
- EJS templating for dynamic rendering and user feedback (flash messages, validation errors, etc.).

To view the website, download the ZIP file.
#### Using this application ####
To get started:

* Run ```npm install``` from the project directory to install all the node packages.

* Run ```npm run build-db``` to create the database on Mac or Linux 
or run ```npm run build-db-win``` to create the database on Windows

* Run ```npm run start``` to start serving the web app (Access via http://localhost:3000)

1. Register a new organiser account 
2. Log in as an organiser
3. Create and manage events
4. View events as an attendee
5. Book an event as an attendee

#### Additional Libraries ####
These are automatically installed via npm install:
- bcrypt
- express-session 
- connect-flash 
- dotenv 
- ejs  
- express 
- sqlite3 

