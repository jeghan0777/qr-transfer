# QR Transfer PWA

This is the first PWA version of QR Transfer.

## Architecture

- The website is only used to deliver the application.
- Files are processed locally in the browser.
- The sender displays QR frames.
- The receiver scans the frames locally.
- The file is not uploaded to the hosting server.
- HTTPS is required for camera access.
- After the app shell is cached/installed, it can be opened without the hosting server for the cached app shell.

## Important

The current QR protocol is still optimized for relatively small files (the original UI says about 500 KB). Larger-file support and bundling the JavaScript dependencies for stronger offline operation are planned for the next iteration.
