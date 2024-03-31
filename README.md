# WebDAV-Media-Organizer

This is a web-based application that allows users to access their media files stored on a WebDAV server. It fetches metadata from The Movie Database (TMDb) to enhance the user experience.

## Features:

- [x] Login with WebDAV protocol, username, password, server IP/domain, port, path
- [x] Listing of files and directories
- [x] Opening files with various media players (Infuse, VLC, or in-browser)
- [x] Navigating through directories
- [ ] Fetching metadata from TMDb for media files
- [ ] Displaying media information (title, description, cover art, etc.)
- [x] Logout functionality

## Known Issues:

The application may encounter CORS (Cross-Origin Resource Sharing) errors and mixed content issues when accessing HTTP and HTTPS resources.

## Technologies Used:

- HTML
- CSS
- JavaScript
- WebDAV protocol
- TMDb API

## Installation and Usage:

1. Clone the repository or alternatively, you can simply open the application at [https://qooode.github.io/WebDAV-Media-Organizer/](https://qooode.github.io/WebDAV-Media-Organizer/).
2. Open the `index.html` file in a web browser.
3. Enter the WebDAV URL, username, and password to log in.
4. Browse and interact with the media files and directories.
5. To log out, click the "Logout" button.

## Contributing:

- Fork the repository
- Create a new branch for your feature or bug fix
- Make your changes and commit them
- Submit a pull request

## Acknowledgments:

This project was created to enhance the user experience of managing media files stored on a WebDAV server like AList or subscription services like Real-Debrid.
