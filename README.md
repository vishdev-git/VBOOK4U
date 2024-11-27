# VBOOK4U - Property Booking Platform

## Overview
VBOOK4U is a **property rental platform** designed to handle three different roles: **User**, **Property Owner**, and **Admin**. The platform allows users to search and book properties, property owners to manage listings, and admins to oversee revenue reports and manage property owner requests.

## Technologies Used
- **Frontend**: JavaScript, EJS (Embedded JavaScript Templates)
- **Backend**: Node.js, Express.js
- **Payment Gateway**: Razorpay
- **Database**: MongoDB
- **File Uploads**: Multer
- **Image Storage**: AWS (Amazon Web Services)
- **Authentication**: Passport.js
- **Validation**: Express Validator
- **Reports & Data Visualization**: Chart.js

## Features

### Role-Specific Dashboards
- **User**:
  - Property filtering and booking features
  - Secure login and account management

- **Property Owner**:
  - Manage property listings: add, edit, unlist, and cancel bookings

- **Admin**:
  - Access revenue reports (daily, monthly, yearly)
  - Manage property owner requests

### Additional Features
- Integrated Razorpay for secure payment processing
- AWS for image storage and Multer for file handling
- Passport.js authentication
- Chart.js for revenue reporting
- Express Validator for secure data validation
- Dynamic views using EJS templating

## Prerequisites
- Node.js
- MongoDB
- Razorpay account
- AWS account

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/vbook4u.git
cd vbook4u
```

### 2. Configure Environment Variables
Create a `.env` file with the following credentials:
```
MONGODB_URI=<your_mongo_db_connection_string>
RAZORPAY_KEY=<your_razorpay_key>
RAZORPAY_SECRET=<your_razorpay_secret>
TWILIO_ACCOUNT_SID=<your_twilio_account_sid>
TWILIO_AUTH_TOKEN=<your_twilio_auth_token>
TWILIO_PHONE_NUMBER=+13142624830
TWILIO_PERSONAL_NUMBER =<your_phone>
GOOGLE_CLIENT_ID = <your_google_client_id>
GOOGLE_CLIENT_SECRET = <your_google_client_secret>
RAZORPAY_KEY_SECRET = <your_razorpay_secret>


```

### 3. Install Dependencies
```bash
npm install
```

### 4. Run the Application
```bash
npm start
```

## Default Admin Credentials
- **Email**: `viswa20.2001@gmail.com`
- **Password**: `Vish@1234`

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License.