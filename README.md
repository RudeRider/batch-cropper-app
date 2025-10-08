🎬 Digital Asset Management Suite (Single File HTML)
This is a powerful, integrated web application built entirely within a single HTML file. It combines three essential tools for digital asset management: a Batch Image Cropper, a Video Frame Capture utility, and a Cloud-Synced Rich Text Editor using Firebase Firestore.

✨ Features
The application is split into three main tabs, accessible via the navigation bar:

1. Batch Cropper
Drag-and-Drop Support: Easily upload multiple PNG or JPEG files.

Global Aspect Ratio Control: Set a single, consistent aspect ratio (e.g., 16:9, 1:1, 9:16) for all images in the batch.

Customization: Per-image controls to override the global ratio, set custom fill colors for non-cropped areas, and define fixed output resolutions.

Transformations: Quick buttons for rotating and flipping images before cropping.

Batch Download: Compiles all processed, cropped images into a single .zip file for efficient downloading.

2. Video Frame Capture
Local Video Processing: Upload video files (MP4, MOV, etc.) directly in the browser.

Precise Frame Extraction: Capture individual frames at the video's current time.

Batch Frame Extraction: Automatically capture a defined number of frames at a specified time interval (in seconds).

Gallery Management: Preview, delete, and download captured frames.

Batch Download: Downloads all captured frames as high-quality PNGs in a .zip archive.

3. Cloud Editor (Minimal Word)
Real-time Cloud Sync: Uses Firebase Firestore to save your content in real-time, persisting it across sessions and devices.

Multi-Notebook System: Features two separate, dedicated storage documents (Notebook 1 and Scratchpad 2) for organizing different types of content.

Rich Text Formatting: Supports basic formatting like bold, italic, and headings (H3) using a simple toolbar.

Document Statistics: Displays live word and character counts.

Download: Exports the content as a fully styled .html file.

🛠️ Technical Stack
The "Digital Asset Management Suite" is designed as a single, portable file:

Component

Technology

Usage

Structure/UI

HTML5 / Vanilla JavaScript / Tailwind CSS (CDN)

Core layout, logic, and modern, responsive dark-mode styling.

Image Cropping

Cropper.js (CDN)

Provides the interactive cropping interface and canvas manipulation.

File Handling

JSZip (CDN) & FileSaver.js (CDN)

Handles client-side compression (.zip creation) and cross-browser file downloads.

Data Persistence

Firebase Firestore (CDN)

Stores rich text content for the Cloud Editor, ensuring data synchronization.

🚀 Setup and Running
Since this is a single file using CDNs, setup is minimal:

Save the file: Save the entire content as index.html.

Modern Browser: Open index.html in any modern web browser (Chrome, Firefox, Edge, Safari).

Cloud Editor Note: The Cloud Editor relies on environment variables (__app_id, __firebase_config, __initial_auth_token) provided by the host environment (like Google Canvas) for secure Firebase authentication and connectivity. If run locally outside of this environment, the Firebase features will not function, but the Cropper and Video tools will remain fully operational.

README.md