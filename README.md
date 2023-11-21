
# Custom Video Player

## Overview

This is a custom video player built using HTML5, CSS3, and JavaScript. It provides a simple and customizable solution for embedding and controlling videos on web pages.

## Features

- HTML5 video playback
- Customizable player controls
- Fullscreen mode
- Play/pause functionality
- Seek functionality
- Volume control
- Time display
- Responsive design

## Usage

1. **Include the Files:**
   - Add the `index.html`, `style.css`, and `script.js` files to your project.

2. **HTML Structure:**
   - Create a `div` element with a unique ID for the video player.

   ```html
   <div id="custom-video-player">
       <!-- Video element will be appended here dynamically -->
   </div>
   ```

3. **Initialize the Player:**
   - Include the `script.js` file in your HTML file.

   ```html
   <script src="path/to/script.js"></script>
   ```

   - Initialize the video player by calling the `initVideoPlayer()` function.

   ```html
   <script>
       document.addEventListener("DOMContentLoaded", function () {
           initVideoPlayer();
       });
   </script>
   ```

4. **Customization:**
   - Customize the appearance and functionality by modifying the `style.css` and `script.js` files.

## Configuration Options

You can customize the following options in the `script.js` file:

- **Video Source:** Change the `videoSrc` variable to specify the path to your video file.

   ```javascript
   const videoSrc = "path/to/your/video.mp4";
   ```

- **Player Controls:** Modify the appearance and functionality of player controls in the `createControls()` function.

## Browser Compatibility

This video player is designed to work on modern browsers that support HTML5 video playback. Ensure that your target audience uses up-to-date browsers for the best experience.

## License

This custom video player is released under the [MIT License](LICENSE).

## Acknowledgments

- Built with ❤️ by [Md. Shoeb]
- Icons by []

## Support

If you encounter any issues or have questions, please [open an issue](https://github.com/mdshoeb2050/Video-player.git).
