# add_subtitle_to_video

Add subtitle(.srt) to downloaded Youtube videos



#### How to use the code?

- Preparation

  - Download videos from Youtube with `Youtube-dl` or `yt-dlp`;
  - Get the Youtube auto-generated subtitles: (the example subtitles are take from this video https://www.youtube.com/watch?v=ELoGT5uD_j4&ab_channel=NicoRosberg)

  <img src="images/get_subtitles_from_youtube.jpg" alt="get_subtitles_from_youtube" style="zoom: 67%;" />

  - Copy (select and `cmd-c`) the subtitles with timestamps ***on***; save the subtitles to a `.txt` file;

    <img src="images/copy_subtitles.jpg" alt="copy_subtitles" style="zoom:67%;" />

  - Make sure ffmpeg has been installed on your machine; [How to install?](https://www.ffmpeg.org/)
  - Python 3.x is a must;
  - Ready to go!

- Command to run

  - Modify the filenames and file paths in the `main function`;
  - In command line, run `python embed_subtitle.py`
  - The code will burn the subtitles onto the video with a 250x speed. Really really fast!