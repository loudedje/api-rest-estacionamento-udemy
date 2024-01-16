# Parking Management - Course Summary

## Description
This repository is the outcome of the Parking Management course offered by Udemy during my internship at Compass UOL. The project's aim is to develop a parking management system, providing a Rest API with authentication via Json Web Token (JWT). The application encompasses essential features, ranging from initial configuration to the management of clients and parking spaces.

## Key Features
- **General Settings:**
  - Configuration of the country's Timezone and Locale.
  - Implementation of audit trails for records.

- **User Features:**
  - Creation of users with unique email addresses.
  - Profiles for administrators or clients.
  - Retrieval of data by generated identifier.
  - Password change with authentication.

- **Authentication System:**
  - Implementation of security and authentication with JWT.

- **Client Registration:**
  - Client registration linked to the user.
  - Authentication restrictions for specific actions.
  - Retrieval of client data via token.

- **Parking Management:**
  - Actions restricted to administrators.
  - Each parking space with a unique code and status (free or occupied).
