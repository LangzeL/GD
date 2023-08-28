## Website Developing Work Progress

<table border="1">
    <thead>
        <tr>
            <th>Task Progress / Week</th>
            <th>Week 1</th>
            <th>Week 2</th>
            <th>Week 3</th>
            <th>Week 4</th>
            <th>Week 5</th>
            <th>Week 6</th>
            <th>Week 7</th>
            <th>Week 8</th>
            <th>Week 9</th>
            <th>Week 10</th>
            <th>Week 11</th>
            <th>Week 12</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Planning & Design</strong></td>
            <td colspan="12"><span style="color:rgb(0, 150, 139)">██████████████████</span><span style="color:rgb(255, 192, 203)"></span> <span><strong>Completed 100%</strong></span></td>
        </tr>
        <tr>
            <td><strong>Front-end Development</strong></td>
            <td colspan="3" style="border-right: none;"></td>
            <td colspan="9" style="border-left: none;"><span style="color:rgb(0, 150, 139)">███████████████</span><span style="color:rgb(255, 192, 203)">███ </span><span><strong>Completed 70%</strong></span></td>
        </tr>
        <tr>
            <td><strong>Back-end Development</strong></td>
            <td colspan="5" style="border-right: none;"></td>
            <td colspan="7" style="border-left: none;"><span style="color:rgb(0, 150, 139)">###</span><span style="color:rgb(255, 192, 203)">### </span><span><strong>Completed ##%</strong></span></td>
        </tr>
        <tr>
            <td><strong>Testing & Feedback</strong></td>
            <td colspan="12"><span style="color:rgb(0, 150, 139)">███████████████████</span><span style="color:rgb(255, 192, 203)">░░░░ </span><span><strong>Completed ##%</strong></span></td>
        </tr>
        <tr>
            <td><strong>Bug Fixing & Optimization</strong></td>
            <td colspan="12"><span style="color:rgb(0, 150, 139)">███████████████████████</span><span style="color:rgb(255, 192, 203)">░░░░ </span><span><strong>Completed ##%</strong></span></td>
        </tr>
    </tbody>
</table>

--------------------------------------------------------------------------------------------------------------------------------------------------------------

**Team structure**

| **Role**           | **Student Name** |
| ------------------ | ---------------- |
| **Product Owner**  | Langze Lu        |
| **Scrum Master**   | Langze Lu        |
| **QA Engineer**    | Wenda Zhang      |
| **Architect**      | Shanqing Huang   |
| **UI/UX designer** | Jing Yun Tan     |
| **Dev engineer**   | Yilin Chen       |

| **Development Team**       |                 |
| -------------------------- | --------------- |
| **Tech Lead**              | **Wenda Zhang** |
| **Front end dev engineer** | Langze Lu       |
|                            | Wenda Zhang     |
|                            | Shanqing Huang  |
|                            | Jing Yun Tan    |
|                            | Yilin Chen      |
| **Code maintenance**       | Shanqing Huang  |
| **Debug+test**             | Yilin Chen      |

