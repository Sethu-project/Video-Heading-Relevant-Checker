# Video-Heading-Relevant-Checker
# 🎥 Heading-Content Relevancy Checker

## 📌 Overview
This application analyzes video transcripts and evaluates how relevant the **headings** (topics or titles) are to the **actual content** of the video.  
It automatically assigns **marks/scores** based on semantic similarity between the heading and the video content.

---

## 🚀 Features
- Extracts text content from video (via transcript or speech-to-text).
- Compares headings with video content using **NLP semantic similarity**.
- Allots marks based on relevancy (e.g., 0–10 scale).
- Generates a report showing:
  - Heading
  - Content summary
  - Relevancy score
  - Feedback

---

## 🛠️ Tech Stack
- **Python 3.9+**
- **Libraries**:
  - `transformers` (for semantic similarity using Sentence-BERT or similar models)
  - `scikit-learn` (for scoring and evaluation)
  - `pandas` (for structured output)
  - `streamlit` (optional, for UI dashboard)
  - `whisper` or `speechrecognition` (for transcript extraction from video/audio)


## ⚙️ How It Works
1. **Input**: Provide a video file or transcript text.
2. **Heading Extraction**: Supply the heading(s) to be checked.
3. **Transcript Processing**: Convert video speech → text (if needed).
4. **Semantic Analysis**: Compare heading vs. transcript using embeddings.
5. **Scoring**: Assign marks based on similarity threshold.
6. **Output**: Report with scores and feedback.


