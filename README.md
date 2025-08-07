# YouTube Video Summarizer using Google Gemini Pro

This project is a Streamlit-based web application that takes a YouTube video link, extracts its transcript, and generates a summarized version of the video content using Google Gemini Pro. It provides concise, point-wise notes that capture the essence of the video in under 250 words.

---

## Project Highlights

- Built using Python and Streamlit for an interactive web interface.
- Integrates with Google Gemini Pro to generate high-quality summaries.
- Automatically fetches transcripts from YouTube videos using `youtube-transcript-api`.
- Generates clean, concise summaries in bullet-point format.
- Displays the video thumbnail and detailed notes for user-friendly viewing.

---

## Tech Stack

- **Language:** Python  
- **Frontend/UI:** Streamlit  
- **APIs/Libraries:** 
  - `google.generativeai` (Gemini Pro)
  - `youtube-transcript-api`
  - `dotenv` (for secure API key loading)

---

## How It Works

1. The user enters a YouTube video URL into the web app.
2. The app extracts the transcript using the video ID via the YouTube Transcript API.
3. The transcript is sent to Google Gemini Pro with a prompt for summarization.
4. Gemini Pro returns a point-wise summary within 250 words.
5. The summary and video thumbnail are displayed on the Streamlit app.