------------------------

   ## Website Structure:

   #### 1. **Home Page**

   - **Header**: Logo, Navigation (Content pages, Calendar, Courses, Membership, Payment & Donation, Contact Us)

   - Main Content

     - Welcoming text or banner
     - Highlights of upcoming events or offers
     - Cool scroll effects (e.g. parallax, fade in/out animations)
     
   - **Footer**: Phone no, Email, Facebook, and other social media links

   #### 2. **Content Pages**

   - General information about the place, offers, and benefits.
   - Sign-up form for new members.
   - Links to events, calendar, and courses for easy navigation.

   #### 3. **Calendar/Booking Systems**

   - Display of monthly/weekly calendar.
   - Highlight of specific events or courses.
   - Clicking on an event/course will show more details and sign-up options.
   - Notification system for changes in events.

   #### 4. **Course Booking Systems**

   - List of available courses.
   - Details for each course and instructor.
   - Option to sign up for courses.
   - QR code generation for attendees.

   #### 5. **Membership**

   - Details about the membership benefits.
   - Option to change details.
   - Overview of past events/courses attended.
   - Notification system for upcoming events or benefits.

   #### 6. **Payment, Room Hire, & Donation**

   - Options for payments (course fees, room hire).
   - Donation system with various options (one-time, monthly, etc.).
   - Secure payment gateway integration.

   #### 7. **Contact Us**

   - Contact form for inquiries.
   - Direct phone and email links.
   - Links to social media pages.

   ### Features:

   1. **Responsive Design**: Ensure that the website is accessible and looks great on all devices, from desktops to mobile phones.
   2. **Accessibility Features**: Text-to-speech, adjustable font size, high contrast mode, etc.
   3. **Backend System**: To manage members, attendees, payments, and notifications.
   4. **Social Media Integration**: Links and possibly feeds from platforms like Facebook.

   ### Recommended Technologies:

   1. **Frontend**:
      - **Framework**: ReactJS with Next.js (for server-side rendering and better SEO)
      - **Styling**: CSS Frameworks like Bootstrap or TailwindCSS (for a modern look and responsiveness)
      - **Animations**: AOS (Animate On Scroll) for scroll effects.
   2. **Backend**:
      - **Framework**: Node.js with Express.js
      - **Database**: MongoDB or PostgreSQL
      - **Authentication**: Passport.js (for member login and registration)
      - **Notifications**: NodeMailer (for email notifications)
   3. **Other Tools**:
      - **Payment Gateway**: Stripe or PayPal for payment and donation processing.
      - **Calendar**: FullCalendar.js (for displaying and managing events)


--------------------------------------------------------------------------------------------------------------------------------------------------------------

## Weekly objectives, tasks and meeting notes

--------------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 1  

#### Group Goal and Task ：
   Formation of group

   Identification of what client's needed 

   Intitial function needed for Longplace beach Website

   1) Simple welcoming website to bring in new member 
   2) long bleach place offers, general information  
   3) able to reach demographics 
   4) events to sign up  
   5) calendar 
   6) if there are changes, notify people that has registered/ attended, backend  
   7) not only sign up for event but also donation, phone no, Facebook, information at the bottom  
   8) cool actions available when scroll down  
   9) colour of the website – natural, generic, no yellow,  fresh white, green, modern 
   10) functional, user-friendly, look fresh, modern 
   11) accessibility, text, audio, layout, usability 

   5 sections - 

   * Content pages (Sign up)   

   - calendar/ booking systems 
   - course booking systems 
   - membership(does not mean a lot ( no need put too much)) (sign up for some courses free) (send you some information) (receive some benefits) (), change detail, see what it is they have done, notifications (event coming up)  Sign up for a course, attendees take manually for now so… 
   - Digitize attendance, who should be coming, boxes (tick) 

   Qr code   - payment, room hire, donation   -contact use -> phone -> email -> social media  - ability to book . click into yoga, calendar show yoga booking  - membership – donation  - volunteer – hire room 

--------------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 2

#### Group Goal and Task ：

#### Meeting Overview:

   ==Meeting 2 Meeting 1 1st Aug Via Zoom==

   Admin: Langze L

   Paticipent: Wenda Z, Yilin C, Jinyun T, Shanqing H

   1. Gather Client's contact detail ❌ (will be done next week)
   2. Finalise what section of the website do we want to do --> Content Page management + Calendar✔
   3. Decide each team member wants to Contribuild in certain parts✔
   4. Create Motivation model✔
   5. discuss the possibe framework for code ✔
      * front end： react/vue
      * backend： node.js
      * database:   Mysql/MongoDB

   Initial concern:

   6. How do we add web content into database

---------------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 3

#### Group Goal and Task ：create a react app and set up environment for every team member

