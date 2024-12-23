# Hotel SPA - React Application

## Overview

Hotel SPA is a responsive React-based Single Page Application (SPA) designed to display a list of hotels along with their detailed information. Users can browse a list of hotels and navigate to a detail page to view specific information about a selected hotel.

## Features

- **Hotel Listing**:
  - Displays a list of hotels with key details like name, location, and rating.
  - Images and descriptions are dynamically fetched and displayed.

- **Hotel Detail Page**:
  - Users can view all details of a selected hotel, including:
    - Hotel name
    - Location
    - Rating
    - Travel dates
    - Board basis
    - Rooms and room types
    - Hotel image

- **Navigation**:
  - Clicking a button on each hotel listing navigates to a detailed page.

- **Error Handling**:
  - Displays an error message if no valid hotel data is passed.

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js (v16 or later)
- Git

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Hotel-SPA.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Hotel-SPA
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open the application in your browser at:
   ```
   http://localhost:3000
   ```

### Backend Setup
The project includes a simple Express server to serve hotel data.

1. Navigate to the server directory:
   ```bash
   cd server
   ```

2. Install backend dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   node server.js
   ```

4. The backend will run at:
   ```
   http://localhost:5000/api/hotels
   ```

## Project Structure
```
HotelSPA/
├── public/           # Public files
├── src/              # React source files
│   ├── assets/       # CSS and static assets
│   ├── components/   # React components (HotelList, HotelDetail)
│   └── App.js        # Main React application
├── server/          # Backend Express server
│   └── server.js     # Server configuration
└── package.json    # Project dependencies and scripts
```

## API Endpoints

### `/api/hotels`
- **Method**: GET
- **Description**: Fetches a list of hotels.

### `/api/hotels/:id`
- **Method**: GET
- **Description**: Fetches detailed information about a specific hotel by ID.

## Technologies Used

- **Frontend**:
  - React
  - React Router DOM
  - CSS

- **Backend**:
  - Node.js
  - Express

## Screenshots

### Hotel List Page
![Hotel List Page](https://via.placeholder.com/800x400?text=Hotel+List+Page)

### Hotel Detail Page
![Hotel Detail Page](https://via.placeholder.com/800x400?text=Hotel+Detail+Page)

## Future Improvements

- Add search and filtering functionality for hotels.
- Implement user authentication.
- Enhance responsiveness for mobile devices.
- Add a booking feature.

## License
This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## Contact
For questions or suggestions, please contact:
- **Name**: Neeraja Beena Sasidharan
- **Email**: bsneeraja@gmail.com
- **GitHub**: [your-username](https://github.com/your-username)

---
Thank you for checking out the project!

