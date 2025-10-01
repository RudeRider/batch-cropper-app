🖼️ Batch Image Aspect Ratio Cropper
This is a client-side web application designed to quickly process multiple images, allowing you to crop them to a consistent aspect ratio, and handle background filling or transparency, all before downloading the results in a single ZIP file.

The application leverages Cropper.js for interactive cropping, JSZip for bundling the final images, and FileSaver.js for triggering the download.

✨ Key Features
Batch Processing: Upload multiple PNG or JPEG files (up to 30 files, max 5MB each) simultaneously for parallel cropping.

Global Aspect Ratio Control: Set a default aspect ratio (e.g., 9:16, 1:1, 16:9) that applies to all loaded images.

Individual Image Overrides: Locally override the aspect ratio, background fill color, and output format for any specific image without affecting the others.

Crop Box Auto-Centering: When the ratio is set, the crop box automatically centers itself to include the largest possible area of the image while maintaining the required aspect ratio.

Flexible Output: Choose between:

PNG: Best for transparency or lossless quality. (Enforced if Fill is unchecked).

JPEG: For smaller file sizes, configurable quality (1% to 100%).

Fill or Transparent Background: If the crop box extends beyond the image bounds, you can choose a solid color fill (default white) or use transparency (PNG output required).

Unique Export Naming: Each cropped image receives a unique, collision-proof filename based on a random ID and the final output resolution (img_UNIQUEID_WxH.ext).

🚀 How to Use
Set Global Defaults (Step 1):

Select one of the preset aspect ratio buttons (e.g., 9:16 (Story)) or input custom width and height values and click Apply. This ratio is applied automatically to all images upon upload.

Upload Images (Step 2):

Click the "Choose Files" button or drag and drop your PNG/JPEG images onto the upload zone.

Review and Adjust Crops (Step 3):

The Crop Gallery will appear with an interactive cropper for each image.

Manual Adjustment: Drag and resize the crop box on any image to adjust the composition. The ratio constraint will be maintained based on the current setting.

Local Overrides: Use the dropdowns on each image card to:

Change the Local Ratio Override to a different ratio for that single image.

Toggle the Fill Empty Area checkbox and select a color if you want to use a solid background.

Change the Output Format (PNG or JPEG) and adjust the quality if JPEG is selected.

Reset: Use the circular arrow button to instantly reset the crop box to the auto-centered position based on the active ratio.

Download (Step 4):

Click the "Download All Cropped Images (ZIP)" button. The application will process each image according to its current crop and local settings, bundle them, and prompt you to download the .zip archive.

(Note: If only one file is loaded, it will download directly without zipping.)

🛠️ Technical Stack
This application is built entirely using vanilla JavaScript and HTML, relying on external libraries for functionality:

HTML5 / Tailwind CSS: For structure and fully responsive styling.

Cropper.js: For the interactive, client-side image cropping interface.

JSZip: For creating the downloadable .zip file archive in the browser.

FileSaver.js: For initiating the cross-browser file save/download process.