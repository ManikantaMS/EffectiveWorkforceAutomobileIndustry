# CEAI Assessment - Spirit Volvo Used Car Status Dashboard

This repository contains the prototype and documentation for the Customer Engagement and Artificial Intelligence (CEAI) assessment, submitted by Manikanta MS.

## ✅ SECTION A – Real-World Customer Engagement Challenge

### 1. Stakeholder Interview

-   **Stakeholder:** John Ryan
-   **Role:** Partner / Brand Ambassador
-   **Organisation:** Spirit Volvo (OHM Group)
-   **Date:** 24 June 2025

#### Interview Summary

As part of my part-time role at Spirit Volvo, I spoke with John Ryan, Partner and Brand Ambassador, regarding key customer engagement challenges observed in the used car sales process. He identified a recurring issue that significantly affects both sales performance and customer satisfaction: the difficulty in locating specific used cars across multiple operational zones.

Spirit Volvo maintains a large inventory of used vehicles, which can be located across various areas including the front showroom display, Yard 1, the Premium Spirit compound, or undergoing different stages of reconditioning (e.g., body repair, valeting, wheel alignment, or service). There is currently no central or real-time system that allows the sales team to know the exact location or status of each vehicle.

This lack of visibility causes delays when a customer walks in—especially those with appointments—expecting to see a specific vehicle. Sales representatives may take several minutes, or even longer, to find where the car is, or whether it's available. This reflects poorly on the dealership and can even result in lost sales. John Ryan confirmed this is a current and significant issue, especially as customer expectations for efficiency and professionalism have risen sharply in the automotive industry.

### 2. Problem Definition

-   **Customer Engagement Pain-Point:** Spirit Volvo lacks a real-time system to track the location and availability of used cars across its premises (e.g., showroom, Yard 1, Premium Spirit, service, valeting, repair). This leads to long delays when trying to present vehicles to potential buyers, causing frustration and potential loss of sales.
-   **Impact:** On busy days or during scheduled appointments, sales representatives may spend 10–20 minutes locating a single car, affecting workflow and customer experience. The resulting delay reduces conversion rates and increases walk-outs. Internally, this leads to inefficiencies and communication breakdowns across departments.
-   **Assumptions and Constraints:**
    -   The solution should require minimal manual data entry.
    -   It must work on desktop/tablet devices available in the showroom.
    -   Internet access is available, but heavy backend systems are not feasible.
    -   The solution must be a lightweight, single-page application that is easy to update and does not require extensive training.

---

## ✅ SECTION B – Prototype

### 3. Prototype Build

The prototype is a single-page web application that satisfies the stakeholder's requirements. The live application is contained entirely within the `index.html` file in this repository.

-   **Single-Page Application:** The solution is built using a single HTML file which contains all embedded CSS and JavaScript.
-   **Data Persistence with localStorage:** The app uses `localStorage` to store and retrieve all car data, simulating a persistent database and ensuring data is not lost on page refresh.
-   **Responsive UI/UX Design:** The interface is clean and designed to be usable on both desktop and tablet screens, which are common in a showroom environment.
-   **Version Control and Deployment:** This project uses GitHub for version control. The final application will be deployed using GitHub Pages.

---

## ✅ SECTION C – Documentation & Reflection

### 4. Project Documentation

#### (a) User requirements

-   **Business Challenge:** The core business challenge is the inefficiency and poor customer experience caused by the inability to quickly locate used vehicles within Spirit Volvo's multi-location operation. This operational friction leads to wasted staff time, frustrated customers, and lost sales opportunities in a competitive market.
-   **Specific User Requirements:**
    1.  A centralized view of all used cars, categorized as "Available" or "Not Available".
    2.  Real-time location tracking for "Available" cars (e.g., Showroom, Yard 1).
    3.  Real-time status tracking for "Not Available" cars (e.g., In Service, In Valeting).
    4.  Role-based access for different staff members (Sales, Department Heads, Admin).
    5.  The ability for department heads to update the status of cars under their care.
    6.  An export function for management to generate reports.
-   **Interview Summary:** The summary of the interview with the stakeholder is included in Section A above.

#### (b) Solution

Our solution is a single-page web application called the "Used Car Status Dashboard." It serves as a centralized, real-time hub for all information regarding the location and status of Spirit Volvo's used car inventory. The dashboard provides role-based views, allowing sales executives to quickly find cars for customers, while enabling department heads (from Service, Valeting, etc.) to log in and update the status of vehicles in their care. All data is stored locally in the browser, making the application fast and self-contained.

This prototype directly addresses the user requirements by replacing a manual, word-of-mouth process with a clear, digital system. It reduces customer wait times, empowers the sales team with accurate information, improves inter-departmental coordination, and provides management with oversight through an exportable reporting feature. The tool is designed to be intuitive and requires no special training, fitting seamlessly into the existing workflow.

#### (c) Screenshots

*(This section will be filled with screenshots of the final working application, including the login screen, main dashboard, and the modal for updating a car's status.)*

#### (d) Public link

*(This section will contain the public GitHub Pages link for the deployed application, e.g., https://[username].github.io/[repository-name]/)* 