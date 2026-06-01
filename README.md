# Data Compression & Decompression Portal

A user-friendly web application designed to reduce and restore file sizes through well-known **lossless compression** techniques such as **Huffman Coding** and **Run-Length Encoding (RLE)**.

## Core Functionality

### Compression and Decompression Modes

Users can seamlessly switch between file **compression** and **decompression** using an intuitive interface.

### Supported Algorithms

- **Huffman Coding**  
  A widely used lossless compression technique that assigns shorter binary codes to frequently occurring characters, making it highly effective for text data.

- **Run-Length Encoding (RLE)**  
  A simple compression method that minimizes storage by replacing consecutive repeated characters with a count and value representation.

### Compression Analytics

Upon processing a file, the application provides useful metrics including:

- Original file size
- Compressed file size
- Compression efficiency percentage
- Processing time measured on the server

### User-Friendly Interface

- Drag-and-drop file upload support
- Traditional file selection option
- Instant download of processed files
- Interactive information section describing the selected algorithm

###**Tech Stack**
**Frontend:** React.js, Vite, Tailwind CSS, axios
**Backend:** Python 3, Flask, Gunicorn
**Hosting:** Vercel,Render

##Deployment

Frontend is hosted at: https://data-compression-and-decompression-sandy.vercel.app
Backend is hosted at: https://data-compression-and-decompression-yjzr.onrender.com