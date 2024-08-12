

# GetBetterHead

GetBetterHead is an AI chatbot that answers in the mental health, psychology, and neurology domains. This innovative tool leverages a comprehensive database of video transcripts from reputable YouTube experts in these fields. The chatbot delivers accurate and insightful responses using state-of-the-art natural language processing techniques. 

**DISCLAIMER** 

## Written Tutorial

[PLEASE MAKE SURE YOU HAVE FFMPEG INSTALLED!](https://www.wikihow.com/Install-FFmpeg-on-Windows)

```$ apt-get install ffmpeg```
or
```$ brew install ffmpeg```

--------------------------------------

0. clone the repo with `git clone https://github.com/XamHans/video-2-text.git`
1. cd into webserver
2. pip3 install -r requirements.txt
3. streamlit run chatbot_app.py (locate this app to your folder)
4. open http://localhost:8501 in your browser

## Help

If you should have any troubles try to re-install pytube.
```
pip uninstall pytube
pip uninstall pytube3
pip install pytube
```
if you should run into an error where streamlit is not recognized by your terminal, try this command in your terminal: export PATH="$HOME/.local/bin:$PATH"

If you still have problems, create a new issue.


## Support
If you want to support me, you can buy me a coffee: https://www.buymeacoffee.com/hayerhans
Your support means a lot to me, thanks!

## Author

Johannes Hayer
https://jhayer.tech

## Version History

- 0.2
  used streamlit for frontend
- 0.1
  - Initial Release

## License

This project is licensed under the MIT license

## Acknowledgments

OpenAI Whisper\* [here](https://github.com/openai/whisper)
