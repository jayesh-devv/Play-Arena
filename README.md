# 🏟️ PlayArena: Turf Booking Website

**PlayArena** is a full-featured turf booking web application that enables users to discover sports venues, book turfs online, and make secure payments using Razorpay. It also provides an admin panel for managing bookings, payments, turf listings, and user feedback.

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS  
- **Backend**: PHP  
- **Payment Gateway**: Razorpay

---

## 👤 User Features

- 🔐 **Login / Signup**: Secure user authentication.
- 🏠 **Home Page**: Explore listed turfs with descriptions and details.
- 📅 **Turf Booking**: Select preferred turf, date, and time for booking.
- 💳 **Payment Integration**: Razorpay used for seamless and secure online payments.
- 🧾 **Booking Invoice**: Confirmed bookings available in *My Bookings* section.
- ✍️ **Feedback & Review**: Users can share reviews for booked venues.
- 🖥️ **User Dashboard**:
  - Home  
  - My Bookings  
  - Contact  
  - About  
  - Feedback & Reviews  
  - Logout

---

## 🛠️ Admin Features

- 🔐 **Admin Login**: Access admin panel using credentials.
- 📋 **Manage Bookings**: View and monitor all user bookings.
- 💰 **Payment Overview**: Track and manage Razorpay transactions.
- 🏟️ **Turf Management**: View existing turfs and add new venues.
- 🗑️ **Feedback Moderation**: Review and remove inappropriate or spam feedback.
- 🔓 **Logout**

---

## 📁 Project Structure

```bash
PlayArena/
├── index.html
├── login.php
├── signup.php
├── dashboard/
│   ├── user/
│   │   ├── home.php
│   │   ├── mybookings.php
│   │   ├── contact.php
│   │   ├── about.php
│   │   ├── feedback.php
│   │   └── logout.php
│   └── admin/
│       ├── bookings.php
│       ├── payments.php
│       ├── view_turfs.php
│       ├── add_turf.php
│       ├── feedbacks.php
│       └── logout.php
├── razorpay/
│   └── payment_integration.php
└── assets/
    ├── css/
    └── images/
