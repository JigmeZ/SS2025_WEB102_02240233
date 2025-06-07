# File Upload Server

This project is a backend file upload server built with **Node.js**, **Express**, and **Multer**. It is designed to handle file uploads from a frontend (such as React or Next.js), store files securely, and provide robust validation and error handling.

## Features

- Accepts file uploads via HTTP POST requests
- Supports JPEG, PNG, and PDF file types
- Limits file size to 5MB
- Stores uploaded files in an `uploads` directory with unique filenames
- Serves uploaded files statically
- Provides clear error messages for invalid file types or oversized files
- CORS enabled for frontend-backend integration
- Includes logging with Morgan

## Technologies Used

- Node.js
- Express
- Multer
- CORS
- Morgan

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm

### Installation

1. Clone the repository or copy the project files.
2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file if you want to specify a custom port or frontend URL:

   ```
   PORT=8000
   FRONTEND_URL=http://localhost:3000
   ```

4. Start the server:

   ```bash
   npm start
   ```

   The server will run on `http://localhost:8000` by default.

## API Usage

### Upload a File

- **Endpoint:** `POST /api/upload`
- **Form Field:** `file` (multipart/form-data)
- **Response:** JSON with file details or error message

### Access Uploaded Files

- Uploaded files are available at `/uploads/<filename>`

## Example Frontend Integration

- Use Axios or Fetch to send a `multipart/form-data` POST request to `/api/upload`.
- Ensure the frontend origin matches the allowed CORS origin.

## License

This project is for educational purposes.
