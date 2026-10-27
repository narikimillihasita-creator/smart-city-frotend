# smart-city-frotend
Official Streamlit frontend for the Smart City Traffic &amp; Parking Management System, featuring integrated user authentication, vehicle fleet management, parking reservations, and admin enforcement portals
# Smart City Traffic & Parking System - Frontend

A production-ready Streamlit frontend built to interface with the Smart City Traffic & Parking FastAPI backend. This application provides dual-portal access for standard users and administrative operators, covering real-time state management, secure session persistence, and full CRUD operations across all system modules.

## ✨ Key Features

### 👤 User Portal
* **Authentication & State Management:** Secure login/signup flows leveraging Streamlit's `st.session_state` to manage user sessions and data masking without repetitive credential prompts.
* **Account & Fleet Management:** Manage personal contact details, account deletion cascades, and vehicle registrations.
* **Parking & Reservations:** Browse available parking zones sorted by rate, book slots with real-time cost calculation, extend/cancel bookings, and track historical spending.
* **Ticketing & Appeals:** View pending traffic violations, settle fines, and file/track dispute appeals.

### 🛡️ Admin Portal
* **System Overview:** Real-time metrics tracking total system capacity, free/occupied slots, zone revenues, and registered user bases.
* **Infrastructure Management:** Provision and manage parking zones, individual slots, sensors, and traffic monitoring cameras.
* **Enforcement & Oversight:** Filter vehicles by registration status, inspect active bookings, log traffic violations, and issue tickets.
* **Dispute Resolution:** Review pending user appeals and render decisions (Accept/Reject/Pending) with automated ticket nullification.

## 🚀 Tech Stack
* **Python**
* **Streamlit** (Frontend UI)
* **Requests** (REST API Communication with FastAPI backend)
