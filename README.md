DEMO: https://screen-recorder-pied.vercel.app

# Screen Recorder Application

A React-based screen recording application that allows users to record their screen, view the recorded video, and download it.

## Features

- **Start/Stop Recording**: Easily start and stop screen recording with a single button.
- **Recording Timer**: Displays the recording time in minutes and seconds.
- **Preview Recorded Video**: View the recorded video directly in the browser.
- **Download Video**: Download the recorded video in WebM format.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/screen-recorder-app.git
Navigate to the project directory:

bash
Copy code
cd screen-recorder-app
Install the dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm run dev
Usage
Open your browser and navigate to the development server URL provided by Vite.
Click the Start Recording button to begin recording your screen.
Stop the recording by clicking the Stop Recording button.
Preview the recorded video.
Download the video using the Download Video button.
How It Works
Screen Recording:

The app uses the navigator.mediaDevices.getDisplayMedia API to capture the screen.
The MediaRecorder API is used to record the captured stream.
Recording Timer:

A timer is implemented using setInterval to track the recording duration.
Video Processing:

The recorded video is stored in a Blob and displayed using a URL.createObjectURL reference.
Download Video:

The recorded video can be downloaded by linking the Blob URL to an <a> tag with a download attribute.
File Structure
Navbar: Displays a sticky navigation bar with a project logo.
Start/Stop Button: Toggles the recording state.
Timer Display: Shows the current recording time.
Video Preview: Displays the recorded video for review.
Download Button: Allows users to download the video in WebM format.
Dependencies
This project uses the following dependencies:

json
Copy code
{
  "react": "^18.3.1",
  "react-bootstrap": "^2.10.7",
  "react-dom": "^18.3.1",
  "bootstrap": "^5.3.3"
}
Dev Dependencies
json
Copy code
{
  "@vitejs/plugin-react": "^4.3.4",
  "vite": "^6.0.5"
}
Future Improvements
Add support for audio recording.
Allow customization of recording resolution and format.
Include error handling for unsupported browsers.
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for any bugs or feature requests.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Built with ❤️ by Asad.