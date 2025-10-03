🎬 Digital Asset Tools (Single-File Application)
This application is a self-contained HTML file providing three separate, useful tools for working with media assets. Switch between the tools using the menu bar at the top.

1. Batch Cropper
A tool for efficiently cropping and resizing multiple images (PNG/JPEG) simultaneously before downloading them as a single ZIP archive.

Key Features:
Drag & Drop Upload: Upload multiple images instantly.

Global Aspect Ratio: Apply a common aspect ratio (e.g., 9:16, 1:1, custom) to all images for consistent output.

Local Overrides: Customize the aspect ratio, output resolution, and background fill color for individual images.

Fixed Resolution Output: Resize the cropped area to a specific pixel dimension (e.g., 1080x1920) or use auto-size based on the crop box dimensions.

Batch Download: Compile all processed images into a single .zip file.

2. Video Frame Capture
A utility for extracting high-quality still images (frames) from an uploaded video file.

Key Features:
Frame Grab: Capture the frame visible in the video player at the current time.

Batch Capture (Interval): Automatically capture a specified number of frames at a constant time interval (e.g., 10 frames every 0.5 seconds).

Frame Gallery: Review, delete, and manage captured frames before download.

ZIP Export: Download all captured frames as individual PNG files compressed in a .zip archive.

3. Text Editor / Scratchpad (Live JSON Highlight)
A minimalist text editor with developer-focused features, ideal for drafting, editing, or validating configuration files.

Key Features:
Live Syntax Highlighting: Automatically detects and highlights text as JSON in real-time. If the content is invalid JSON or plain text, the highlighting is disabled for a clean scratchpad experience.

Stats Counter: Displays word count and character count at the top.

Download: Save the text content to a .txt file with a custom filename.

Note: The editor intelligently handles and ignores JavaScript-style // and /* */ comments when attempting to validate the JSON structure, allowing for common config file practices.