#### Meeting Overview:

   ==Meeting 3 Meeting 1 8th Aug Via Zoom==

   Admin: Langze L

   Paticipent: Wenda Z, Yilin C, Jinyun T, Shanqing H

   1. **Preliminary Decisions:**
      - Determine the questions we need to ask the client.
      - Establish the content that should be included in our presentation.
   2. **Design Preview:**
      - Provide an initial graphic design draft for the client's review. (we have a sample ver 1 and ver 2 of content page)
   3. **Scheduling:**
      - If things go smoothly, I will aim to schedule a meeting with the client on Wednesday, Thursday, or Friday.
   4. **Online Meeting Proposal:**
      - Explore the possibility of an online meeting with the client.
      - If feasible, I hope that all team members can attend to ensure consistent information and understanding.
   5. **Emphasis on Group Cohesiveness:**
      - Our tutor appears to evaluate based on overall group capability.
      - I hope that this week, our group can surpass other groups in terms of progress.

**Outcome**

**1. Links to Different Areas**

   Navigation Bar: This will provide links to all parts of the website.
   Anchor Links: These allow users to quickly scroll to specific sections of a page.


**2. Content Management**

   We aim to provide an admin dashboard or interface that allows for easy content addition, editing, and removal.


**3. Navigation**

   Top Navigation Bar: This will contain links to the main pages.
   Footer: This will have auxiliary links, including contact details and social media links.
   Sidebar (Optional): Depending on the design, this might provide shortcuts or tools for users.


**4. Search Function**

   This will let users input keywords to search for specific content on the website.

   

**Question to be ask**

   * Are there specific functionalities or features you envision for the content management aspect?
   
   * Regarding the search function, are there any specific features or behaviours you'd like implemented?

---------------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 4

#### Group Goal and Task ：Finalize the home page using react 

#### Meeting Overview:

   ==Week4 meeting 1 16th Aug Via Zoom==

   Admin: Langze L

   Paticipent: Wenda Z, Yilin C, Jinyun T, Shanqing H

**Agenda and Progress:**

1. **Links to Different Areas** ✔
   - Navigation Bar: This feature is complete. It provides links to all parts of the website.
   - Anchor Links: Also complete. These allow users to quickly scroll to specific sections of a page.
2. **Content Management** **TBD**
   - Goal: To provide an admin dashboard or interface that allows for easy content addition, editing, and removal.
3. **Navigation** ✔
   - Top Navigation Bar: This feature is complete and contains links to the main pages.
   - Footer: Also complete. It contains auxiliary links, including contact details and social media links.
   - Sidebar (Optional): Depending on the design, this might provide shortcuts or tools for users.
4. **Search Function** **TBD**
   - Goal: To let users input keywords to search for specific content on the website.

**Challenges and Considerations:**

- How to link tables with URLs, considering React Router DOM.
- How to connect the front-end to the back-end.

 ==Week4 meeting 2 20th Aug Via Zoom==

   Admin: Langze L

   Paticipent: Wenda Z, Yilin C, Jinyun T, Shanqing H

**Current Progress:**

1. **Content Page Formation**
   - Creation of the Nav Bar
   - Creation of the dropdown menu
   - User login page (without actual functionality)
   - Dropdown animations
   - Main content section
   - Creation of three subsections
   - Contact section and social media links
2. **Preliminary Understanding of Backend**
   - Installation of Flask (entire team should ideally have the React and Flask environment set up by today)
   - Use of Axios library (for simplifying HTTP requests to the server)
   - Flask's login library with example code.

**Challenges and Considerations:**

- Uncertainty with the backend -> Need to coordinate with other teams.
- Lack of specific server information.
- Adding features to make our website stand out.
- Debugging and testing steps.
- Client requirements are still at a preliminary stage. Need to constantly report progress to the client and confirm requirements.

**Work Allocation for Next week:**

- Complete the layout for each content page.
- For the backend, coordinate with other teams and aim to create an admin dashboard.
- Whether online or offline, organize a meeting with the client to walk through the process.

---------------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 5

#### Group Goal and Task ：

#### Meeting Overview:

   ==Week 5 Meeting 1 22nd Aug Via Zoom==

   Admin: Langze L

   Paticipent: Wenda Z, Yilin C, Jinyun T, Shanqing H

**Agenda for Client Meeting:**

1. **Editing Feature Expectations**
   - What kind of editing features are you expecting? A simple textbox for content changes, or something more user-friendly?
