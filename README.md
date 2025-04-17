# EDUNET_
### Personal Fitness Tracker using Python 

A **Personal Fitness Tracker** is a tool that allows individuals to log and monitor their fitness activities. In Python, a simple console-based tracker can be implemented without using web technologies like Flask. Here is a brief explanation of the key components and implementation of such a tracker.

---

### Key Features:
1. **User Registration & Login**:
   - Allows users to create an account and securely log in.
   - Credentials are stored in memory and persisted in a file.

2. **Activity Logging**:
   - Users can log different types of activities (e.g., running, cycling).
   - The system tracks the **duration** of each activity and **calories burned** (using a basic calculation like 10 calories per minute).

3. **Stats Tracking**:
   - Users can view their total **duration** and **calories burned** for all activities.
   - Provides a summary of logged activities.

4. **File-based Data Persistence**:
   - Uses Python’s `pickle` module to save and load user data and activities from files (`users.pkl`, `activities.pkl`).

---

### Basic Code Structure:

1. **User Class**: 
   - Represents user details, including username and password.
   - Manages the user's activity logs.

2. **Tracker Class**: 
   - Responsible for logging activities, viewing past activities, and calculating stats.
   - Tracks the type, duration, and calories burned for each activity.

3. **Main Program (`app.py`)**:
   - Handles user interaction in the console.
   - Provides a menu to allow the user to register, log in, log activities, and view stats.

---


### Summary of Implementation:

- **Data Persistence**: Data is saved and loaded using `pickle`, allowing the application to retain user data and activity logs across sessions.
- **Activity Logging**: Users can log fitness activities, and the system computes calories based on the duration of the activity.
- **User Interaction**: A text-based menu allows the user to interact with the tracker, log activities, and check progress.

