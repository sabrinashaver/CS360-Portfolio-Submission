# CS360-Portfolio-Submission
**App Overview & User Needs:**
The goal of this project was to design and implement a functional Android mobile application that allows users to create an account, log in securely, and manage event data stored in a persistent SQLite database. The app was designed to address the need for simple, local event tracking with optional SMS notifications for upcoming events. Core user needs included secure access, reliable data storage, clear event visibility, and the ability to add, update, and delete events without unnecessary complexity.

**Screens, Features, & User-Centered UI Design:**
To support these needs, the application includes a login and account creation screen, an event display screen showing stored data in a structured list, and a permission screen that clearly explains SMS notification usage. The UI design prioritizes clarity, minimal input requirements, and logical navigation between screens. User-centered design principles were applied by keeping layouts uncluttered, using clear labels and prompts, and ensuring that optional features, such as SMS notifications, don't block core functionality if permissions are denied. These design decisions were successful in creating an interface that is intuitive and accessible for first-time users.

**Coding Approach & Development Strategy:**
My coding approach focused on modular design and readability. I separated responsibilities across activities and helper classes, such as using a database helper to manage SQLite interactions and keeping UI logic within activity classes. I followed Android best practices including consistent naming conventions, in-line comments, and logical method structure. Incremental development and frequent testing helped isolate issues early. These strategies are directly transferable to future projects, especially larger applications that require maintainable and scalable codebases.

**Challenges & Innovation:**
One of the primary challenges was integrating multiple app components—authentication, database persistence, UI navigation, and SMS permissions—into a cohesive application. I had to adapt my implementation to ensure that optional permissions did not disrupt the overall app experience. Overcoming this required careful conditional logic and thoughtful UI messaging to guide the user without forcing permissions. This experience strengthened my understanding of real-world Android development constraints.

**Strengths:**
I was particularly successful in implementing the database structure and application logic in a clean and organized manner. Manual code review confirmed strong encapsulation, logical flow, and adherence to best practices. The SMS permission workflow and launch plan further demonstrate my ability to think beyond basic functionality and consider usability, privacy, and deployment readiness.

**Closing Reflection:**
This project represents a significant milestone in my development as a computer science student. From initial planning through final implementation, it required the integration of technical skills, user-centered design, and problem-solving. While configuration issues highlighted areas for growth, the overall project demonstrates my ability to design and build a functional mobile application suitable for inclusion in a professional portfolio.
