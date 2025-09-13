# To run the Call_Quality_Analyzer_Final.ipynb notebook, follow these simple steps:

Open Google Colab:
Visit https://colab.research.google.com/.

Upload the Notebook:
Click on File > Upload notebook and select the Call_Quality_Analyzer_Final.ipynb file from your local system.

Install Dependencies:
Run the first code cell to install required packages (yt-dlp, faster-whisper, vaderSentiment, and textblob).

Run All Cells Sequentially:
Click Runtime > Run all to execute the notebook end-to-end. This will:

Download YouTube audio from the preset test file URL(you can also provide your custom youtube url)

Transcribe the audio using the faster-whisper tiny model

Detect speakers and calculate talk time ratios

Detect and display all questions asked with enhanced accuracy

Analyze call sentiment

Generate actionable insights

Display comprehensive results with full transparency

View Output:
Results will print within the notebook, including the total questions detected and a numbered list showing all detected questions for easy validation.

This notebook is designed to run efficiently on Google Colab’s free CPU-only tier, completing typical sales call analysis within 15-25 seconds.

Just follow these steps to get a fast, transparent, and detailed call quality analysis!
