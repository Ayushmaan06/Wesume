# W-Resume: Assistance for Resume Management  📈
A tool designed to streamline resume analysis, review, and improvement using advanced AI and NLP technologies. This application helps users refine their resumes to be Applicant Tracking System (ATS)-compliant and optimize them for better professional opportunities.

## Features 🚀
- File Upload & Text Extraction

  - Supports PDF, DOCX, TXT, and RTF formats.
  - Extracts content from resumes for analysis.
- Resume Parsing

  -Identifies key sections like name, email, phone, education, experience, and skills using SpaCy.
- ATS Compliance Review

  - Leverages Google PaLM AI to analyze resumes for ATS compliance.
  - Scores resumes out of 100 and provides section-wise feedback with improvement suggestions.
- Conversational Refinement

  - Chat-based interaction to help users refine resumes further.
  - Powered by Google PaLM or offline models like ChatOllama.
- PDF Generation

  - Creates ATS-friendly resumes in PDF format for download.
- Interactive Dashboard

  - Displays real-time feedback and allows interactive resume editing.
## Installation 💻
- Clone the Repository
```
git clone https://github.com/your-repo/karm.git
cd karm
```
- Install Dependencies
  -Ensure you have Python 3.8+ installed.

```bash
pip install -r requirements.txt
```
- Set Up Environment Variables
  - Create a .env file with your Google API Key:

```
GOOGLE_API_KEY=your_google_api_key
```
Run the Application

```bash
streamlit run app.py
```
## Usage 📋
- Launch the app on your browser (default: http://localhost:8501).
- Upload your resume file via the sidebar.
- Click "Review Resume" to start the analysis.
- Interact with the AI to get specific suggestions for improvement.
- Download the optimized ATS-friendly PDF.
## Technical Details 🔍
- AI Models:
  - Google PaLM for resume review and conversational AI.
  - ChatOllama for offline interactions.
- Text Processing:
  - SpaCy for entity recognition and text parsing.
  - RecursiveCharacterTextSplitter for chunking long texts.
- Vector Storage:
  - FAISS for efficient similarity search and retrieval.
- PDF Generation:
  - ReportLab for generating high-quality PDFs.

## Future Enhancements 🌟
- Add multilingual support for resume parsing.
- Improve scoring by incorporating industry-specific benchmarks.
- Extend compatibility to more document formats.
## Contributions 🤝
Contributions are welcome! Feel free to fork this repository, raise issues, or submit pull requests.

