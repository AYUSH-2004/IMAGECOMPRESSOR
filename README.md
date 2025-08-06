# PixelTools: A Client-Side Image Compressor and Converter
**PixelTool** is a powerful and privacy-focused web-based tool for compressing images and converting them into different formats. Built with modern web technologies, it provides a seamless user experience for instantly reducing image file sizes, converting PDF to image or vice versa directly in the browser. This project was developed as part of the B.Tech Computer Science and Engineering curriculum, demonstrating proficiency in front-end development and an understanding of client-side processing.

## 🚀 Live Demo
You can see a live version of the project here: https://pixel-tool.netlify.app/

## ✨Key Features
**Client-Side Compression**: All image processing happens directly in the user's browser. No files are ever uploaded to a server, ensuring 100% privacy and security.

**Client-Side Conversion**: All image or PDF  conversion happens directly in the user's browser. No files are ever uploaded to a server, ensuring 100% privacy and security.

**Batch Processing**: Users can upload and compress multiple images simultaneously, streamlining the workflow.

**Download All**: Compressed images can be downloaded individually or all at once in a single .zip file.

**Real-time Feedback**: The interface provides real-time progress indicators and displays the original size, compressed size, and the percentage of space saved for each image.

**Responsive Design**: A clean, modern, and fully responsive user interface built with Tailwind CSS, ensuring a great experience on both desktop and mobile devices.

**Drag & Drop**: An intuitive drag-and-drop area for easily adding files.

**Wide Format Support**: Compresses all major image formats, including JPEG, PNG, and WebP.

## 🛠️ Technologies Used
**HTML5**: For the structure and content of the web application.

**Tailwind CSS**: A utility-first CSS framework for creating the modern and responsive user interface.

**JavaScript (ES6+)**: For all the application logic, DOM manipulation, and handling user interactions.

**browser-image-compression.js**: A lightweight and efficient JavaScript library for handling the core image compression logic in the browser.

**JSZip.js**: A library for creating, reading, and editing .zip files, used for the "Download All" functionality.

**particles.js**: A library for creating the animated particle background, enhancing the visual appeal of the application.

## ⚙️ How to Use
Open the Application: Simply open the index.html file in any modern web browser.

**Upload Images:**

Drag and drop your image files onto the designated upload area.

Alternatively, click the upload area to open the file selector and choose your images.

Compression: The tool will automatically start compressing the images. You can monitor the progress for each file.
Similarly, it works for conversion.

**Download:**

Once an image is compressed or converted, a "Download" button will appear next to it. Click it to save the individual file.

To download all compressed images or converted PDF or images  at once, click the "Download All" button, which will save them in a single .zip archive.

Start Over: Click the "Clear" button to remove all files and start a new session.

🛡️ Security
The primary security feature of PixelShrink is its client-side architecture. Since no data is ever transmitted to a server, users can be confident that their images remain private and secure on their own devices. This approach eliminates the risks associated with data breaches and unauthorized access on servers.
