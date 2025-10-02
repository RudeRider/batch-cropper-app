🖼️ Batch Image Aspect Ratio Cropper
This is a powerful, client-side application designed for efficiently cropping multiple images to a uniform aspect ratio (or fixed pixel resolution). All processing, including cropping, resizing, filling, and ZIP compilation, is handled directly in your browser, ensuring speed and privacy.

The user interface is split into two main columns:

Controls (Right Sticky Sidebar): Persistent access to upload, global settings, and batch download, regardless of scroll position.

Gallery (Left Scrollable Area): Displays individual cropping previews and local, per-image overrides.

✨ Features
Batch Upload: Supports multiple PNG and JPEG files via file selection or drag-and-drop.

Sticky Controls: Global settings and download button remain visible in a fixed sidebar while scrolling the gallery.

Global Aspect Ratio Presets: Easily set a default ratio (e.g., 9:16, 1:1, 16:9) applied to all images.

Custom Ratio Input: Define any custom ratio (e.g., 5:2).

Individual Cropping Previews: Adjust the crop box for each image visually using the Cropper.js interface.

Prevent Accidental Zoom: Mouse wheel scrolling over the image area is reserved for image zoom only, preventing accidental page scroll interference.

Local Overrides (Per Image):

Local Ratio Override: Set a unique aspect ratio for an individual image.

Output Format & Quality: Choose PNG (for transparency) or JPEG (with adjustable quality/compression).

Solid Color Fill: Apply a solid background color to areas outside the original image boundary (useful when cropping a landscape photo to a portrait ratio).

Fixed Output Resolution: Optionally define an exact width and height in pixels for the final image output.

Download Options:

Batch Download (ZIP): Download all processed images compiled into a single ZIP file.

Local Download: Download a single processed image directly from its card.

🚀 Workflow
Upload Files (Step 1): Use the file input or drag-and-drop your PNG/JPEG images into the zone in the sticky sidebar.

Set Global Settings (Step 2): Select a default Aspect Ratio or apply a Custom Ratio. This is automatically applied to all loaded images.

Review Gallery (Step 4): Images appear in the gallery area on the left.

For each image, you can manually drag the crop box to refine the selection.

Use the local controls on each card to override the ratio, set a fixed Output Resolution, choose Fill Color, or change the Output Format.

Download (Step 3):

Use the large "Download All Cropped Images (ZIP)" button in the sidebar to process and download the entire batch.

Use the "Download Single Image" button on individual cards for immediate download.

🛠️ Local Controls Explained
Each image card provides detailed local controls that override the global settings:

Control

Description

Visual Feedback

Local Ratio Override

Sets a specific ratio for this image only.

Indigo border/ring if not set to "Global Default".

Fill Empty Area

Toggles solid color filling for transparent areas (when cropping outside the source image bounds).

Pink border/ring if fill color is not the default white (#ffffff) and the toggle is checked.

Output Resolution

Sets the exact pixel dimensions (W x H) for the final exported image (rescales the cropped content).

Orange border/ring if either Width or Height has a valid input.

Output Format

Allows selection between PNG (better for transparency/quality) or JPEG (smaller size, uses quality slider).

Green border/ring if set to JPEG.

