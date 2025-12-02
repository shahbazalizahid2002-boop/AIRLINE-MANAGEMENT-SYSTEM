# Operation Flow Explanation - Airline Management System

## Operation 1: Add Flight with Sorted Insertion
**What the operation does:**
Adds a new flight to the system while maintaining flights in ascending order by flight number.

**Data Structure that supports it:**
Singly Linked List with sorted insertion

**Why the Data Structure is suitable:**
- Dynamic memory allocation for flights
- Efficient insertion without shifting elements
- Maintains sorted order automatically
- Easy traversal for display

**How the user interacts with it:**
1. User presses 'a' from main menu
2. Enters: Flight number, destination, aircraft type, departure time, duration
3. System inserts flight in correct sorted position
4. Shows confirmation message

---

## Operation 2: Register Client with Flight Validation
**What the operation does:**
Registers a client for a flight after validating the flight exists.

**Data Structure that supports it:**
Two Singly Linked Lists (Flights list + Clients list)

**Why the Data Structure is suitable:**
- Separate lists for different entities
- Linear search in flight list for validation
- Sorted insertion in client list by name
- Prevents booking on non-existent flights

**How the user interacts with it:**
1. User presses 'r' from menu
2. Enters: Client name, flight number, ticket class
3. System searches flight list
4. If flight found, adds client to client list
5. Shows success or error message

---

## Operation 3: Display All Records
**What the operation does:**
Shows all flights, clients, or employees in formatted output.

**Data Structure that supports it:**
Linked List Traversal

**Why the Data Structure is suitable:**
- Sequential access from head to tail
- Simple implementation with while loops
- Real-time data display
- No additional memory needed

**How the user interacts with it:**
1. User presses:
   - 'f' for flights
   - 'c' for clients  
   - 'p' for employees
2. System traverses linked list
3. Displays all records in table format
4. Shows "No records" if list is empty
