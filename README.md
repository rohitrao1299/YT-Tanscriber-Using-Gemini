# YT-Tanscriber-Using-Gemini
# YouTube Transcript to Detailed Notes Converter

This project is a Streamlit application that extracts transcripts from YouTube videos and summarizes them into detailed notes using Google's Generative AI model.

## Features

- **Extract YouTube Transcript**: Extracts and consolidates the transcript from a given YouTube video URL.
- **Generate Summary**: Uses Google Gemini's Generative AI to summarize the transcript into concise, important points.
- **User Interface**: A simple and interactive interface built with Streamlit to input YouTube video URLs and display results.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/your-repo.git

# Navigate to the Project Directory
cd your-repo

# Set Up Environment
Create a .env file in the project root directory and add your Google API key:
GOOGLE_API_KEY=your_google_api_key_here

# Install Dependencies
You can use pip to install the required Python packages:
pip install -r requirements.txt

# Run the Application
Start the Streamlit app with the following command:
streamlit run app.py