# Cloud9

**Cloud9** is a user-friendly cloud storage platform inspired by Google Drive, built with **Node.js** and backed by **Amazon S3**. It allows users to upload, manage, and preview files directly in the browser. With built-in file preview and search capabilities, Cloud9 also leverages machine learning to make document searching smarter and more intuitive.

## Features

Cloud9 provides seamless file management through a web interface. Users can upload, view, and organize their documents, images, and media files using a sleek and simple UI. Files are stored in Azure, ensuring scalability and reliability. A JavaScript-based S3 file viewer enables in-browser previews, while integrated machine learning powers intelligent document search, making it easy to find what you need quickly.

## Getting Started

To run the project locally, clone the repository and install the required dependencies with `npm install`. Create a `.env` file in the root directory with your AWS credentials:

```
AWS_ACCESS_KEY_ID=your_key
AWS_SECRET_ACCESS_KEY=your_secret
S3_BUCKET_NAME=your_bucket
```

Start the server with `npm start`, then open your browser to begin uploading and managing your cloud files.

## Tech Stack

Cloud9 is built with Node.js and JavaScript. It uses AWS S3 for backend storage and applies machine learning techniques for enhanced document search. The interface provides a minimal, clean user experience similar to cloud storage services like Google Drive.



## Contact

@studbaneso1322