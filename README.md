# Plsql-class-assignment
 # 1. AUCA System Access Policy Implementation

## Project Overview
**Question:** Implement database triggers to enforce AUCA's system access policy restricting data access to Monday-Friday, 8:00 AM to 5:00 PM, while logging all violation attempts.

## Solution Approach
We implemented two primary database triggers:

### 1. Access Restriction Trigger
- Prevents INSERT, UPDATE, DELETE operations on Sabbath (Saturday/Sunday)
- Blocks access outside business hours (8:00 AM - 5:00 PM)
- Provides real-time enforcement with descriptive error messages

### 2. Violation Logging Trigger
- Records all unauthorized access attempts
- Captures user, timestamp, action type, and violation reason
- Maintains audit trail for compliance monitoring

## Technology Stack
- Oracle Database 23ai
- PL/SQL for trigger implementation
- SQL for testing and validation

## Key Features
✅ Real-time access control  
✅ Comprehensive audit logging  
✅ Sabbath protection (Saturday/Sunday)  
✅ Business hours enforcement  
✅ Violation tracking and reporting  


## Screenshots

### Trigger Implementation
![Trigger Creation](<img width="1205" height="630" alt="Screenshot 2025-11-29 213859" src="https://github.com/user-attachments/assets/4f77b428-abb3-405c-8145-00543a3ec808" />
)

### Test Cases Execution  
![Test Results](screenshots/test_cases.png)

### Violation Audit Logs
![Audit Trail](screenshots/violation_logs.png)
