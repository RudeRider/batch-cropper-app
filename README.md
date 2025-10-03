🎬 Digital Asset Tools (Batch Cropper & Video Frame Capture)
This is a comprehensive, single-file web application designed for fast, client-side manipulation of images and videos. It eliminates the need for server-side processing or external software by leveraging modern browser APIs, including the HTML5 Canvas, Cropper.js, and browser-based file utilities.

✨ Features
The application is split into two primary tools accessible via the header navigation:

1. Batch Cropper
The Batch Cropper allows users to upload multiple JPEG or PNG files and apply consistent or customized cropping rules across the entire batch before downloading them as a single ZIP file.

Feature

Description

Global Aspect Ratio

Set a default ratio (e.g., 16:9, 1:1, 9:16) that applies to all images.

Local Overrides

Override the global ratio, output resolution, output format (PNG/JPEG), and JPEG quality for individual images.

Visual Indicators

Each card displays a clear indicator showing whether the image is using the Global Default or a Local Override ratio.

Image Manipulation

Controls for Rotation (90° clockwise) and Horizontal Flipping are available on each card.

Resizing & Fill

Optionally set fixed output resolutions and define a solid fill color (default is white) if the cropped area doesn't match the required output dimensions.

Batch Download

Compiles all processed images into a single .zip file for efficient downloading using JSZip.

2. Video Frame Capture
This tool allows users to load a video file and extract high-quality still frames (PNG) at specific moments or in timed batches.

Feature

Description

Frame Extraction

Capture the exact frame at the current video playback position.

Batch Capture

Automatically capture a user-defined number of frames at a set time interval (e.g., capture 5 frames every 0.5 seconds).

Frame Gallery

Review captured frames in a sidebar gallery. Frames can be individually deleted.

Batch Export

Download all captured frames compiled into a single .zip file.

🛠️ Technical Stack
This is a highly optimized, single-file HTML application utilizing client-side resources:

HTML5/CSS3 (Tailwind CSS): For structure, styling, and a fully responsive layout.

JavaScript (ES6+): All application logic, state management, and file handling.

Cropper.js: Provides the interactive, touch-friendly image cropping interface.

JSZip: Used for client-side compression to create the batch .zip download files for both cropped images and video frames.

FileSaver.js: Enables cross-browser saving of the generated Blobs (images and ZIP archives).

🚀 Usage
Open digital_asset_tools.html in any modern web browser.

Switch between Batch Cropper and Video Frame Capture using the buttons in the header.

Follow the numbered steps provided in the sidebar of each tool.

Use the global settings for batch rules, and individual card controls for fine-tuning specific files.