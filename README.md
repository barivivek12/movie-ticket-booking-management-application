🎬 Movie Ticket Booking Management Application
📌 Project Overview

The Movie Ticket Booking Management Application is designed for CineWave Entertainment to manage movie ticket bookings across multiple theatres and locations.

The application manages the complete booking lifecycle, including submitting a ticket request, checking seat availability, calculating the booking cost, confirming the booking, allocating seats, generating a ticket ID, routing requests based on show type, and sending booking confirmation notifications.

🚀 Features
🎟️ Submit movie ticket booking requests
🎬 Capture movie and show details
🪑 Check seat availability
💰 Calculate total booking cost
✅ Confirm or cancel booking requests
👀 Review booking details before confirmation
🪑 Allocate seat numbers
🎫 Generate Ticket ID
📊 Maintain booking status
🔀 Route bookings based on show type
⏱️ Configure SLA for booking requests
📧 Send booking confirmation notifications
🔄 Application Workflow
Submit Booking
      ↓
Check Show Availability
      ↓
Calculate Booking Cost
      ↓
Review Booking Details
      ↓
Confirm Booking
      ↓
Booking Execution
      ↓
Allocate Seats
      ↓
Generate Ticket ID
      ↓
Route Based on Show Type
      ↓
Send Booking Confirmation
      ↓
Resolve Case
📋 User Stories
US-01: Submit Movie Ticket Request

Customers can submit a movie ticket request by providing:

Movie Name
Show Date
Show Time
Number of Tickets
US-02: Check Show Availability

The application checks whether sufficient seats are available before proceeding with the booking.

The system captures:

Seat Availability Status
Available Seats
US-03: Calculate Booking Cost

The total booking cost is calculated using:

Total Cost = Ticket Price × Number of Tickets

The calculated total cost is stored with the booking.

US-04: Confirm Booking Request

Customers can confirm or cancel their booking request.

The booking status can include:

Confirmed
Cancelled
Pending
US-05: Maintain Movie and Show Data
Movie Data
Movie Name
Genre
Show Data
Show Date
Show Time
Seat Capacity
Show Type
Ticket Price
US-06: Review Booking Details

Before confirmation, customers can review:

Movie Name
Show Timing
Number of Tickets
Total Cost
US-07: Process Ticket Booking

After confirmation, the application processes the booking by:

Allocating seats
Generating seat numbers
Generating a Ticket ID
Updating booking confirmation status
US-08: Notify Booking Confirmation

After successful booking completion, the system sends a confirmation notification containing:

Case ID
Movie Name
Show Date and Time
Number of Tickets
Seat Numbers
Total Cost
US-09: Define Booking SLA

The Movie Ticket Request case includes an SLA with:

Goal: 1 Day
Deadline: 2 Days
US-10: Route Booking Request by Show Type

Booking requests are automatically routed based on the show type.

Premium Show
     ↓
PremiumShowQueue

Standard Show
     ↓
StandardShowQueue
🏗️ Application Architecture
Case Type
Movie Ticket Request
Main Stages
Submit Booking
Availability
Approval
Booking Execution
Resolution
🛠️ Technologies Used
Pega Platform
Pega Infinity
Pega App Studio
Pega Blueprint
Pega Academy Exercise System
📊 Key Data Objects
Customer
Movie
Show
Booking
Seat Allocation
Booking Notification
📸 Application Screenshots
Pega Blueprint Application Design




Movie Ticket Request Workflow

Add your workflow screenshot here.
<img width="1917" height="907" alt="Screenshot 2026-08-28 150857" src="https://github.com/user-attachments/assets/0218e156-d942-4d87-b968-f40b3a1790ad" />


Data Objects

Add your Data Objects screenshot here.

<img width="1913" height="902" alt="Screenshot 2026-08-28 151013" src="https://github.com/user-attachments/assets/cfd74d7c-74bc-4ebc-b3bf-23a36c1a828d" />

Application Preview

Add your final working application screenshot here.
<img width="1572" height="827" alt="Screenshot 2026-08-28 151115" src="https://github.com/user-attachments/assets/40fcb104-3aa9-49a2-96b6-faa31185fc13" />
<img width="1605" height="876" alt="Screenshot 2026-08-28 151208" src="https://github.com/user-attachments/assets/43081d9c-8e7d-4b73-a147-7c8d485e923b" />


🎯 Project Objective

The objective of this project is to automate the movie ticket booking process and provide a structured workflow from booking request submission through ticket confirmation.

The application improves the management of booking requests by supporting availability validation, cost calculation, customer confirmation, seat allocation, ticket generation, routing, SLA tracking, and booking notifications.

👨‍💻 Author

Vivek Bari

📌 Note

This project was developed as part of the National Internship Program (NIP) / Pega Academy project requirements.

