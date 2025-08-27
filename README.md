## IT Project : UoN Student Marketplace ##
### Titled : Uni-Trade / Uni-T ###

**A Gumtree-style online marketplace built for students at the University of Newcastle (UoN). This web application facilitates the buying and selling of goods, services, and accommodation within the UoN community.**

---

### **Team Members**
* Firaas Ahmed Nizar
* Fozan Mohammed Azhar
* Sheikh Muhammad Furqan
* Diego Banda Aburto
* Pratham Khadka

---

### **Tech Stack**
### Application Architecture

This project is built using a **three-tier architecture**. This design separates the application into :  the Presentation Tier (frontend), the Logic Tier (backend), and the Data Tier (database). This separation allows for parallel development, scalability, and organized code management.

### Flow of Information

The communication between the tiers is linear and follows a standard client-server model:

`React Frontend (Client Browser)  <---(apicalls)--->   Node.js/Express API (Server)   <---(queries)--->  SQL Server (Database)`

---

#### 1. Presentation Tier (Frontend)
* **Members:** yet to decide*
* **Technology:** **React** (with TypeScript)
* **Responsibility:** manage the user interface (UI) and user experience (UX).  handling all visual elements, user interactions, and makes  API calls to the Logic Tier to fetch or send data.


---

#### 2. Logic Tier (Backend)

* **Members:** yet to decide*
* **Technology:** **Node.js** with the **Express** framework
* **Responsibility:** The backend is a RESTful API that serves as the core  of the application. 
    * Handling business logic and application rules.
    * Authenticating and authorizing users.
    * Processing incoming HTTP requests from the React frontend.
    * Communicating with the Data Tier to perform database operations (Create, Read, Update, Archive).
    * Sending data back to the frontend in a structured JSON format.

---

#### 3. Data Tier (Database)
* **Members:** yet to decide*
* **Technology:** **Microsoft SQL Server**
* **Responsibility:** This tier is responsible for the  management of application data. 
    * Storing data in a structured, relational format.
    * Ensuring data integrity and security.
    * Executing queries sent from the Logic Tier.
    * The database is only ever accessed by the backend; the frontend has no direct access.


---


### **Project Management**

This project's tasks and progress are managed on our Jira board.

**[Jira Board ](https://uonitproject.atlassian.net/jira/software/projects/UNIT/boards/1?atlOrigin=eyJpIjoiMWIzMjE0N2Q5NWIwNGU3ZGJjMzY4NjljMmU2ZTlkMTgiLCJwIjoiaiJ9)**

