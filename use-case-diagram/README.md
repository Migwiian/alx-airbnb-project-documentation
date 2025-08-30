# Airbnb Clone - Use Case Diagram Explanation

## 🧍 Actors

| Actor | Description |
| :--- | :--- |
| **Guest** | Users who search and book properties |
| **Host** | Users who list and manage properties |
| **Administrator** | System administrators who manage the platform |
| **Payment System** | External payment processing services |

## 🎯 Main Use Case Groups

### 1. User Management
- **Register Account** - Guest/Host registration process
- **Login/Logout** - User authentication and session management
- **Manage Profile** - Update personal information and preferences
- **Manage Security** - Two-factor authentication, password reset

### 2. Property Management
- **Create Property Listing** - Host creates new accommodation listing
- **Edit Property Details** - Modify existing property information
- **Manage Availability Calendar** - Set available booking dates
- **Upload Photos** - Add property images and media
- **Set Pricing Rules** - Configure seasonal pricing and discounts

### 3. Booking Management
- **Search Properties** - Find available accommodations
- **Filter & Sort Results** - Refine search results based on criteria
- **View Property Details** - Access complete listing information
- **Make Reservation** - Book a property for specific dates
- **Cancel Booking** - Cancel existing reservation
- **Modify Booking** - Change booking details or dates

### 4. Payment Management
- **Process Payment** - Handle transaction processing
- **Handle Refunds** - Process refund requests and reversals
- **Manage Payouts** - Transfer funds to hosts after stays
- **Generate Receipts** - Create payment documentation

### 5. Review System
- **Write Review** - Guest reviews property after stay
- **Respond to Review** - Host responds to guest reviews
- **Report Inappropriate Review** - Flag problematic content

### 6. Communication
- **Send Message** - Host-Guest direct communication
- **View Message History** - Access past conversations
- **Get Notifications** - Receive updates and alerts

### 7. Administration
- **Manage Users** - User account management and moderation
- **Moderate Content** - Review listings and user-generated content
- **View Analytics** - Platform performance metrics and reporting
- **Handle Disputes** - Resolve conflicts between users
- **Manage System Settings** - Platform configuration and maintenance

## 🔗 Key Relationships

- **«includes»** - Making a reservation includes payment processing
- **«extends»** - Canceling a booking may extend to refund processing
- **«inherits»** - Both Guest and Host inherit basic user functionalities

## 📊 Diagram Overview

This comprehensive use case diagram captures all essential interactions between users and the Airbnb clone system, providing a complete overview of the system's functionality from multiple user perspectives. The diagram illustrates how different actors interact with various system components, ensuring all user needs and system requirements are visually represented.
