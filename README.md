# Chat-Analyzer

A Streamlit-based application to analyze WhatsApp chat exports, providing insights such as message counts, active participants, sentiment analysis, and word usage statistics.

## 🚀 Live Demo

Check out the deployed app here:

[https://chat-analyzer-jjnkgaz9odx5takqdfdqes.streamlit.app/](https://chat-analyzer-jjnkgaz9odx5takqdfdqes.streamlit.app/)

## 📋 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## 🔍 Features

- **Message Overview**: Total messages, media, and emojis used.
- **Participant Analysis**: Top senders, active hours, and chat timeline.
- **Text Analysis**: Most common words, stopwords filtering, and word cloud visualization.
- **Sentiment Analysis**: Breakdown of positive, negative, and neutral messages.

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/samudra-07/Chat-Analyzer.git
   cd Chat-Analyzer
   ```

2. **Create and activate a virtual environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate    # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

## ▶️ Usage

1. **Run the app locally**
   ```bash
   streamlit run app.py
   ```

2. **Upload your WhatsApp chat export** (TXT file) via the sidebar.
3. **Explore** various analytical panels:
   - Overview
   - Timeline & Activity
   - Word Frequency & Cloud
   - Sentiment Breakdown

## ☁️ Deployment

This app is deployed on Streamlit Community Cloud:

1. Verify that your repository contains a valid `requirements.txt`.
2. In your Streamlit Cloud dashboard, connect the GitHub repo `samudra-07/Chat-Analyzer`.
3. Specify `app.py` as the entrypoint and click **Deploy**.
4. Your live app URL will appear—share it with others!

## 📂 Project Structure

```text
Chat-Analyzer/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python packages
├── pages/              # (Optional) Streamlit multipage apps
├── assets/             # Images, fonts, and other static files
└── README.md           # This file
```

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Built with 💬 by [samudra-07](https://github.com/samudra-07)*

