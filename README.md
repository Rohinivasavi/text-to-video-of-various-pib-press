#Text-to-Video Generator with Avatar, Audio, Translation & Image Overlays

This project is a complete automated system that converts "text → translated text → speech → video" using Python inside Google Colab. It generates a final MP4 video with a looping avatar, synchronized audio, and timed image overlays.

Project Highlights
✔ Automatically translates text to any language
✔ Generates speech using gTTS
✔ Loops avatar video to match the audio duration
✔ Adds images at fixed timestamps (10s, 25s, 40s...)
✔ Supports custom positions like "left", "top"
✔ Exports a final MP4 video
✔ 100% automated inside Google Colab
✔ Suitable for mini or major capstone projects
System Overview
Pipeline:

User provides input text
Text is translated (googletrans / LibreTranslate)
gTTS converts translated text to audio (.mp3)
Avatar video is resized & looped
Images are overlayed at specific times
MoviePy merges everything into a final MP4
Architecture: Simple pipe-and-filtersystem.

Tools & Technologies
python 3.10+
Google Colab
moviepy – video generation
googletrans / LibreTranslate – translation
gTTS – text-to-speech
Pillow – image processing
Install in Colab:

!pip install moviepy gTTS pillow googletrans==4.0.0-rc1
