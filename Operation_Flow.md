# Operation Flow Explanation

## 1. Adding a Flight
**What it does:** Adds new flight to the system

**Data Structure:** Linked List (Sorted)

**Why suitable:** Keeps flights in order by flight number

**User interaction:**
- User selects 'a' from menu
- Enters flight details
- System adds it in correct sorted position

## 2. Registering a Client  
**What it does:** Books a client on a flight

**Data Structure:** Two Linked Lists

**Why suitable:** One list for flights, one for clients

**User interaction:**
- User selects 'r' from menu
- Enters client name and flight number
- System checks if flight exists
- If yes, adds client to client list

## 3. Displaying Records
**What it does:** Shows all flights, clients, or employees

**Data Structure:** Linked List Traversal

**Why suitable:** Easy to go through each item one by one

**User interaction:**
- User selects 'f', 'c', or 'p'
- System shows all items in order
- Shows message if list is empty
