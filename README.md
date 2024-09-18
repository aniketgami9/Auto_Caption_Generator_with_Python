# Auto Caption Generator

This project is designed to automatically generate and synchronize captions for videos. It uses Python and integrates several powerful tools and libraries to achieve accurate and well-timed captions. The best part? It’s completely free of cost.

## Features

- **Automatic Captioning:** Transcribes spoken content into text.
- **Synchronized Captions:** Ensures captions are properly aligned with the audio.

## Libraries and Tools

- **Python 3.x:** The programming language used for development.
- **[FFmpeg](https://ffmpeg.org/download.html):** A tool for video processing.
- **[MinGW](https://osdn.net/projects/mingw/releases/):** Provides the necessary compilation tools.
- **[OpenAI Whisper](https://github.com/openai/whisper):** For speech-to-text transcription.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/auto-caption-generator.git
   cd auto-caption-generator
Install Python Dependencies:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
Install FFmpeg:

Follow the installation instructions for FFmpeg on your operating system.
Install MinGW:

Download and install MinGW as per the instructions on its official site.
Download Whisper Model:

Follow the setup instructions from the Whisper repository to obtain the necessary model files.
File Formats
Input Video Formats: .mp4, .avi, .mov, and other common video formats.
Output Caption Format: .srt (SubRip Subtitle) for captions.
Usage
For detailed instructions on how to use the script, refer to the Usage Guide in this repository.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
OpenAI Whisper for the speech-to-text model.
FFmpeg for video processing capabilities.
MinGW for compiling tools.
Cost
This project and all associated tools are free of cost.
