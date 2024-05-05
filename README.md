YouTube Transcript Summarizer

Summary
YouTube Transcript Summarizer is an "end-to-end" application that utilizes Google's Gemini Pro library to transcribe and summarize YouTube videos automatically. It extracts transcripts from public YouTube videos using the YouTube Transcript API and generates concise summaries using gemini Pro's summarization capabilities.

Features
Transcript Extraction: Utilizes the YouTube Transcript API to extract transcripts from public YouTube videos.
Summary Generation: Implements prompt-based summarization using gemini Pro's "generate_content" function.
Streamlit App: Provides a Streamlit application with components for inputting YouTube video links, displaying video thumbnails, and presenting the generated summary.

Usage
Paste the YouTube video link into the input box.
Click the "Get Detailed Notes" button.
The app will automatically extract the transcript and generate a summary based on the given prompt.

Reference
The original project was developed by Dendra Verma.

Installation
To set up the project locally, follow these steps:

Clone the repository:

git clone https://github.com/vaisharma16/trendin.git

Install dependencies:

pip install -r requirements.txt

Create a .env file and add your Google API key:

GOOGLE_API_KEY=your_api_key_here

Run the Streamlit app:

streamlit run app.py

Acknowledgments

Special thanks to Dendra Verma for the original project.
I acknowledge that I watched Krish Naik's video to gain inspiration for this project. The video link is [here](https://www.youtube.com/watch?v=VZOnp2YpY8Q&list=PLZoTAELRMXVNbDmGZlcgCA3a8mRQp5axb&index=10&t=1s).

This project utilizes the Google Gemini Pro library and the YouTube Transcript API.
