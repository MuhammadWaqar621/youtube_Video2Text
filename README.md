![banner img](https://i.ibb.co/4tzG9LY/Video2-Text-Banner.png)


# Video2Text

Video2Text allows you to easily convert a youtube video to text. This process is also called transcription.
It is completely free to use and runs locally on your pc.



## Written Tutorial

[PLEASE MAKE SURE YOU HAVE FFMPEG INSTALLED!](https://www.geeksforgeeks.org/how-to-install-ffmpeg-on-windows/)

```$ apt-get install ffmpeg```
or
```$ brew install ffmpeg```

--------------------------------------

0. clone the repo with `git clone https://github.com/MuhammadWaqar621/youtube_Video2Text.git`
1. cd into webserver
2. pip3 install -r requirements.txt
3. streamlit run app.py
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


## Author

Muhammad Waqar


## Version History

- 0.2
  used streamlit for frontend
- 0.1
  - Initial Release

## License

This project is licensed under the MIT license

## Acknowledgments

OpenAI Whisper\* [here](https://github.com/openai/whisper)
