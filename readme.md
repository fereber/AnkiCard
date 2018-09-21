# Anki Cards

Templates and styles of my Anki cards.

<figure style="float: left; width:32%; padding-right:1%; margin:0;">
  <img style="border:1px solid #eee;" src="https://raw.githubusercontent.com/Ber-Fer/AnkiCard/master/screenshots/language-card.gif">
  <figcaption style="text-align: center; font-size: 75%;">Language Card</figcaption>
</figure>

<figure style="float: left; width:32%; padding-right:1%; margin:0;">
  <img style="border:1px solid #eee;" src="https://raw.githubusercontent.com/Ber-Fer/AnkiCard/master/screenshots/screenshot_10.jpg">
  <figcaption style="text-align: center; font-size: 75%;">Video Card (with subtitles)</figcaption>
</figure>

<figure style="float: left; width:32%; padding-right:1%; margin:0;">
  <img style="border:1px solid #eee;" src="https://raw.githubusercontent.com/Ber-Fer/AnkiCard/master/screenshots/screenshot_09.jpg">
  <figcaption style="text-align: center; font-size: 75%;">Simple Card</figcaption>
</figure>

<br style="clear: both">

[More sreenshots...](https://github.com/Ber-Fer/AnkiCard/tree/master/screenshots)

## Type of cards

### Simple card

**Fields:**

1.  Front (Sort by this field in browser)
2.  Back

### Language card

It's only supported on AnkiDroid!

**Fields:**

1.  Target (Sort by this field in browser)
2.  Native
3.  Sound
4.  Reply
5.  Picture
6.  Notes

### Video card

Show video with subtitle on Anki cards.

It's only supported on AnkiDroid!

**Fields:**

1.  Video Title (Sort by this field in browser)
2.  Video File Name
3.  Target Subtitle Content
4.  Native Subtitle Content

#### Default media player

If you use this syntax in Anki cards: `[sound:video_file_name.webm]`, it's works fine! But there aren't subtitles and the learning time will be false in statistics.

#### Video Subtitling with Web Video Text Tracks (WebVTT) format

The 'Subtitle Content' field for subtitles, in the following example:

    WEBVTT

    00:08.000 --> 00:14.000
    Hello!
    This is a subtitle.

    00:15.000 --> 00:12.000
    Ok.

#### Anki file size limit

"At the moment there are [no limits on the size of your media](https://anki.tenderapp.com/kb/anki-ecosystem/are-there-limits-on-file-sizes-on-ankiweb), although the **size of individual** media files is limited to 100MB."

Use video file larger than 100 MB, so the Anki only synchronizes the note type with subtitles and **not video files**. (You have to copy the video file to Anki's media folder.)
