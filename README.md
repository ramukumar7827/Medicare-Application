# Medicare - Healthcare Mobile App

Medicare is a full-stack healthcare mobile application built with **Flutter**, **Node.js**, and **MongoDB**. The app enables users to book appointments with doctors, make payments through **Razorpay**, and locate nearby medical professionals using the **Google Geocode Maps API**.

## Demo

Watch the video demonstration of the app below:

https://vimeo.com/1103574547?share=copy

> Replace the link above with your actual YouTube or Google Drive video link.

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
| ![](screenshots/home.png) | ![](screenshots/doctor.png) | ![](screenshots/appointment.png) |

| Payment Options | Payment Success |
|------------------|----------------|
| ![](screenshots/payment.png) | ![](screenshots/success.png) |

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

