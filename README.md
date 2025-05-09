# SeHealthy - Application

SeHealthy is a mobile health application designed to provide **easy access to health check-ups**, **disease screenings**, **medical history management**, and **health education**. The app aims to improve the health awareness of its users by offering an intuitive and interactive interface. It also allows users to track their health journey and maintain a digital record of their medical check-ups.

## Features

### 1. **User Role Selection**
- Choose between **Masyarakat (General User)** or **Admin (Healthcare Facility)**.

### 2. **Registration & Check-Up Scheduling**
- **Masyarakat** can register for **free health check-ups** and select their nearest **health facility** and appointment date.
  
### 3. **TBC Screening**
- Users can perform a **TBC (Tuberculosis) screening** through a simple questionnaire to assess their risk.
- Based on results, the app provides **recommendations** for further check-up or treatment.

### 4. **Medical History**
- Keep track of your **health records**, including check-up results like **blood pressure**, **glucose levels**, **cholesterol**, etc.
  
### 5. **Health Education & Campaigns**
- Access **articles** and **videos** related to health prevention, healthy lifestyle tips, and disease awareness.

### 6. **Appointment Management (for Admin)**
- **Admin** can manage **appointments**, confirm or reject scheduled check-ups, and add/edit health education content.

## Technologies Used

### Frontend (Mobile App - Flutter)
- **Programming Language**: Dart
- **Framework**: Flutter
  - Flutter is chosen for building a **high-performance**, **cross-platform mobile app** with a consistent user interface.

### Backend (Firebase or Node.js)
- **Firebase Firestore**: Real-time **NoSQL database** for storing user data and medical records.
- **Firebase Authentication**: For secure user login (email, password, Google sign-in).
- **Firebase Cloud Functions**: Used for backend logic such as generating screening results and sending notifications.

### API Integrations
- **Google Maps API**: For displaying nearby **health facilities** and managing check-up appointments.
- **AI Screening API**: For analyzing TBC screening results and offering recommendations based on symptoms.
- **Firebase Cloud Messaging**: For **push notifications** to remind users about their appointments or health check-ups.

## How to Run the Project Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/SeHealthy-Application.git
