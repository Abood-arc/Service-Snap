# Service Snap

Service Snap is a full-stack web application designed to connect users with home service providers (like electricians, plumbers, AC repair, and more). The platform streamlines booking, order management, and admin oversight, making it easy for users to request services and for admins/workers to manage them.

## Key Features

- **User Authentication:** Secure sign-up, login, and password management (including Google/Facebook OAuth).
- **Service Booking:** Users can browse and book various home services.
- **Order Management:** Track order status, approvals, and history.
- **Admin Dashboard:** Admins can approve/reject orders, manage users, and oversee platform activity.
- **Worker Module:** Workers can view and manage assigned jobs.
- **Comments & Reviews:** Users can leave feedback and interact via comments.
- **Notifications & Email:** Email notifications for important actions (e.g., order status, password reset).

## Tech Stack

- **Frontend:** React, Redux, Tailwind CSS, Material UI, Ant Design, Axios, Firebase (for some features).
- **Backend:** Node.js, Express, MongoDB (Mongoose), Passport (OAuth), JWT, Nodemailer, Multer (file uploads).
- **APIs:** RESTful endpoints for all major actions, with secure data handling.

## Folder Structure

- **frontend/**: React app with all UI components, pages, and assets.
- **backend/**: Express server, API routes, controllers, models, and database logic.
- **uploads/**: Stores user-uploaded files (e.g., avatars).

## How It Works

1. **Users** sign up or log in, browse available services, and place orders.
2. **Admins** review and approve/reject orders, manage users, and monitor activity.
3. **Workers** access their assigned jobs and update order statuses.
4. **All parties** receive notifications and can interact through comments and reviews.
