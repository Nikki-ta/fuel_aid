# FuelAid 🚗⛽
**Delivering Fuel & Roadside Aid Anytime, Anywhere!**  

A real-time web application designed to assist users with emergency roadside services and fuel delivery. 


<a target="blank"><img align="center" src="https://github.com/Nikki-ta/fuel_aid/blob/main/img1.png" width="70%"></a>

## Table of Contents

- [Installation and setup](#installation-and-setup)
- [Features](#features)
- [Technologies used](#technologies-used)
- [npm packages used](#npm-packages-used)
- [Prerequisites](#prerequisites)
- [Useful Links](#useful-links)
- [Contact](#contact)

## Installation and Setup

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/fuel_aid.git
   cd fuel-aid

2. Install all the dependencies
   ```sh
   npm install
   ```
3. Create a file named ".env" and enter the following credentials:
   ```js
   MONGO_URI = yourmongouri;
   OPENCAGE_API_KEY = your_apikey;
   ```
4. Run the web application
   ```sh
   npm start
   ```
5. Open http://localhost:5000 in your browser.

## Features

### 👥 User Types

- **Customer**: Requests fuel or roadside assistance through an intuitive service request form. Customers can track service status in real-time, view receipts, and submit feedback.

- **Mechanic**: Receives and accepts nearby service requests (within 100 km). Mechanics can update service status, track customers, and view their service history.

- **Fuel Delivery Boy**: Assigned by the admin to deliver petrol or diesel to customers. They can view customer location, confirm delivery, and mark requests as completed.

- **Admin**: Oversees the platform, verifies new users, manages service requests, assigns fuel delivery personnel or mechanics, and ensures smooth operational flow.


### 🚗Customer Features

- Signup/login with driving license verification.
- Request services: Roadside, Maintenance, or Fuel.
- View status & track mechanic/fuel delivery in real-time.
- Receive service receipts.
- Submit feedback & rate services.

### 🧰 Mechanic Features

- Login with location tracking.
- View and accept nearby service requests (within 100 km).
- Dashboard auto-refresh every 20 minutes.
- Real-time customer tracking & service update.
- Submit post-service notes and view service history.

### ⛽ Fuel Delivery Boy Features

- Submit hiring form (includes experience & background).
- Assigned deliveries based on proximity.
- Track customer, provide fuel, mark completion.
- Follow receipt and feedback cycle.

### 🛠️ Admin Features

- Manage customer & fuel delivery boy onboarding.
- Assign services manually based on proximity.
- Monitor all service request statuses (pending/ongoing/completed).
- View feedback, ratings, and notes.
- Full platform moderation and quality assurance.


## Technologies used

- HTML
- CSS
- Bootstrap
- Javascript
- Node.js
- Express.js
- Mongodb
- ejs

## npm packages used

- express
- ejs
- express-ejs-layouts
- mongoose
- express-session
- bcryptjs
- passport
- passport-local
- connect-flash
- method-override
- dotenv
- geolib
- pdfkit
- socket.io

## APIs and Libraries

- **OpenCage Geocoding API**: Converts textual addresses to lat/long and vice versa.
- **Leaflet.js**: Displays live map view for customer-mechanic tracking.
- **Haversine-distance**: Calculates shortest distance between two coordinates for ETA accuracy.
- **Geolib**: Filters and ranks nearest service providers based on real-time geolocation.

## Prerequisites

For running the application:

- Node.js must be installed on the system.
- You should have a MongoDB database.
- You should have a code editor (preferred: VS Code)

## Useful Links

- [Node.js Download](https://nodejs.org/)
- [VS Code Download](https://code.visualstudio.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)
- [Leaflet.js Docs](https://leafletjs.com/)
- [Socket.io Docs](https://socket.io/docs/)
- [OpenCage API](https://opencagedata.com/)
- [GitHub Docs](https://docs.github.com/en/get-started/quickstart/hello-world)

## Contact

📧 For queries or contributions: [nikitabansal006@gmail.com](mailto:nikitabansal006@gmail.com)  
🔗 GitHub Repo: [https://github.com/Nikki-ta/fuel-aid](https://github.com/Nikki-ta/fuel-aid)
