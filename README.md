# Video Refactor

VideoRefactor is a Windows winform application that allows you to easily make common changes
to video files such as changing video and audio codecs, the resolution (1080p to 720p for example),
remove the Default tag on audio and subtitle tracks, and whether to keep any existing subtitle
tracks or not. In addition, it allows you to specify how many seconds to take off the start and end of
the video (for example, if you have your system configured to start recording a few minutes early
and run a few minutes after the desired show to ensure getting the entire program).

First, setup the path to your Ưmpeg executable. This is the tool that VideoRefactor uses to make the
magic happen. If you do not have it, you can get it for free at Download FFmpeg. Press the DSelect
Directory button and selec the directory that has the Ưmpeg.exe executable. Typically something
like C:\ffmpeg\bin. This will be remembered by the app in the future, so you only need to do this
setup one time.

Next select your video file by pressing the Select File button. After a few seconds the video length
and Original Properties will be filled in, and the Desired Properties will be set to the videos original
properties.

Now select any and all changes you desire, and press the Refactor button.

The status line (above the Exit and Refactor buttons), will let you know when the processing is
complete.

## Note
VideoRefactor is CharityWare. If you like this program and find it of value, please consider making a
donation to a local charity that benefits children such as Special Olympics.
