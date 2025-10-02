🎬 Digital Asset Tools: Batch Cropper & Frame Capture
This application bundles two powerful, client-side tools designed for efficient media asset preparation directly in your browser. All processing, including image manipulation, frame extraction, and ZIP compilation, is handled locally for speed and privacy.

✨ Application Structure
The interface uses a sticky header for quick tool switching and a responsive two-column layout on large screens:

Controls (Right Sticky Sidebar): Provides persistent access to file upload, global settings, and batch download buttons for the active tool, regardless of scroll position.

Tool Content (Left Area): Displays the working area, such as the Cropper Gallery or the Video Player.

🖼️ Tool 1: Batch Image Cropper
This tool streamlines the process of cropping multiple images to a specific aspect ratio or fixed pixel resolution.

🚀 Batch Cropper Workflow
1. Upload Files (Sticky Sidebar): Drag-and-drop or select your PNG/JPEG images.

2. Set Global Settings (Sticky Sidebar): Define the default Aspect Ratio (e.g., 9:16) for all images.

4. Crop Gallery (Left Area): Review all images and use the local controls for granular adjustments.

3. Batch Download (Sticky Sidebar): Use the main button to download all processed images in a single ZIP file.

🛠️ Local Controls Explained (Per Image)
Control

Description

Default Setting

Local Ratio Override

Overrides the global aspect ratio for this image only. Keeps the mouse wheel zoom enabled for precise control, while preventing accidental scrolling of the main page.

Uses Global Default

Output Resolution

Sets the final image dimensions in exact pixels. Use presets (like 1080x1920) or define custom WxH.

1080x1920 (Story)

Fill Empty Area

Toggles solid color filling for transparent areas (occurs when cropping outside the original image bounds).

Checked (White Fill)

Output Format

Allows selection between PNG (better for quality/transparency) or JPEG (smaller file size, uses quality slider).

PNG

Download Single Image

Downloads the current image immediately, applying all local settings.

N/A

🎥 Tool 2: Video Frame Capture
This tool lets you upload a short video and extract individual frames as high-quality PNG images.

🚀 Frame Capture Workflow
1. Upload Video (Left Area): Select an MP4, MOV, or other common video file.

Capture Frames:

Single Frame: Manually move the video timeline scrubber to the desired moment, then click "Capture Frame".

Auto Batch: Use "Capture 10 Frames (Auto)" to quickly extract 10 frames based on the current time and the set interval (in seconds).

2. Captured Frames (Right Sidebar): Review the gallery of captured frames. You can delete frames individually.

Download: Click "Download All Frames (ZIP)" to save all captured PNG images in a compressed archive.