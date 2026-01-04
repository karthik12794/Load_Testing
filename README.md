# Load_Testing
# Load Testing Task  
# CODTECH Internship - Task 4  

**Company:** CODTECH IT SOLUTIONS  
**Intern Name:** Kandimalla Karthik  
**Intern ID:** CTIS2128  
**Domain:** Software Testing  
**Duration:** 4 Weeks  
**Mentor:** Neela Santosh  

---

## Task Description

As part of my internship at CODTECH IT SOLUTIONS, I was assigned **Task-4: Load Testing with Gatling**. The objective of this task was to perform **advanced load testing** on a sample web application using **Gatling**, a powerful open-source load testing tool. The main goal was to simulate multiple users accessing a web application simultaneously and evaluate its performance under heavy load conditions.  

Load testing helps identify potential bottlenecks, measure response times, and determine how the system behaves under stress. For this task, I used a **demo web application** and created a simulation script (`LoadTest_Simulation.scala`) in Gatling to replicate realistic user actions including visiting pages, logging in, navigating the application, and logging out. The deliverables include a detailed HTML report, screenshots of key metrics, and a summary of system performance under simulated load.

---

## Simulation Setup

1. **Environment Setup:**
   - Installed **OpenJDK 21** for Java support.
   - Downloaded and extracted **Gatling bundle**.
   - Set the **GATLING_HOME** environment variable correctly to point to the Gatling folder.
   - Opened Gatling via `gatling.bat` in the `bin` folder.

2. **Simulation Script:**
   - Created `LoadTest_Simulation.scala` containing a sequence of HTTP requests simulating user behavior:
     - Open home page
     - Navigate to login page
     - Submit login credentials
     - Visit account summary page
     - Logout
   - Configured **10 virtual users** to simulate concurrent traffic using `atOnceUsers(10)`.
   - Used pauses between actions to mimic real user think time.
   - Configured Gatling HTTP protocol with base URL of the demo application and automatic fetching of embedded resources (images, CSS, JS).

---

## Running the Simulation

- Opened **Gatling via CMD** in the `bin` folder.
- Selected `LoadTest_Simulation` from the simulation menu.
- Entered a run description (optional).
- Gatling executed the simulation and generated a **detailed HTML report** in the `results` folder.

---

## Screenshots Captured

For submission, I captured **three key screenshots** from the report:

1. **summary.png**: Shows the simulation running and completion details in CMD.
2. **global_info.png**: Shows the **Global Information** section of the HTML report including total requests, response times, and percentiles.
3. **graphs.png**: Shows the **Response Time Distribution** and **Throughput** charts illustrating system performance under load.

These screenshots provide a clear and concise representation of the load testing results and system behavior.

---

## HTML Report

The HTML report folder (`computerdatabasesimulation-20260104111438784`) contains all the details of the simulation:

- `index.html` — main report file that can be opened in a browser
- `js/` — JavaScript for interactive charts
- `css/` — styling for report
- `img/` — images used in the charts
- `fonts/` — fonts for report visualization
  ## output

  
