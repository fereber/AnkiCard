# Anki Cards

Template and style of Anki cards.

![Multifunctional Card](https://raw.githubusercontent.com/Ber-Fer/AnkiCard/master/screenshot.gif)

## Fields

1.  Front (Sort by this field in browser)
2.  Back
3.  Picture
4.  Sound
5.  Audio File Name
6.  Video File Name\*
7.  Story\* / Subtitle 1
8.  Subtitle 2
9.  Notes

### Default

Easy-to-read cards with toggle switch fields (show/hide).

| Field                | Comment                                        |
| -------------------- | ---------------------------------------------- |
| **Front**            | **expression here; sort by this field**        |
| **Back**             | **expression translation**                     |
| Picture              | optional; `<img src="story_audio_file.jpg" />` |
| Sound                | optional; `[sound:story_audio_file.mp3]`       |
| Audio File Name      | optional; `story_audio_file.mp3`               |
| Video File Name\*    | _leave blank!_                                 |
| Story\* / Subtitle 1 | _leave blank!_                                 |
| Subtitle 2           | no displayed;                                  |
| Notes                | optional;                                      |

The following fields are available to show/hide content:

-   Front (to use the note as a reverse card as well)
-   Front Type  (to check if you are correct)
-   Audio File Name (to replay the audio)
-   Notes (show your comments)

**Note:** Playing video and audio files (this way) are only supported with AnkiDroid.

### Story

Fill out the field of `Story\* / Subtitle 1*`, so the carrd is suitable for longer content as well.

| Field                    | Comment                                           |
| ------------------------ | ------------------------------------------------- |
| **Front**                | **title of story; sort by this field**            |
| Back                     | optional; eg. the front translation               |
| Picture                  | optional; `<img src="story_audio_file.jpg" />`    |
| Sound                    | no displayed;                                     |
| Audio File Name          | optional; `story_audio_file.mp3`                  |
| Video File Name\*        | _leave blank!_                                    |
| **Story\* / Subtitle 1** | **if it's not empty, the card become story card** |
| Subtitle 2               | optional; eg. the front content translation       |
| Notes                    | optional;                                         |

### Video

If you use this syntax in Anki cards: `[sound:video_file_name.webm]`, it's works fine! But there aren't subtitles and the learning time will be false in statistics. Use `_video_file_name.webm` in the Video File Name\* field instead of `[sound:video_file_name.webm]` syntax.

| Field                      | Comment                                             |
| -------------------------- | --------------------------------------------------- |
| **Front**                  | **title of video; sort by this field**              |
| Back                       | no displayed                                        |
| Picture                    | no displayed                                        |
| Sound                      | no displayed                                        |
| Audio File Name            | no displayed                                        |
| **Video File Name\***      | **if it's _not_ empty, the card become video card** |
| **Story\* / Subtitle 1**   | **optional; subtitle 1 come here**                  |
| **Subtitle 2**             | **optional; subtitle 2 come here**                  |
| Notes                      | no displayed;                                       |

Use the `Story\* / Subtitle 1` and `Subtitle 2` fields for subtitles, in the following example, Video Subtitling with Web Video Text Tracks (WebVTT) format:

    WEBVTT

    00:08.000 --> 00:14.000
    Hello!
    This is a subtitle.

    00:15.000 --> 00:12.000
    Ok.

"At the moment there are [no limits on the size of your media](https://anki.tenderapp.com/kb/anki-ecosystem/are-there-limits-on-file-sizes-on-ankiweb), although the **size of individual** media files is limited to 100MB."

Use video file larger than 100 MB, so the Anki only synchronizes the note type with subtitles and **not video files**. (You have to copy the video file to Anki's media folder.)
