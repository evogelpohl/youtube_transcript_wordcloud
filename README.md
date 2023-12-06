# YouTube Transcript Word Cloud Generator

## Introduction
This project provides a tool to extract transcripts from YouTube videos, process the text data, and generate a word cloud visualization. It's particularly useful for analyzing keynotes or presentations to quickly identify the most frequently mentioned terms.

## Installation

### Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.x
- pip (Python package installer)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/evogelpohl/youtube_transcript_wordcloud
   ```
2. Navigate to the project directory:
   ```bash
   cd youtube_transcript_wordcloud
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To use this tool, follow these steps:

1. Find the YouTube video ID for the transcript you want to analyze. The video ID is the string after `watch?v=` in the YouTube URL.
2. Open the script and replace the `video_id` variable's value with your desired YouTube video ID.
3. Run the script:
   ```bash
   python [Your Script Name].py
   ```
4. The script will display a word cloud based on the transcript of the provided YouTube video.

## Customization

You can customize the list of stop words in the script by modifying the `more_stop_words` list. Add any word you want to exclude from the word cloud analysis.

## Acknowledgments

This project uses several open-source packages:
- [youtube_transcript_api](https://pypi.org/project/youtube-transcript-api/)
- [NLTK](https://www.nltk.org/)
- [wordcloud](https://pypi.org/project/wordcloud/)
- [matplotlib](https://matplotlib.org/)

## License

[MIT License](LICENSE)

## Contact

Eric Vogelpohl - eric.vogelpohl@outlook.com

Project Link: https://github.com/evogelpohl/youtube_transcript_wordcloud