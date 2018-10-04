# Anki Cards

Template and style of Anki cards.

![Language card](https://raw.githubusercontent.com/Ber-Fer/AnkiCard/master/screenshot.gif)

## Fields

1.  Front (Sort by this field in browser)
2.  Back
3.  Picture
4.  Sound
5.  Audio File Name
6.  Video File Name\*
7.  Content Front\*
8.  Content Back
9.  Notes

### Default

Easy-to-read cards with toggle switch fields (show/hide).

| Field             | Comment                                        |
| ----------------- | ---------------------------------------------- |
| **Front**         | **expression here; sort by this field**        |
| **Back**          | **expression translation**                     |
| Picture           | optional; `<img src="story_audio_file.jpg" />` |
| Sound             | optional; `[sound:story_audio_file.mp3]`       |
| Audio File Name   | optional; `story_audio_file.mp3`               |
| Video File Name\* | _leave blank!_                                 |
| Content Front\*   | _leave blank!_                                 |
| Content Back      | no displayed;                                  |
| Notes             | optional;                                      |

The following fields are available to show/hide content:

-   Front (to use the note as a reverse card as well)
-   Front Type  (to check if you are correct)
-   Audio File Name (to replay the audio)
-   Notes (megjegyzések megtekintéséhez)

### Story

Fill out the field of `Content Front*`, this format is ideal for longer content.

**Note:** It's only supported on AnkiDroid!

| Field               | Comment                                           |
| ------------------- | ------------------------------------------------- |
| **Front**           | **title of story; sort by this field**            |
| Back                | optional; eg. the front translation               |
| Picture             | optional; `<img src="story_audio_file.jpg" />`    |
| Sound               | no displayed;         |
| Audio File Name     | optional; `story_audio_file.mp3`                  |
| Video File Name\*   | _leave blank!_                                    |
| **Content Front\*** | **if it's not empty, the card become story card** |
| Content Back        | optional; eg. the front content translation       |
| Notes               | optional;                                         |

### Video

If you use this syntax in Anki cards: `[sound:video_file_name.webm]`, it's works fine! But there aren't subtitles and the learning time will be false in statistics. Use `_video_file_name.webm` in the Video File Name\* field instead of `[sound:video_file_name.webm]` syntax.

**Note:** It's only supported on AnkiDroid!

| Field                 | Comment                                             |
| --------------------- | --------------------------------------------------- |
| **Front**             | **title of video; sort by this field**              |
| Back                  | no displayed                                        |
| Picture               | no displayed                                        |
| Sound                 | no displayed                                        |
| Audio File Name       | no displayed                                        |
| **Video File Name\*** | **if it's _not_ empty, the card become video card** |
| **Content Front\***   | **optional; subtitle 1 come here**                  |
| **Content Back**      | **optional; subtitle 2 come here**                  |
| Notes                 | no displayed;                                       |

Use the `Content Front*` and `Content Back` fields for subtitles, in the following example, Video Subtitling with Web Video Text Tracks (WebVTT) format:

    WEBVTT

    00:08.000 --> 00:14.000
    Hello!
    This is a subtitle.

    00:15.000 --> 00:12.000
    Ok.

"At the moment there are [no limits on the size of your media](https://anki.tenderapp.com/kb/anki-ecosystem/are-there-limits-on-file-sizes-on-ankiweb), although the **size of individual** media files is limited to 100MB."

Use video file larger than 100 MB, so the Anki only synchronizes the note type with subtitles and **not video files**. (You have to copy the video file to Anki's media folder.)
