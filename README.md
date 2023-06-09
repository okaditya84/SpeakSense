# Profanity-Checker

This repository contains a Python script that performs profanity checking and sentiment analysis on audio files. The script utilizes APIs from Google Speech Recognition, Purgomalum, and the VADER Sentiment Analysis tool.

## Features

- Record audio from the microphone or select an audio file for analysis
- Perform profanity checking using the Purgomalum API
- Analyze sentiment using the VADER Sentiment Analysis tool
- Generate sentiment scores and labels
- Store input and output data in a CSV file

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/okaditya84/Profanity-Checker.git
```

2. Install the required dependencies by running the following command:
   ```shell
pip install -r requirements.txt
```

3. Ensure you have the necessary API keys:

- Google Speech Recognition API key (follow Google's documentation on obtaining an API key)
- Purgomalum API key (visit the Purgomalum website and sign up to get an API key)


## Usage

1. Run the Profanity checker.py script:
   ```shell
python Profanity\ checker.py
```

2. Choose the desired mode of input:

- Enter 'mic' to record audio from the microphone.
- Enter 'file' to select an audio file for analysis.

3. Follow the on-screen instructions:

- If using the microphone, speak clearly into the microphone after the prompt.
- If selecting a file, use the file dialog to choose an audio file.

4. Wait for the script to perform the following tasks:

- Convert audio to text using Google Speech Recognition.
- Preprocess the text by removing stop words and lemmatizing words.
- Check for profanity in the text using the Purgomalum API.
- Analyze the sentiment of the text using VADER Sentiment Analysis.
- Display the results, including the sentiment scores and label.

5. The input text, filtered text, sentiment scores, and sentiment label will be saved in the 'output.csv' file.
