Summary:

This project aims to create an "end to end" application using Google's gemini Pro library to transcribe and summarize YouTube videos automatically.

Transcript Extraction:

Uses the YouTube Transcript API to extract transcripts from public YouTube videos based on their IDs.
The extracted transcript is then converted into a paragraph for further processing.

Summary Generation:

Implements a prompt-based summarization approach using gemini Pro's "generate_content" function.
The prompt instructs gemini Pro to summarize the transcript text into concise points within 250 words.
Streamlit App:

A Streamlit application is created with the following components:
Title: "YouTube Transcript to Detail Notes Converter"
Text input box: Accepts a YouTube video link
Image display: Shows the video's thumbnail image
Button: Triggers the extraction and summarization process
Summary display: Presents the generated summary in markdown format.

Usage:

Paste the YouTube video link into the input box.
Click the "Get Detailed Notes" button.
The app will automatically extract the transcript and generate a summary based on the given prompt.

Reference:

The original project was developed by Dendra Verma.
