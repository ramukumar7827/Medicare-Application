# Medicare - Healthcare Mobile App

Medicare is a full-stack healthcare mobile application built with **Flutter**, **Node.js**, and **MongoDB**. The app enables users to book appointments with doctors, make payments through **Razorpay**, and locate nearby medical professionals using the **Google Geocode Maps API**.

## Demo

Watch the video demonstration of the app below:

https://vimeo.com/1103574547?share=copy

## Features

- View and book appointments with nearby registered doctors
- Doctor profile pages with specialization, experience, availability, and contact information
- Appointment booking form with custom reason/message input
- Integrated Razorpay payment gateway supporting UPI, cards, netbanking, wallets, and EMI
- Location-based filtering using Google Geocode API
- Separate interfaces for patients and doctors

## Tech Stack

| Component   | Technology         |
|------------|--------------------|
| Frontend   | Flutter             |
| Backend    | Node.js, Express    |
| Database   | MongoDB             |
| Payments   | Razorpay SDK        |
| Maps API   | Google Geocode API  |

## Screenshots

| Home | Doctor Profile | Appointment Booking |
|------|----------------|---------------------|
| ![Home](https://github.com/user-attachments/assets/00446edd-a1c3-4d5d-b4b5-5f3bcde05248) | ![Doctor Profile](https://github.com/user-attachments/assets/1eafb8b5-cc61-44f1-8c9f-c4fcba7d1bc2) | ![Appointment Booking](https://github.com/user-attachments/assets/d611495d-2aec-449c-92b6-168b38d98374) |

| Payment Options | Payment Success |
|------------------|----------------|
| ![Payment Options](https://github.com/user-attachments/assets/5c6a3fc2-5c77-4f8b-9405-e5b7ab07c568) | ![Payment Success](https://github.com/user-attachments/assets/ed582ba4-d0ef-4bba-b52c-79700e691bea) |


## Getting Started

### Prerequisites

- Flutter SDK (3.x)
- Node.js and npm
- MongoDB (local or cloud)
- Razorpay account with API keys
- Google Maps API key

### Setup Instructions

**Frontend (Flutter)**

```bash
cd medicare-app
flutter pub get
flutter run