2. **Homepage Feedback**
   - Do you like the current homepage? If not, what specific changes would you like to see?
3. **Admin Roles**
   - Different admins might have different permissions. We need confirmation from you to understand what kind of admin roles we should implement.
4. **Unique Selling Points**
   - What features would make this website stand out from competitors or similar websites? For instance, are you interested in having a chatbot?
5. **Layout Consistency**
   - Do you want a unified layout for different content pages or do you prefer each page to have its own unique format?
6. **Section Redundancy**
   - Some elements, like those in the navbar, are repeated in the contact section. Should the new contact section be more minimalistic?
7. **Content Consistency**
   - Should the text on each page remain consistent with the original website?
8. **Search Function**
   - Do you still want to proceed with the search function, or should we consider it dropped?
9. **Cover Slide Window**
   - Are you interested in having animated transitions for the slide window on the cover page?
10. **Additional Features for Editing**
    - Do you require additional features like history, restore, backup, picture upload, cropping, and file size limitations for the editing function?
11. **Server and Domain**
    - Could you provide us with server access and the domain name?
12. **Website Deployment**
    - Is this website really going to be used?

This agenda aims to clarify client expectations and ensure that our project aligns with their vision. It will help us in defining the scope and functionalities that need to be developed.

   ==Week 5 Meeting 1 23rd Aug In LBP community centre==

   Admin: Langze L

   Paticipent: Wenda Z, Yilin C, Jinyun T, Shanqing H

   Guest: Client(Cat Beed) 

**Client Feedback Summary:**

1. **Logo & General Design:**
   - The client doesn't require a mural and prefers darker and pink colors. They are not satisfied with the current orange text and wish to change the 'Contact Us' section to a blue background.
2. **Login Portal:**
   - The client wants the color of the login portal changed and suggests different portals for staff/tutors and members.
3. **Sliding Animation:**
   - The client desires automatic sliding animation that stops when the cursor is put over it. They prefer separate text and image boxes that also have sliding animations.
4. **Sponsors:**
   - The client wants the section renamed to "Supported By" and prefers smaller logos.
5. **Contact Us:**
   - The admin login should be at the very bottom. The Instagram link needs correction, and the section should include a 'Subscribe' option. At the very bottom, they want a map, admin login, and address info.
6. **Feature Requests:**
   - The client wants an easy-to-use admin page with functionalities similar to Wix, including preview, publish, and undo options. They also want the flexibility to move images from one column to another.
7. **Database:**
   - Only one type of admin is required. Members also don't need to have different types or levels.
8. **Reference Website:**
   - The client has pointed to the Cockatoo Community House website as a reference, particularly noting the "Sign up to newsletters" feature.
9. **Server Information:**
   - The client is unsure about server details at this time.

This feedback is critical for realigning our project goals and tasks to meet client expectations better. It serves as a guide for the functionalities and design elements that need attention or rework.

==Week 5 Meeting 2 27th Aug Via zoom==

   Admin: Langze L

   Paticipent: Wenda Z, Yilin C, Jinyun T, Shanqing H

**Current Progress:**

1. **Home Page:**
   - The home page is mostly complete, with all subsections having their respective layouts.
2. **Login Page:**
   - A basic login page is ready.
3. **Map:**
   - Preliminary work on including a map is done, but it's not yet added to the site.

**Current Challenges:**

1. **Google API Key:**
   - The client has not provided the Google API key, affecting the integration of certain features like maps.
2. **Edit Feature:**
   - Implementing the edit functionality is challenging. The client wishes for an entire page with a toolbar on the side for intuitive website editing.
3. **Admin Login and Dashboard:**
   - Creating the admin login and dashboard/edit board is still pending.
4. **Admin Login Verification:**
   - Implementing authentication and permission checks for admin login is also a challenge.

Given the current progress and challenges, the next steps involve focusing on implementing the edit feature as described by the client and working on the admin functionalities. The team should also reach out to the client for necessary credentials like the Google API key.

---------------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 6

#### Group Goal and Task ：

#### Meeting Overview:

   ==Meeting 1 8th Aug Via Zoom==