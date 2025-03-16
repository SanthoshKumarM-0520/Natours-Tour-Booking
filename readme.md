# Natours Application
Natours is a full-stack tour booking web application designed to provide a seamless experience for users to explore and book nature tours. It follows the MVC (Model-View-Controller) architecture, ensuring clean code structure, maintainability, and scalability.

 ### Key Features
✅ User Authentication & Authorization – Secure login, signup, and role-based access (admin, users).

✅ Tour Management – Users can browse available tours with details like descriptions, difficulty levels, and locations.

✅ Review & Ratings – Users can leave reviews and ratings for tours they have attended.

✅ Geolocation & Maps – Integrated Mapbox API to display tour locations interactively.

✅ Performance Optimization – Efficient database queries, caching, and security best practices.

✅ Responsive Design – Fully optimized for both desktop and mobile users.

### Technologies Used
🟢 Backend:
- Node.js – JavaScript runtime for server-side development.
- Express.js – Web framework for handling routes and middleware.
- MongoDB – NoSQL database for storing user and tour data.
- Mongoose – ODM library for managing MongoDB schemas.

🔵 Frontend:
- Pug (Templating Engine) – Used for rendering dynamic HTML pages.
- CSS – Styling for UI responsiveness and user experience.

🟠 Other Integrations:
- JWT (JSON Web Tokens) – Secure authentication and session management.
- Mapbox API – Interactive map integration for visualizing tour locations.
- Express Rate Limiter & Helmet – Security enhancements for request rate limiting and HTTP headers protection

🔹 Project Architecture
-1️⃣ Model (M) – Defines the schema and data structure in MongoDB using Mongoose.
-2️⃣ View (V) – Uses Pug templates for rendering dynamic UI.
-3️⃣ Controller (C) – Handles business logic, authentication, and database interactions
