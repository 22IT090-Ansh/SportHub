# TurfSpot

TurfSpot is a comprehensive turf booking application with three modules: Admin, Owner, and User. This app allows users to view and book turf grounds, owners to manage their turfs and bookings, and admins to oversee all activities within the platform.

## Features

### User Module

- **Browse Turfs**: Users can view various turfs, check their details, and select time slots for booking.
- **Slot Booking**: Purchase time slots using Razorpay. After booking, users receive a confirmation email with all the booking details, including price, turf name, start time, end time, and a QR code containing all these details.
- **Rate Turfs**: Users can provide ratings for the turfs they have booked.
- **Become Owner**: Users can apply to become turf owners by filling out a form. Admins will review the application and send an approval or rejection email accordingly.

### Owner Module

- **Turf Management**: Owners can add new turfs, manage their existing turfs, and view all related booking details.
- **Dashboard**: Owners have access to a dashboard where they can view transactions and booking statistics in a graphical format.
- **Review Management**: Owners can view and manage reviews left by users for their turfs.

### Admin Module

- **Owner Requests**: Admins can approve or reject requests from users who wish to become owners. If approved, the user will receive an email with a registration link to the owner section.
- **User and Owner Management**: Admins can view all users and owners registered on the platform.
- **Turf Management**: Admins can view all turfs listed by owners and manage them as necessary.
- **Transaction Overview**: Admins have access to all transactions on the platform and can view transaction data on a monthly basis in graph format.

---


### 🔐 Admin Credentials (For Demo)

- **Email**: `admin@gmail.com`  
- **Password**: `rijo.com`

> 🛠️ **Note**: Admin accounts are created directly in the database. The admin process involves adding an owner manually in the `owners` table and updating their `role` to `admin`.

---

## Technologies Used

- **Frontend**: React, Tailwind CSS, DaisyUI, Redux
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payments**: Razorpay
- **Image Hosting**: Cloudinary



