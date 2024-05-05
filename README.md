# YouTube Transcriber

## Summary

YouTube Transcriber is a Streamlit application designed to extract transcripts from YouTube videos and provide them in text format. It utilizes the YouTube Transcript API to extract transcripts from public YouTube videos based on their URLs.

## Features

- **Transcript Extraction**: Uses the YouTube Transcript API to extract transcripts from YouTube videos.
- **Text Output**: Provides the extracted transcript in text format for further processing or analysis.

## Usage

1. Paste the YouTube video link into the provided input box.
2. Click the "Get Transcript" button to extract the transcript.
3. The extracted transcript will be displayed in text format.

## Requirements

- Python 3.x
- Streamlit
- youtube_transcript_api
- requests

## Installation

To set up the project locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/your_username/yt-transcriber.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Set up your environment variables by creating a .env file and adding your Google API key:
   ```bash
   GOOGLE_API_KEY=your_api_key_here
   
4. Run the application:
   ```bash
   streamlit run yt_transcriber.py

## Acknowledgments

1. Special thanks to Dendra Verma for the original project.
2. I acknowledge that I watched Krish Naik's video to gain inspiration for this project. The video link is [here](https://www.youtube.com/watch?v=VZOnp2YpY8Q&list=PLZoTAELRMXVNbDmGZlcgCA3a8mRQp5axb&index=10&t=1s).

This project utilizes the Google Gemini Pro library and the YouTube Transcript API.
