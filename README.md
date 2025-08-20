# 🎓 YouTube Lecture Summarizer and Note Generator AI

A **Streamlit-based AI tool** that allows you to convert YouTube lecture videos into summarized notes, generate smart study notes, and create personalized study plans. Users can also ask questions about the lecture summary in a chat-like interface.

---

## 🛠 Features

1. **YouTube Transcript Extraction**  
   - Fetches transcripts from any public YouTube lecture video.

2. **Lecture Summarization**  
   - Generates concise summaries in bullet points.
   - Creates smart, self-explanatory notes for easy review.

3. **Interactive Q&A**  
   - Ask questions based on the lecture summary.
   - Answers are generated using the summary as context.

4. **Personalized Study Plan Generator**  
   - Create day-by-day study plans based on your exam date and preferred study hours.

5. **PDF Export**  
   - Download lecture summaries, notes, and study plans as PDF files.

---

## ⚡ Requirements

- Python 3.10+
- Install dependencies:

```bash
pip install -r requirements.txt


🔧 Setup

Clone the repository:

git clone https://github.com/Billal0845/YouTube-Lecture-Summarizer-and-Note-Generator-AI.git
cd YouTube-Lecture-Summarizer-and-Note-Generator-AI


Create a .env file in the project root:

OPENAI_API_KEY=sk-your_api_key_here


Run the app:

streamlit run app.py

📖 Usage

Enter the YouTube lecture URL.

Click Summarize Transcript to generate summary and notes.

Ask questions related to the lecture summary.

Click Create Study Plan to generate a personalized plan.

Download PDFs of summaries or study plans.

⚠️ Notes

Do not commit your .env file with the API key.

.gitignore already excludes .env to keep your API key safe.

💡 Future Improvements

Add support for multiple video URLs at once.

Enhance Q&A with more context understanding.

Integrate advanced study plan customization options.
