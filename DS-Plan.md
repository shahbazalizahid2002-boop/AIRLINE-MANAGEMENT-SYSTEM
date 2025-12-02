# Data Structure Planning Table - Airline Management System

| Operation | Data Structure Used | Reason for Choosing DS |
|-----------|---------------------|------------------------|
| Add/Store Flights | Singly Linked List (Sorted by flight number) | Maintains sorted order while allowing dynamic insertion without shifting elements |
| Register Clients | Singly Linked List (Sorted by name) | Efficient alphabetical ordering of client records with easy insertion |
| Add Employees | Singly Linked List (Sorted by name) | Simple management of employee database with sorted alphabetical access |
| Flight Validation | Linear Search in Linked List | For client registration verification (flight must exist before booking) |
| Display All Records | Linked List Traversal | Sequential access is perfect for displaying all items in order |
| Memory Cleanup | Linked List Deletion | Efficient deallocation of all dynamically allocated nodes |
| Sorted Insertion | Linked List with Sorted Insertion | Maintains alphabetical/numerical order during insertion |
