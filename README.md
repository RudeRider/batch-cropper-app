🎬 Digital Asset Tools (Single-File Web App)
A lightweight, multi-purpose tool suite built in a single HTML file using Tailwind CSS, Cropper.js, JSZip, and Prism.js. It is designed for quick, client-side manipulation of images, videos, and structured text data without any server dependencies.

✨ Features
This application combines three powerful, self-contained utilities accessible via the main navigation bar:

1. Batch Cropper
An efficient tool for handling multiple image cropping tasks simultaneously.

Global Controls: Set a default aspect ratio (e.g., 9:16, 1:1) and output resolution (e.g., 1080x1920) that applies to all images.

Local Overrides: Each image card allows you to override the global aspect ratio and choose whether to fill empty space outside the crop area with a solid color.

Transformations: Includes individual controls for rotation and flipping.

Batch Export: Download all processed images as a single ZIP file with customizable JPEG quality or PNG format.

2. 🎥 Video Frame Capture
Extract high-quality frames from video files with precise control.

Video Playback: Upload and play local video files directly in the browser.

Single Frame Capture: Capture the current frame being displayed (down to millisecond precision).

Batch Frame Capture: Automatically capture a specified number of frames at a defined time interval.

Export: Download captured frames instantly as a batch ZIP file.

3. 📝 Text Editor / Scratchpad
A dual-layer text editor designed for writing notes and managing structured data.

Live JSON Highlighting: When you type or paste valid JSON (even with C-style comments), the editor automatically shifts into a transparent, live-highlighting mode for improved readability.

Metrics: Displays live word count and character count.

Download: Export content as a .txt file using a customizable filename.

🚀 Usage
Since this is a single HTML file, no server setup or installation is required.

Download: Save the entire index.html file to your local computer.

Open: Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, etc.).

Switch Tools: Use the menu buttons in the header to navigate between the Batch Cropper, Video Frame Capture, and Text Editor.

Note: All file processing (cropping, frame extraction, zipping) is done locally in your browser. Files are never uploaded anywhere.