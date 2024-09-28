

# Employee Leave Management System

This is a simple **Java console application** that allows users to manage employee leave requests. Employees can create leave requests, and administrators can approve or reject those requests based on the employee's available leave balance.

## Features

- **Employee Registration**: Employees can input their names and leave balances.
- **Leave Request Creation**: Employees can request leave by specifying the start date, end date, and type of leave (e.g., Annual, Sick).
- **Leave Request Approval/Rejection**: Administrators can process leave requests, either approving or rejecting them. The system checks if the employee has enough leave balance to approve the request.
- **Leave Request Status**: The status of each leave request is displayed (Pending, Approved, Rejected).
- **View All Leave Requests**: Administrators can view a list of all leave requests, including employee details, leave type, start and end dates, and the request status.

## Usage

1. **Start the program**: Upon starting, you will be presented with a menu:
   ```
   === Employee Leave Management System ===
   1. Create Leave Request
   2. Process Leave Request
   3. View All Leave Requests
   4. Exit
   ```

2. **Create a Leave Request**: Choose option `1` to create a new leave request. You will be prompted to enter:
   - Your first name and last name
   - Your available leave balance
   - The start and end dates of the leave (in the format `YYYY-MM-DD`)
   - The type of leave (e.g., Annual, Sick)

3. **Process a Leave Request**: Choose option `2` to process (approve or reject) an existing leave request. You will be prompted to:
   - Enter the Request ID of the leave request you want to process.
   - Approve (`true`) or reject (`false`) the request. If rejected, you'll need to provide a reason for the rejection.

4. **View All Leave Requests**: Choose option `3` to view all current leave requests, including their status (Pending, Approved, or Rejected).

5. **Exit the program**: Choose option `4` to exit the system.

## Example

Here is an example of how to create a leave request:

1. Start the program and select `1` to create a new leave request.
2. Input employee details such as:
   ```
   Enter your first name: John
   Enter your last name: Doe
   Enter your leave balance (e.g., 15.5 days): 10
   Enter start date (YYYY-MM-DD): 2024-10-01
   Enter end date (YYYY-MM-DD): 2024-10-05
   Enter leave type (e.g., Annual, Sick): Annual
   ```
3. The leave request will be successfully created, and the status will be marked as "Pending".

