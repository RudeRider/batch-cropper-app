🖼️ Batch Image Aspect Ratio Cropper
This is a powerful, client-side web application designed for fast, accurate, and high-volume image preparation. It allows users to upload multiple JPEG or PNG images, define a single aspect ratio, and then fine-tune the crop, output format, and compression quality for each image individually before downloading the results in a single, convenient ZIP archive (or a direct download for single files).

The application operates entirely in the browser, ensuring your images are never uploaded to a server, prioritizing speed and privacy.

✨ Key Features
Category

Feature

Description

Workflow

Drag-and-Drop Upload

Quickly load multiple files by dragging them directly into the designated area.

Precision

Global Ratio Presets

Set a default aspect ratio (e.g., 9:16, 1:1) instantly applied to all uploaded images.

Automation

Auto-Centered Crop

On upload, the crop box automatically centers itself to intelligently frame the content based on the current aspect ratio, providing a great starting point.

Flexibility

Local Overrides

Override the global ratio, fill color, output format, and JPEG quality for specific images that require unique treatment.

Control

Individual Card Controls

Each image card includes buttons to Reset the Crop back to its auto-centered state and Regenerate ID for filename customization.

Output

Flexible Output Format

Choose between PNG (for quality and transparent backgrounds) or JPEG (for smaller file size) for each file.

Compression

Adjustable JPEG Quality

A slider appears for JPEG outputs, allowing per-file control over compression quality (1-100).

Batching

ZIP Download

Download all processed images in a single ZIP file, maintaining their original output format and quality settings. Automatically switches to Direct Download for single files.

UI/UX

Visual Feedback

Local override controls (ratio, color, format) show a colored border when they deviate from the global/default setting, making overrides easy to spot.

🚀 How to Use
The application is designed for a simple, responsive, full-screen workflow:

1. Set Global Defaults
Use the preset buttons (e.g., 9:16, 1:1) or the custom input fields to establish the default aspect ratio. This ratio will be applied to every image upon upload.

2. Upload Files
Drag and drop your JPEG or PNG files onto the dedicated drop zone, or click the zone to open the file selector.

Each valid file (max 5MB) will generate an individual Crop Gallery Card.

The cropping box will appear immediately, automatically centered to the default aspect ratio.

3. Adjust and Override
For each image card, you can:

Visually Adjust: Drag, zoom, or pan the cropper window on the image preview to fine-tune the selection.

Local Ratio Override: Use the dropdown to set a ratio different from the global default (the border turns red to indicate the override).

Fill Control: Change the color or toggle the 'Fill Empty Area' checkbox if the crop area extends beyond the original image boundaries.

Output Format: Switch the output from PNG to JPEG and adjust the quality slider (0-100) for compression control.

Reset/Regenerate: Use the quick buttons to reset the current crop or assign a new unique ID to change the resulting filename prefix.

4. Download Results
Click the main Download button at the bottom:

Multiple Files: A single batch_cropped_images.zip file will be downloaded containing all processed images with their unique settings.

Single File: The file will be downloaded directly without zipping.

💻 Tech Stack
HTML5 / Vanilla JavaScript (ES Modules): Core structure and interactivity logic.

Tailwind CSS: Fully responsive, utility-first styling framework.

Cropper.js (v1.6.1): Powerful, client-side image cropping library.

JSZip (v3.10.1): Used for creating the multi-file ZIP archive client-side.

FileSaver.js (v2.0.5): Ensures cross-browser compatibility for file downloading.