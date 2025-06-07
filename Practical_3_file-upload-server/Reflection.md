# Reflection.md

## a) Documentation

In this practical, I built a backend file upload system using **Node.js**, **Express**, and **Multer**, designed to work with a React/Next.js frontend. Key concepts included:

- **Multipart Form Data**: Used Multer to handle file uploads and extract files from requests.
- **File Storage**: Configured Multer to save files with unique names in an `uploads` directory.
- **Validation & Limits**: Allowed only PDF files and set file size limits using Multer’s options.
- **Error Handling**: Added middleware to catch and respond to upload errors.
- **CORS**: Enabled cross-origin requests for frontend-backend communication.
- **Frontend Integration**: Used Axios for file uploads and displayed progress in real time.

## b) Reflection

This exercise gave me a clear understanding of secure file uploads in a full-stack setup. I learned how to configure Multer, validate file types and sizes, and manage errors both on the backend and frontend. Setting up CORS and tracking upload progress with Axios were also valuable skills.

### Challenges Faced

I initially struggled with Multer’s file filter, as it was rejecting all files due to case-sensitive MIME type checks. Changing the check to `.toLowerCase()` fixed this. I also had to handle large file uploads gracefully; adding Multer’s `limits` and a custom error handler solved server crashes and provided clear feedback to users.

---

Overall, this practical improved my confidence in handling file uploads and integrating backend and frontend logic for real-world applications.
