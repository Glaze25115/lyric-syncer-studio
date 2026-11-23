# Lyrics Syncer Studio
A basic **Vibe-coded** lyric synchronizing web-tool that works for some players like [Metrolist](https://github.com/MetrolistGroup/Metrolist) and [ViVi Music](https://github.com/vivizzz007/vivi-music).

# About This Tool
What it does is to synchronize lyrics to the track currently playing

**Example**: Tapping space adds a timestamps to a line or word, depending on the synchronizing mode.

Functions and shortcuts
- Basics
  - Next Line - `Spacebar`
  - Undo - `Backspace`
  - Paste or Add existing `.txt` or `.lrc`
  - Adding required audio files, any audio files like `.mp3`, `.m4a`, `.flac`, etc
  - Save as `.lrc`, need compiling and exporting result first then save with the track's filename like `songFilename.mp3`.
- Advanced
  - Switch to Pipestream LRC or Normal .LRC, Normal .LRC is the default
  - Switch to Line-by-line, or Word-by-word
  - Toggle Character-by-character or Mix(Switch to word-by-word first)
  - Pipeline `|` and Hyphen `-` Separators
  - Vocal roles v1, v2, v3, Bg(Background vocal role), and crowd vocal role(v1000)
  - Romanization button

## Shortcut Keys
- `Spacebar` - Next word/next line
- `V` - Word end - Stamps the end time of a word or character
- `Backspace` - Undo the current line
- `0...5` - Vocal Roles
  - `0` - Off
  - `1` - Voice 1
  - `2` - Voice 2
  - `3` - Voice 3
  - `4` - Background Singer role
  - `5` - Crowd Vocals


-----
**Word Grouping**: Wrap multiple words in chevrons like `<gonna be>` to stamp them together as one unit.

**Syllable Splitting**: Use `|` directly inside raw words `(e.g., to|ge|ther)` to split them into seamless separate stampable targets. 

**Mix Mode (Word + Char)**: In Word-by-Word mode, Mix keeps Latin words `(including ' and -)` together and respects `|` and `<...>`, while splitting non-Latin/CJK/Cyrillic and em/en-dashes individually without adding extra spaces.

**Romanize Toggle**: Toggle Romanize independently to show offline romanization under pills and lines in Line-by-Line, Word-by-Word, Char-by-Char, and Mix modes.

**Instant Sentence Jump**: On the final word of a line, pressing Next Word ends that word, hops lines, and starts the next line instantly!

**Hot Audio Audition**: Click any already-synced row to instantly jump the audio player back to that line's exact start timestamp.

-----

# Go see site
[Visit Site](https://glaze25115.github.io/lyric-syncer-studio/)

Vibe-coded using Gemini AI
