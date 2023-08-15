# Video-to-Hinglish Text Conversion Project

This project is designed to split a video into several parts, extract audio from each part, convert the audio to text, and then translate the extracted text to Hinglish, which is a mix of Hindi and English. The goal is to provide a convenient tool for processing videos and extracting meaningful content in Hinglish, making it more accessible to a wider audience.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Project Overview

The Video-to-Hinglish Text Conversion Project consists of a set of Python scripts and tools that work together to achieve the following tasks:

1. **Video Splitting:** The project takes an input video and splits it into several smaller parts, each of a specified duration.

2. **Audio Extraction:** For each split video segment, the audio is extracted and saved as a separate audio file.

3. **Speech-to-Text Conversion:** The extracted audio files are converted to text using a speech recognition library.

4. **Translation to Hinglish:** The generated text is then translated to Hinglish, which is a combination of Hindi and English, making the content more accessible and understandable to non-native Hindi speakers.

## Features

- Split a video into multiple parts.
- Extract audio from video segments.
- Convert audio to text using speech recognition.
- Translate the extracted text to Hinglish.
- Customizable parameters for splitting, audio extraction, and translation.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/VamsiMuraparthi/video-to-hinglish.git
   cd video-to-hinglish
   ```

2. Install the required dependencies:

   ```bash
   pip install moviepy googletrans SpeechRecognition
   ```

## Usage

1. Place the input video file in the project directory.

2. Open the `split_and_convert.ipynb` script and customize the parameters according to your needs (e.g., input video filename, duration of video segments).

3. Run the script in Jupyter Notebook:

   ```bash
   python split_and_convert.ipynb
   ```

4. The script will split the video, extract audio, convert speech to text, and translate the text to Hinglish. The results will be saved in the `output` directory.

## Dependencies

- `moviepy`: For video splitting and audio extraction.
- `googletrans`: For translating text to Hinglish.
- `SpeechRecognition`: For converting audio to text.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to create a pull request or submit an issue.


---

By Vamsi_Muraparthi

For any inquiries, please contact [vamsimuraparthi@gmail.com].
