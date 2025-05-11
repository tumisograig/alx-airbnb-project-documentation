# Task 0: Documenting Project Features and Functionalities

## Objective

Create a detailed inventory of all backend features and functionalities the Airbnb Clone must support.

## Key Features & Functionalities

1. **User Authentication**

   * User registration (sign up)
   * Secure login (email + password)
   * Password hashing and reset flows
   * Role management (guest, host, admin)

2. **User Profile Management**

   * View and update personal details
   * Host profile settings (bank/account info)

3. **Property Management**

   * Hosts can create, edit, delete listings
   * Upload photos and set prices
   * View all properties by host

4. **Search & Filter**

   * Search by location, date, price range
   * Filter by amenities, ratings

5. **Booking System**

   * Guests can select dates and book a property
   * Prevent overlapping bookings
   * Booking status (pending, confirmed, canceled)

6. **Payment Processing**

   * Integrate with payment gateway (Stripe, PayPal)
   * Record transactions and statuses
   * Refund workflows for cancellations

7. **Reviews & Ratings**

   * Guests leave ratings (1–5) and comments
   * Hosts and users view past reviews

8. **Messaging System**

   * In-app messaging between users
   * Store conversation history

9. **Notifications & Alerts**

   * Email notifications for bookings, payments
   * In-app alerts for new messages or status changes

10. **Admin Dashboard (optional)**

    * Monitor users, properties, bookings
    * Flag or remove inappropriate content

---

## How to Create the Diagram in Draw\.io

1. **Open Draw\.io**

   * Navigate to [https://draw.io](https://draw.io).
   * Click **Create New Diagram**, choose **Blank Diagram**, then **Create**.

2. **Set Up Canvas**

   * Optional: Switch to **Landscape** in Page Settings for a wider view.

3. **List Features**

   * From the left panel, drag a **Text** shape onto the canvas.
   * Double-click, paste the feature titles and bullet points.

4. **Group by Category**

   * Use **Rectangle** shapes as containers to group related features (e.g., all user-related features in one box).

5. **Connect Relationships (optional)**

   * If desired, draw arrows between feature groups to indicate workflow (e.g., authentication → booking).

6. **Style & Arrange**

   * Align boxes neatly using the grid.
   * Adjust text size or color for readability.

7. **Export as PNG**

   * Go to **File → Export As → PNG**.
   * Ensure **Include a copy of my diagram** is checked, then **Export** and **Download**.

8. **Save to Repository**

   * Create the folder `features-and-functionalities/` in your repo.
   * Place the exported PNG and this README.md inside it.

