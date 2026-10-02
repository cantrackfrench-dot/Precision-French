# Precision French

WebAR audio scanner and reading app for "Precision French: The Strategic Guide to DELF Preparation" using a lesson-based structure.

## What this app includes

- lesson library with 40 lesson cards
- lesson detail page with audio playback
- matching audio file load per lesson
- reading exercise page per lesson
- previous/next lesson navigation
- library and lesson switching flow
- placeholder AR scan button ready for future image-triggered lesson mapping

## Folder structure

- `index.html` — main app UI and lesson logic
- `audio/README.md` — naming guide for lesson audio files
- `audio/` — place lesson MP3 files here in the format `lesson-01.mp3`, `lesson-02.mp3`, ...

## Lesson audio naming pattern

Place files like this:

- `audio/lesson-01.mp3`
- `audio/lesson-02.mp3`
- `audio/lesson-03.mp3`
- ...
- `audio/lesson-40.mp3`

The app loads the matching file automatically when a lesson is opened.

## Reading exercise flow

Each lesson can open a reading page with:

- reading comprehension text
- key vocabulary
- navigation between lessons
- return to the audio lesson page

## Status

The core lesson architecture is in place and ready for real audio and reading content.

Add your actual lesson audio files and expand the reading content for later lessons to complete the experience.
