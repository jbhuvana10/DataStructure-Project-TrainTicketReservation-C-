# TRAIN TICKET RESERVATION SYSTEM

### Data Structures Project Report

---

## 1. Introduction

The Train Ticket Reservation System is a simulation of railway ticket booking.
It demonstrates how passengers are allocated seats and managed using data structures.

The system supports booking, cancellation, and waiting list management.

---

## 2. Objective

* To simulate real-world ticket reservation
* To understand queue and list management
* To implement dynamic data handling
* To apply data structures in practical scenarios

---

## 3. System Description

The system is designed as a command-line application.
It allows users to book tickets, cancel tickets, and view passenger details.

When seats are available, tickets are confirmed.
If seats are full, passengers are added to a waiting list.

---

## 4. Data Structures Used

### 📦 Vector

* Stores confirmed passengers
* Allows dynamic resizing

### 🔁 Queue

* Maintains waiting list (FIFO order)
* First waiting passenger gets confirmed when a seat is free

---

## 5. Functional Modules

### 5.1 Ticket Booking

* Accepts passenger name and age
* Assigns unique ID
* Confirms ticket if seats available
* Otherwise adds to waiting list

---

### 5.2 Ticket Cancellation

* Removes passenger from confirmed list
* Moves first waiting passenger to confirmed

---

### 5.3 View Confirmed Tickets

* Displays all confirmed passengers

---

### 5.4 View Waiting List

* Displays all passengers in waiting queue

---

## 6. Algorithm (Working Principle)

1. Initialize system with limited seats
2. Accept user input
3. If booking:

   * Check seat availability
   * Confirm or add to waiting list
4. If cancellation:

   * Remove passenger
   * Promote waiting passenger
5. Display data when requested
6. Repeat until exit

---

## 7. Advantages

* Simple implementation
* Efficient seat management
* Demonstrates queue usage
* Real-world application

---

## 8. Limitations

* Limited seat count
* No database storage
* No seat number allocation
* No priority system

---

## 9. Future Enhancements

* Add seat numbering
* Implement RAC system
* Add priority (senior citizens)
* Store data in files
* GUI interface

---

## 10. Conclusion

The Train Ticket Reservation System effectively demonstrates how queues and lists can be used to manage real-world booking systems.
It provides a clear understanding of data structures in practical applications.

---

## 11. References

* Data Structures textbooks
* C++ documentation

---

## 👩‍💻 Author

BHUVANA J

1st YEAR VLSI

711525BEV009
