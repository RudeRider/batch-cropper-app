🖼️ Batch Image Aspect Ratio Cropper
Introduction
The Batch Image Aspect Ratio Cropper is a client-side tool designed to efficiently prepare multiple images for publishing, particularly for platforms requiring specific aspect ratios (like social media stories, banners, or video thumbnails).

It leverages Cropper.js for precise visual manipulation and JSZip/FileSaver.js for fast, in-browser batch processing and download.

✨ Features
Batch Upload: Process multiple PNG or JPEG files simultaneously.

Drag-and-Drop Support: Quickly initiate upload by dragging files directly onto the upload zone.

Global Default Ratio: Set a single aspect ratio (default 9:16) that applies to all images, saving significant time.

Auto-Centering: On load or crop reset, the crop box automatically centers itself within the largest possible area of the image while respecting the chosen aspect ratio.

Per-File Overrides: Customize settings for individual images using local controls:

Local Ratio: Override the global ratio to apply a unique ratio or enable a free crop.

Fill Control: Toggle solid color filling for areas cropped outside the original image boundary, with a customizable color picker.

Reset/Rename: Reset Crop to the original auto-centered position or Regenerate ID for a unique export name prefix.

Flexible Output: Set the output format for each image individually:

PNG: For best quality and support for transparent backgrounds (when fill is disabled).

JPEG: For smaller file sizes, with an adjustable Quality Slider (1-100).

Visual Feedback: Local overrides are clearly indicated by color-coded borders on the input fields.

Batch Download: Download all processed images compiled into a single .zip file. Automatically initiates a direct download for single files.

🚀 How to Use
Set Global Defaults (Section 1): Select one of the preset aspect ratios (e.g., 9:16) or define a custom ratio using the input fields. This ratio will be applied to all newly uploaded images.

Upload Files (Section 2):

Click the "Upload PNG or JPEG Files" input.

OR, drag and drop your image files directly into the dashed upload zone.

Adjust Crops (Section 3 - Crop Gallery):

Each image appears in the gallery with the global default ratio applied (and auto-centered).

Click and drag the crop box to refine the selection.

Use the Local Ratio Override dropdown to change the ratio just for that image (e.g., switch one image to 1:1 while others remain 9:16).

Toggle Fill Empty Area and select a color if you want to pad out the image rather than leaving transparent borders.

Select the desired Output Format (PNG or JPEG) and adjust the quality if JPEG is chosen.

Download: Click the green "Download All Cropped Images (ZIP)" button at the bottom.

If only one file is present, it will download directly.

If multiple files are present, a ZIP archive named batch_cropped_images.zip will be downloaded containing all processed files.

🛠️ Technology Stack
HTML5/JavaScript: Core application logic.

Tailwind CSS: Responsive styling and modern UI.

Cropper.js: Image manipulation and cropping library.

JSZip: Client-side file compression for batch download.

FileSaver.js: Cross-browser file download utility.