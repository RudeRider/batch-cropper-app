🎬 Digital Asset Tools (Batch Cropper & Video Frame Capture)
This single-page application provides a suite of tools for processing and manipulating common digital assets (images and videos) directly in the browser.

✂️ Batch Cropper (Image Manipulation)
The Batch Cropper allows users to upload multiple JPEG or PNG images and apply uniform or individual cropping, resizing, and rotation settings before downloading the results as a single ZIP file.

Key Features
Multi-File Upload: Drag-and-drop support or standard file input for batch processing multiple images.

Global Settings: Quickly set a default Aspect Ratio (e.g., 9:16, 1:1, Free) and Output Resolution (e.g., 1080x1920, 4K) for all loaded images.

Per-Image Overrides: Each image card allows for local overriding of the global ratio and resolution settings.

Interactive Cropping: Utilizes Cropper.js for a fluid, interactive cropping experience on each image.

Image Transformations: Includes controls for Rotation and Horizontal Flip.

Background Fill: Option to specify a solid Fill Color (default: white) for areas outside the crop box when using a custom or non-matching ratio.

Batch Download: Compresses all processed images into a single .zip file for efficient downloading.

Output Control
Resolution Scaling: Images can be scaled up or down to a target resolution (e.g., forcing a 1920×1080 output). If only one dimension is specified, the output is scaled proportionally.

Format & Quality: Choose between PNG (for transparency and maximum quality) and JPEG (for smaller file size). JPEG output includes an adjustable quality slider.

🎥 Video Frame Capture
This tool allows users to extract high-quality still frames from video files loaded locally into the browser.

Key Features
Video Upload: Load video files (MP4, MOV, WebM, etc.) directly from your local system.

Manual Capture: Use the "Capture Frame" button to extract the exact frame currently displayed in the video player.

Batch Capture: Define an Interval (in seconds) and the total Number of Frames to automatically capture a sequence of stills, useful for creating spritesheets or capturing motion.

Frames Gallery: Displays all captured frames with the corresponding timestamp used for capture.

Individual & Batch Management: Delete individual frames or clear the entire gallery.

ZIP Download: Download all captured frames as high-quality PNG files compressed into a single .zip archive.