🎯 YouTube Hate Speech Detection using BERT & Flask

This project is a Flask-based web application that detects Hate Speech and Non-Hate Speech in YouTube video comments. It uses the pre-trained unitary/toxic-bert model from HuggingFace Transformers to classify comments in real-time.

The app provides:

✅ Real-time hate speech detection

📊 Visualization with pie charts

📥 Downloadable results (CSV format)

📈 Model evaluation metrics (Accuracy, Precision, Recall, F1 Score)

🔄 Reset functionality to clear old results

🚀 Features

🔹 Input YouTube video URL to fetch comments

🔹 Preprocessing and classification using BERT

🔹 Hate/Non-Hate distribution via Pie Chart

🔹 Export results as CSV

🔹 Check evaluation metrics (/metrics route)

🔹 Clean and modern UI with dark theme

**File structure** 

<pre>youtube-hate-speech-detector/<br>
├── app.py                # Main Flask app<br>
├── utils.py              # Helper function to fetch YouTube comments<br>
├── templates/<br>
│   ├── index.html        # UI for input & results<br>
│   ├── metrics.html      # Metrics page<br>
├── static/<br>
│   ├── results.csv       # Generated CSV file (after analysis)<br>
│   ├── piechart.png      # Generated pie chart (after analysis)<br>
├── requirements.txt      # Project dependencies<br>
└── README.md             # Documentation</pre>

