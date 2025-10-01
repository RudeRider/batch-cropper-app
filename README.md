Batch Image Cropper Gallery
A minimalist, client-side web application for batch cropping multiple PNG and JPEG images to a uniform aspect ratio or custom dimensions, with the added capability of filling transparent areas with a solid color.

This tool is designed for speed and efficiency, allowing users to upload up to 30 files, view them in an interactive gallery, apply global crop settings, and download all resulting cropped images in a single ZIP archive.

✨ Features
Batch Processing: Upload up to 30 PNG and JPEG files at once.

Interactive Gallery: View and manipulate all uploaded images simultaneously in a responsive grid.

Global Aspect Ratio Control: Instantly apply standard presets (16:9, 4:3, 1:1) or custom ratios to all images.

Free Crop Mode: Choose a "Free Crop" ratio (NaN) to allow independent, unrestricted cropping for each image.

Individual Manipulation: Fine-tune the position and scale of the crop box on each image using the Cropper.js interface.

Solid Color Fill: Automatically fill transparent areas (created by cropping outside the original image boundary) with a user-specified solid color (default: white).

Single-Click ZIP Download: All successfully processed images are compressed and downloaded as one convenient batch_cropped_images.zip file.

Single-File Application: The entire tool runs client-side, requiring no server setup or complex dependencies.

🚀 Getting Started (Using GitHub Pages)
Since this is a single-file application (index.html), hosting it is extremely easy using GitHub Pages.

Create a Repository: Create a new public repository on GitHub (e.g., batch-cropper).

Upload Files: Upload both the index.html and this README.md file to the root of your new repository.

Enable Pages: Go to your repository's Settings tab, navigate to Pages, select the main branch, and the / (root) folder, then click Save.

View Live: Your application will be live in a few moments at a URL like: https://[your-username].github.io/[repo-name]/

🛠️ Usage Instructions
Set Global Crop Settings:

Select an Aspect Ratio Preset (e.g., 16:9) or use the Custom Ratio inputs and click "Apply." This ratio will be enforced on all images.

Choose your Empty Area Fill Method: Check the box to use a solid color fill (and select the color), or uncheck it to maintain transparency in cropped-out areas.

Upload Files: Click "Upload PNG or JPEG Files" and select up to 30 images. They will appear instantly in the gallery.

Adjust Crops: If needed, use your mouse to move (pan) the images and adjust the crop box positions within the gallery.

Download: Click "Download All Cropped PNGs (ZIP)". The tool will process each image and download the final ZIP archive containing all the cropped files.