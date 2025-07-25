## **About the Client**

We are a Brisbane based company with clubs at Ashgrove, Brisbane City, Chermside, Graceville and Westlake.

High Street Gym is Australia's newest brand in health and fitness, with gyms opening throughout the Brisbane metropolitan area. High Street Gym believes fitness comes first and keeping fit and improving your health is not just a fad \- it's a way of life. Whether your goal is weight loss, body building, nutrition or diet improvements, having more energy, or just looking and feeling better \- we're here for you\! 

High Street Gym offers cutting edge exercise such as group fitness for weight loss, circuit training, boxing and karate. Our trainers are all Les Mills accredited instructors and are second to none – all have Bachelor Degrees in Human Movements. 

We are a family operated business that has little to do with the rest of the fitness industry. Our gym world does not include the annoying telemarketers or membership consultants. Our gyms speak for themselves, our members do our marketing. We believe that word of mouth has way more credibility than something that a marketing machine dreams up.  You are always welcome to look through any of our gyms at your own pace, with no pressure whatsoever. With hard-selling 'health club' sales consultants hustling you on every corner, we pride ourselves on being a refreshing change from that. Our 'no obligation, no pressure' attitude is clearly evident with our $10 CASUAL visit rate.

We have created gyms that we would love to train in and share that passion and enthusiasm with our valued members. Our gyms have an old school feel with a new school attitude\!

We are open 24:7. YOU can now train any time you like, weekdays, weekends & public holidays. WE ARE OPEN\! Unlike other so called 24:7 gyms, we are staffed all the time. If you need a late-night workout, a protein bar or shake, supplements or a cool t-shirt, we are open for you. Our class times change constantly so check out on the web site for the timetable at each of our clubs.

Current sessions/activities include:

* Yoga

* Pilates

* Abs 

* HIIT or high-intensity interval training

* Indoor cycling

* Boxing

* Zumba

Other activities will be added if they are requested by gym members and trainers are available.


## **Project Specification:**

You are employed by Uptown IT’s Creative Department as a Web Developer. Your manager has given you a new project to design, develop and test a new gym management system with accompanying mobile first web application. 

The client, High Street Gym, requires the web-based management system and a database to enable management of session bookings for a variety of activities offered across various locations, and general administrative functionality. Once the management system is implemented, an accompanying mobile first web application should be developed, that aims to provide first-class support for viewing and managing sessions, bookings, and microblog posts from mobile devices.

### **Initial Specifications**

The following specifications are from the initial client meeting and may not include all required functionality. Follow up with your project manager (teacher) to clarify any existing or additional specifications. Ensure all communications are recorded in using the appropriate logs.

#### ***Responsive Design***

Both web interfaces/sites must incorporate a high level of responsive design, including but not limited to:

* Support for screen sizes ranging from desktop to mobile (2840px to 360px).

* Responsive navigation (use of mobile optimised menus).

* Headers and Footers on every page with navigation and contextual information.

* Dynamic content layouts that adjust to the current device viewport.

* The use of images, icons, and graphics.

* Forms that apply good practices to enable easy data entry.

* Accessibility considerations: contrast, scale, layout, and metadata for assistive software.

#### ***Website login (user authentication and authorisation)***

The site must allow users to login using an email address and password. Every user in the system is assigned a role (member, trainer, administrator), which determines what features and functions are accessible to them.

#### ***Class Bookings***

Users must be able to view available scheduled sessions on a calendar and make a booking, with the ability to select the specific trainer if more than one of the same class type is scheduled at that time. Users must also be able to view the session they have booked (bookings) and have the option to cancel those booking.

#### ***Member Microblog***

Members must be able to make posts to a shared blog, a blog post consists of a subject and body content (text only for now). Members should be able to delete only their own posts. Administrators can delete any posts. Anyone (any role) can view the blog, including unauthenticated users.

#### ***Management Features***

Administrators must have administrative CRUD functions for users, posts, sessions, bookings, activities, and locations.

Search functionality must be provided to administrators on some CRUD screens:

* Filtering sessions by date range  
* Filtering sessions by trainer  
* Filtering bookings by member 

#### ***Additional Notes***

Foreign keys should never be displayed to any users of the system, database joins must be used to present human readable alternatives instead. The site must apply security best practices, including but not limited to, input validation, sanitisation, and query parameter binding.

### **Deliverables – Gym Management System (Web Development 1 \- ICTDBS507, ICTWEB513)**

The client has required the design, development, and testing of a responsive web-based management system for their gym. The management system must feature interfaces used by members, trainers, and managers for various tasks, including but not limited to, account management, scheduling and booking session, microblogging, and administrative functions.

The implementation should be primarily backend focused, using server-side rendering and MVC architecture. It must integrate with a database that supports the features described above (see Database Requirements section for more details).

#### ***Expected pages / interfaces***

* Website login  
  * Register account  
  * Login / Logout  
  * Not authenticated  
* Class bookings  
  * Weekly calendar of all sessions  
  * Personal bookings of sessions for members  
  * Weekly sessions for trainers  
* Member microblog  
  * View post feed  
  * Create post  
* Management features  
  * Users CRUD  
  * Posts CRUD  
  * Sessions CRUD  
  * Bookings CRUD  
  * Activities CRUD  
  * Locations CRUD

### **Deliverables – Web App \- (Web Development 2 \- ICTPRG553, ICTWEB514, ICTWEB518)**

The client has requested that a mobile first web application be developed to provide an enhanced mobile experience for members and trainers. The mobile first interface must provide an improved schedule and session/booking management functionality, it does not need to implement all the existing management features included in the backend. The implementation must use client-side rendering code that communicates with the existing backend using a JSON web API.

The sample wireframes provided on the right provide a rough idea of the kind of interface the client is expecting. You are welcome to adapt and improve the design, so long as all required functionality is still incorporated.

The client has also specifically requested XML export functionality for two kinds of data. The first allows trainers to export their scheduled sessions for the week, so that they can be imported into their personal calendar. The second allows for members to export all their previous bookings, including the associated activity information, so it data can be imported into their fitness tracking applications.

#### ***Expected pages / interfaces***

* Login  
* Register  
* Timetable (showing sessions for the current week)  
  * Create booking from scheduled session  
* Microblog feed (with create post functionality)  
* XML Export  
  * Export scheduled sessions (for trainers only)  
  * Export previous bookings with activity data (for members only)

## **Database Requirements:**

A conceptual entity relationship diagram of the database structure is presented below. You can add to, modify, and improve the database structure as required to suit the project but you cannot remove any tables or relationships.

The database must be validated to ensure that:

* Key constraints are enforced.  
* Referential integrity constraints rules have been observed.  
* Datatypes match \- especially in primary foreign key relations  
* Export/dump database file (SQL extension) and keep it as backup in case you need to recover the structure and/or data.

You will need to determine and document the required columns using various requirements gathering techniques, including but not limited to via meetings with the client (teacher).

![A diagram of a structureDescription automatically generated][image1]

[image1]: <data:image/png;base64,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>