Travel and Logistics Automation
A Java-based application designed to automate booking operations for a travel and logistics company. This dynamic menu-driven system enables users to manage bookings, calculate fares, and handle account security efficiently.

Features
Admin User Registration: Add new admins with secure credentials, account status management, and failed login attempt tracking.
Account Security: Automatic account locking after 5 invalid login attempts.
Journey Planning:
Validate travel dates, source, destination, and available vacancies.
Calculate dynamic fares with weekend surcharges and GST.
Allow rescheduling of journeys.
Interactive Design: Displays the company logo on startup for a professional touch.
Data Validation: Ensures accurate input for all user and booking details.
In-memory Data Management: Utilizes Collection API (List, Map) for efficient data storage and retrieval.
Technologies Used
Java: Core Java for backend development and application logic.
Collection API: Efficient data handling using List and Map.
SQL: Reliable storage and retrieval of user and booking data.
File Handling: To display the company logo on application startup.
Java 8 LocalDate: For robust and modern date handling.
How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/travel-and-logistics-automation.git
Open the project in your favorite Java IDE (e.g., IntelliJ, Eclipse).
Compile and run the Main class to launch the application.
Follow the menu options displayed in the console to use the application.
Challenges Faced
Ensuring dynamic fare calculations with GST and weekend surcharges.
Managing data validation without a database by leveraging in-memory data structures.
Implementing robust exception handling to ensure smooth user interaction.
Key Learning Outcomes
Mastery of Core Java and Collection API for real-world problem-solving.
Building a secure and scalable application for booking management.
Hands-on experience with in-memory data handling and dynamic validation logic.
Future Improvements
Add a graphical user interface (GUI) for a better user experience.
Integrate a database for persistent data storage.
Expand the system to include additional travel management features like cancellations and promotions.
