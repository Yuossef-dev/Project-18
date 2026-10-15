# 🏨 Velora Hotel - Luxury Meets Comfort

A modern, responsive, and elegant website for **Velora Hotel**, built to provide a seamless booking request experience and showcase hotel rooms and services.

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Getting Started](#-getting-started)
- [Usage & Booking Flow](#-usage--booking-flow)
- [License](#-license)

---

## 🌟 Overview
Velora Hotel's website offers an inviting digital experience for prospective guests. Users can explore various luxury room options, learn about the hotel's amenities, and submit a demo booking request.

---

## ✨ Features

- **Responsive Landing Page (`index.html`)**:
  - **Hero Section**: Welcoming header with dynamic call-to-actions.
  - **Rooms & Suites Grid**: Clean card layout showcasing available room types.
  - **The Velora Experience**: Highlights core services and features.
  - **Call to Action**: Quick navigation to book a stay.

- **Booking Request Form (`Log_in.html`)**:
  - Dynamic room selection pre-filled based on landing page interactions.
  - Date validation for Check-in and Check-out.
  - Client-side form feedback and error handling.

- **Design & UX**:
  - Built with custom CSS utilizing modern grid and flexbox layouts.
  - Styled with typography powered by **Google Fonts (Roboto Slab)**.
  - Optimized for mobile, tablet, and desktop viewports.

---

## 📁 Project Structure

```text
.
├── index.html       # Main landing page
├── style.css        # Stylesheet for the main page
├── Log_in.html      # Booking request page
├── Log_in.css       # Stylesheet for the booking page
└── README.md        # Project documentation
```

---

## 🛠️ Technologies Used

- **HTML5**: Semantic layout and markup.
- **CSS3**: Custom variables, Flexbox, CSS Grid, and responsive media queries.
- **JavaScript (Vanilla)**: Date validations, URL parameters parsing, and dynamic UI messaging.
- **Google Fonts**: Roboto Slab typeface.

---

## 🚀 Getting Started

To view and run this project locally:

1. **Clone or Download** the repository files into a directory.
2. **Open `index.html`** in any web browser (Google Chrome, Firefox, Safari, Edge).

*No additional build tools or npm dependencies are required.*

---

## 📝 Usage & Booking Flow

1. **Browse Rooms**: Navigate to the "Rooms" section on `index.html`.
2. **Select Room**: Click on **"Choose room ↗"** on any room card.
3. **Automated Selection**: You will be redirected to `Log_in.html` with the selected room automatically chosen in the dropdown.
4. **Submit Request**: Fill in your travel details and dates to complete the demo booking request.

---

## 📌 Note
> **Demo Disclaimer**: This is a frontend student project. Form submissions are handled locally via JavaScript and do not connect to a live booking backend server.
