# Anki Note Type: Language Card - Video

Show video with subtitle on Anki cards.

**It's only supported on AnkiDroid!**

## Fields

1.  Video Title (Sort by this field in browser)
2.  Video File Name
3.  Target Subtitle Content
4.  Native Subtitle Content

## Default media player

If you use this syntax in Anki cards: `[sound:video_file_name.webm]`, it's works fine! But there aren't subtitles and the learning time will be false in statistics.

## Video Subtitling with Web Video Text Tracks (WebVTT) format

The 'Subtitle Content' field for subtitles, in the following example:

    WEBVTT

    00:08.000 --> 00:14.000
    Hello!
    This is a subtitle.

    00:15.000 --> 00:12.000
    Ok.

## Anki file size limit

"At the moment there are [no limits on the size of your media](https://anki.tenderapp.com/kb/anki-ecosystem/are-there-limits-on-file-sizes-on-ankiweb), although the **size of individual** media files is limited to 100MB."

Use video file larger than 100 MB, so the Anki only synchronizes the note type with subtitles and **not video files**. (You have to copy the video file to Anki's media folder.)
