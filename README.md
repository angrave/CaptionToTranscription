# Caption To Transcription

An privacy-preserving accessibility tool to convert SRT and VTT files to a plain text transcription. The tool is available here-

https://angrave.github.io/CaptionToTranscription/

## Features
* Privacy-preserving; no caption data is sent or stored on a server.
* ARIA and screen-reader support.
* Speaker changes ("Speaker:") and Speaker change ("- ") cause paragraph breaks
* HTML Entity support (e.g. &gt; &amp;)
* Support for multiline cues vtt and srt
* Extended paraphraph lengths if the caption does not finish a sentence.

# Example input
```txt
1
00:02:00,400 --> 00:04:15,300
This is an example of
a srt <b>subtitle</b> &amp; entity.

2
00:08:16,400 --> 00:15:25,300
This is an example of a
2 line cue.
```

