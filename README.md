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
![image alt](

### Test Cases Execution  
![image alt] (https://github.com/ShamiKaregaChris/Plsql-class-assignment/blob/main/Screenshot%202025-11-29%20214102.png?raw=true)

### Violation Audit Logs
![image alt](https://github.com/ShamiKaregaChris/Plsql-class-assignment/blob/main/Screenshot%202025-11-29%20214017.png?raw=true)
