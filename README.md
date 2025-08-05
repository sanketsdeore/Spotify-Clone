# Spotify Clone

## Overview
This project is a Spotify Clone, a web application that mimics core functionalities of the Spotify music streaming service. It allows users to play music, manage playlists, and enjoy a simple music streaming experience using locally stored songs.

## Features
- **Music Playback**: Play, pause, and skip songs stored in a local folder.
- **Playlist Management**: Create and manage playlists with local music files.
- **Search Functionality**: Search through locally stored songs by title or artist.
- **Responsive Design**: User interface optimized for both desktop and mobile devices.
- **Simple UI**: Clean and intuitive interface built with vanilla HTML, CSS, and JavaScript.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Data Source**: Songs fetched from a local folder
- **No Backend**: Purely client-side application

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sanketsdeore/Spotify-Clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Spotify-Clone
   ```
3. Add your music files:
   - Place your `.mp3` or other supported audio files in a designated folder (e.g., `/songs`).
   - Update the JavaScript code to point to this folder for fetching songs.
4. Open the application:
   - Open `index.html` in a web browser to run the application locally.

## Usage
- Open `index.html` in a browser to access the application.
- Browse and play songs from the local folder.
- Use the search bar to find specific tracks or create playlists from available songs.

## Folder Structure
```
Spotify-Clone/
├── index.html        # Main HTML file
├── css/             # CSS styles
│   └── style.css
├── js/              # JavaScript files
│   └── script.js
├── songs/           # Local folder for storing music files
│   └── *.mp3
└── README.md        # Project documentation
```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License.

## Contact
For questions or suggestions, feel free to reach out to the project maintainer at [your-email@example.com].
