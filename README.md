🏟️ PlayArena: Turf Booking Website
PlayArena is a dynamic turf booking platform that allows users to discover and book sports venues online with ease. Integrated with Razorpay for secure transactions, the site offers seamless experiences for both users and administrators.

🧰 Tech Stack
* Frontend: HTML, CSS
* Backend: PHP
* Payment Gateway: Razorpay

👤 User Features
* 🔐 Login / Signup: Secure user authentication.
* 🏠 Home Page: Browse available turfs with details.
* 📅 Turf Booking: Book a turf by choosing date & time.
* 💳 Payment: Integrated Razorpay checkout for smooth payments.
* 🧾 Booking Invoice: View booking history in "My Bookings".
* ✍️ Feedback & Review: Leave reviews for played venues.
* 🖥️ User Dashboard:
  * Home
  * My Bookings
  * Contact
  * About
  * Feedback & Reviews
  * Logout

🛠️ Admin Features
* 🔐 Admin Login: Secure access to the admin panel.
* 📋 Manage Bookings: View and manage all bookings.
* 💰 Payment Overview: Monitor Razorpay transactions.
* 🏟️ Turf Management: Add or view turf listings.
* 🗑️ Feedback Moderation: Remove inappropriate reviews.
* 🔓 Logout

📁 Project Structure
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


