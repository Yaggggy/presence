# Presence

**Presence** is a geolocation-based attendance tracking web application designed to streamline and automate the process of recording attendance by leveraging users' geographic locations.

## Features

- **Geolocation-Based Tracking**: Accurately records attendance based on users' physical locations.
- **Secure and Private**: Ensures user data is protected and only accessible to authorized personnel.
- **Real-Time Monitoring**: Allows administrators to monitor attendance in real-time.
- **User-Friendly Interface**: Intuitive design for both administrators and users.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Geolocation Services**: Integrated with [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API) for accurate location tracking.


##Screenshots


![Screenshot 2024-12-06 005134](https://github.com/user-attachments/assets/c29c9660-21a2-4e4c-83e5-4dabe226e43a)


![Screenshot 2024-12-06 005154](https://github.com/user-attachments/assets/9627dbd4-29e6-418b-820e-3097d2b700e8)


## Installation

### Prerequisites

- Node.js v14 or higher
- MongoDB
- [Bun](https://bun.sh/) JavaScript runtime

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Yaggggy/presence.git
   cd presence
   ```

2. **Install dependencies**:

   ```bash
   bun install
   ```

3. **Set up environment variables**:

   - Rename `.env.sample` to `.env`:

     ```bash
     mv .env.sample .env
     ```

   - Update the `.env` file with your configuration details.

4. **Start the development server**:

   ```bash
   bun run dev
   ```

   The application will be accessible at `http://localhost:3000`.

## Usage

- **For Users**: Log in and allow location access when prompted. Your attendance will be recorded based on your current location.
- **For Administrators**: Access the admin panel to view and manage attendance records.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`feature/your-feature-name`).
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.


