# Student Hostel Booking Mobile App Task Flows

## 1. Introduction

This document defines three major task flows for the Student Hostel Booking Mobile Application. The flows represent common tasks that a university student would perform when searching for accommodation, booking a room, and checking an existing booking.

The three flows are designed to support the application's main mobile interaction scenarios required by the project.

---

## 2. Task Flow 1 — Find a Hostel

### Goal

Allow a student to find a suitable hostel and view its details.

### Flow

```text
Home
  ↓
Search Hostels
  ↓
Enter Search Criteria
  ↓
Apply Filters
  ↓
View Hostel List
  ↓
Select Hostel
  ↓
View Hostel Details
```

### Description

1. The student starts from the Home screen.
2. The student opens the hostel search function.
3. The student enters relevant search criteria.
4. The student applies available filters.
5. The application displays matching hostel options.
6. The student selects a hostel.
7. The application displays the selected hostel's details.

### Expected Outcome

The student successfully finds a hostel and can view its relevant information, including available rooms, prices, photographs, location, and facilities.

---

## 3. Task Flow 2 — Book a Room

### Goal

Allow a student to select and confirm a suitable hostel room.

### Flow

```text
Hostel Details
  ↓
View Available Rooms
  ↓
Compare Rooms
  ↓
Select Preferred Room
  ↓
Review Booking Details
  ↓
Confirm Booking
  ↓
Payment
  ↓
Booking Confirmation
```

### Description

1. The student starts from the Hostel Details screen.
2. The student views available room types and prices.
3. The student compares available room options.
4. The student selects a preferred room.
5. The student reviews the booking details.
6. The student confirms the booking.
7. The student proceeds through the payment step represented by the prototype.
8. The application displays booking confirmation.

### Expected Outcome

The student successfully selects a room, confirms the booking, and receives clear confirmation of the booking.

---

## 4. Task Flow 3 — Check Booking Status

### Goal

Allow a student to check the current status of an existing hostel booking and its payment status.

### Flow

```text
Home
  ↓
Bookings
  ↓
Select Booking
  ↓
View Booking Status
  ↓
View Payment Status
```

### Description

1. The student starts from the Home screen.
2. The student opens Bookings.
3. The student selects the relevant booking.
4. The application displays the booking status.
5. The student views the associated payment status.

### Expected Outcome

The student can clearly determine the current status of their hostel booking and payment.

---

## 5. Task Flow Summary

| Flow | Main Task | Starting Point | End Point |
|---|---|---|---|
| Flow 1 | Find a hostel | Home | Hostel Details |
| Flow 2 | Book a room | Hostel Details | Booking Confirmation |
| Flow 3 | Check booking status | Home | Booking/Payment Status |

## 6. Relationship to Main Application Functions

| Task Flow | Main Functions Used |
|---|---|
| Find a hostel | Search, filtering, hostel listing, hostel details |
| Book a room | Room availability, room comparison, room selection, booking confirmation, payment |
| Check booking status | Bookings, booking status, payment status |
