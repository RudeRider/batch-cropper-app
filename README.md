🎬 Digital Asset Tools: Batch Cropper & Video Frame Capture
A robust, client-side web application combining two essential tools for preparing visual assets: a powerful Batch Cropper utilizing Cropper.js, and a Video Frame Capture utility for extracting high-quality still images from videos.

This application runs entirely in the browser and supports drag-and-drop, global settings, and batch downloads using JSZip.

✨ Features
1. Batch Cropper
Multi-Image Upload: Process multiple PNG or JPEG files simultaneously.

Global Aspect Ratio: Apply common ratios (9:16, 1:1, 16:9, custom) to all images instantly.

Per-Image Overrides: Customize ratio, output resolution, and fill color for individual files.

Resizing & Filling: Set fixed output resolutions and fill transparent or cropped areas with a solid color.

Transforms: Quick rotate and horizontal flip controls per image.

Batch Download: Export all cropped images as a single ZIP archive.

2. Video Frame Capture
Video Loading: Upload local video files (MP4, MOV, etc.) for playback.

Precise Capture: Capture a single frame directly from the current video position (paused or playing).

Interval Capture: Automatically extract a set number of frames at a defined time interval (in seconds).

Gallery Management: Preview, delete, and manage captured frames in a dedicated sidebar gallery.

Batch Download: Export all captured frames as high-quality PNG files in a single ZIP archive.

🛠️ How to Use
Since this is a single self-contained HTML file, no server configuration or build steps are required.

Open the file: Download and open index.html directly in any modern web browser.

Switch Tools: Use the main header buttons (Batch Cropper or Video Frame Capture) to switch between the two utilities.

🖼️ Tool 1: Batch Cropper Guide
This tool is designed for bulk resizing and cropping large numbers of images efficiently.

Cropping Workflow
Upload: Use the "Upload PNG or JPEG Files" input or drag and drop your files into the marked zone.

Global Settings (Right Sidebar):

Select a Global Aspect Ratio (e.g., 9:16 for stories). This is applied to all uploaded images by default.

Choose the Default Output Resolution (e.g., 1920x1080) or leave it on "Auto-size" to match the crop box dimensions.

Select the Output Format (PNG for transparency, JPEG for smaller files) and set the JPEG quality if applicable.

Local Adjustments (Main Gallery): For any image, use the controls within its card:

Change the Aspect Ratio or Resolution to override the global setting.

Toggle "Fill Empty Area" and select a color if the crop is smaller than the output size or involves rotation/scaling that leaves transparent space.

Use the Rotate and Flip buttons to quickly adjust the image orientation before cropping.

Final Download: Click the Download All Cropped Images (ZIP) button to process and compress all images using their current settings.

🎥 Tool 2: Video Frame Capture Guide
This tool allows you to pull high-resolution still images from uploaded video content.

Capture Workflow
Upload: Click "Upload Video" and select your local video file (the video should load and appear in the viewer).

Seek: Play the video or manually drag the scrubber to the exact moment you wish to capture.

Single Frame Capture: Click Capture Frame to extract a single PNG image from the video's current position.

Multiple Frame Capture (Time-based):

Set the frame count (e.g., 10) and the sec interval (e.g., 0.5s).

The capture will begin from the current video time, moving forward by the set interval until the required number of frames are captured or the video ends.

Manage: Captured frames appear in the right-hand gallery. You can remove individual frames.

Final Download: Click Download All Frames (ZIP) to save all captured images to your computer.

📦 Dependencies
The application relies on the following external libraries, loaded via CDN:

Tailwind CSS: For all styling and responsive layout.

Cropper.js: For interactive image cropping and transformation.

JSZip: For creating the ZIP archives for batch downloads.

FileSaver.js: For triggering cross-browser file save/download dialogues.