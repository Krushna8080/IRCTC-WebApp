------------------------------------------------------------
Train Ticketing System: E-Ticketing System for IRCTC-like Application – FINAL
------------------------------------------------------------

INSTRUCTIONS:
-------------
Before proceeding with any file changes or code generation, please do the following:

1. Thoroughly read and analyze the entire blueprint below.
2. Take some time to "think" about every aspect of the project—including train management, catalogue browsing, passenger addition, booking operations, cancellation, booking history, and optional search functionality.
3. Review the Train Ticketing rule file (train_rules.txt) to ensure that all dependency checks, backup routines, logging, and consistency verifications are applied before making any changes.
4. Verify that all dependencies (Node.js, React.js, MongoDB, etc.) are present and that any previous file state and history are accounted for.
5. Develop a comprehensive plan based on the blueprint below, considering industry-level best practices and ensuring that every module integrates with its dependencies.
6. Only after this thorough review and planning process, begin the creation (coding) process for the application.
7. Remember: All changes must honor the Train Ticketing rule file – ensuring dependency checks, backup snapshots, and integrity verifications are performed before any modifications.

------------------------------------------------------------
Train Ticketing System: Detailed Blueprint
------------------------------------------------------------

Project Overview:
-----------------
The Train Ticketing System is a web application designed to mimic an IRCTC-like e-ticketing platform. The system will allow:
- **Admins** to manage (create, update, delete) train schedules and set pricing.
- **Customers** to browse a catalogue of trains, select journeys (e.g., Mumbai to Chennai), add multiple passengers with various attributes (gender, age, discount eligibility), complete a checkout process, view booking history, and cancel tickets if necessary.
- An optional search functionality to help users quickly find trains.
-add mock data for all the trains and for everything which looks like real and so many data 

Functional Requirements:
------------------------
1. **Train Management (CRUD Operations):**
   - Admin role exclusively manages the train list and pricing details.
   - Create, read, update, and delete operations for train schedules (routes like Mumbai to Chennai, etc.).

2. **Catalogue Browsing:**
   - Allow customers to view an up-to-date catalogue of available trains.

3. **Train Selection:**
   - Enable users to select a specific train from multiple options.

4. **Passenger Details:**
   - Permit adding multiple passengers per booking.
   - Capture essential details: gender, age, and applicable discounts (which may influence ticket pricing).

5. **Ticket Booking:**
   - Provide a clear checkout process enabling users to finalize their ticket booking.

6. **Booking History:**
   - Maintain a detailed record of all bookings made by the user for future reference.

7. **Ticket Cancellation:**
   - Allow customers to cancel tickets directly from their booking history with proper confirmation and refund processing.

8. **Search Functionality (Optional):**
   - Implement search capabilities for users to filter trains based on criteria like destination, departure time, or price.

Non-Functional Requirements & Best Practices:
-----------------------------------------------
- **Dependency & Environment Verification:**
  - Before any modifications, run dependency checks in both backend and frontend directories (e.g., using `npm install`).
  - Verify that the MongoDB instance is properly configured and accessible.
  
- **Code Quality & Standards:**
  - Follow industry best practices with modular design, clear naming conventions, comprehensive comments, and error handling.
  - Ensure that API endpoints are well-documented and consistently used between the backend and frontend.
  
- **User Interface & Experience:**
  - Develop a responsive, intuitive React.js frontend that seamlessly consumes backend APIs.
  
- **Deployment Considerations:**
  - Prepare environment-specific configurations (using `.env` files) and document any custom setup instructions.
  - Ensure logging, backup routines, and consistency verifications are in place as per the Train Ticketing rule file.

Tech Stack:
-----------
- **Frontend:** React.js
- **Backend:** Node.js
- **Database:** MongoDB

Project Setup & Dependency Management:
----------------------------------------
1. **Backend Setup:**
   - Navigate to the backend directory.
   - Execute `npm install` to install all dependencies.
   - Confirm MongoDB connectivity and API endpoint configuration.
   - Document any additional setup steps in the project’s `README.md`.

2. **Frontend Setup:**
   - Navigate to the frontend directory.
   - Execute `npm install` to install all dependencies.
   - Ensure that API endpoints are properly referenced within the React application.
   - Include any necessary build or deployment scripts in your documentation.


------------------------------------------------------------
FINAL REMINDER:
------------------------------------------------------------
Before starting any code generation or modifications, ensure that the Train Ticketing rule file (train_rules.txt) is loaded and applied. Verify that all project dependencies are intact and that backup and integrity checks are in place. Only then proceed with implementing the code based on this blueprint.

------------------------------------------------------------
END OF CONTEXT FILE
------------------------------------------------------------
