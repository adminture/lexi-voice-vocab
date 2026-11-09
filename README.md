# 🎙️ Lexi – Voice Vocabulary Coach

A voice agent prototype that helps you learn vocabulary. Lexi reads a definition aloud, you say the word, and she gives instant feedback, an example sentence, hints, and re-queues words you missed.

**Live demo:** https://YOUR-USERNAME.github.io/lexi-voice-vocab/

## How it works
- Text-to-speech and speech recognition via the browser's Web Speech API (no backend, no API keys)
- Fuzzy answer matching using the top 5 recognition guesses
- Voice commands: "hint", "repeat", "skip"
- Typed-answer fallback if the mic is unavailable

## Run locally
Open `index.html` in Chrome or Edge. (Mic access needs HTTPS or localhost, so for local use run `python3 -m http.server` and visit http://localhost:8000.)

## Browser support
Chrome / Edge recommended. Firefox has no speech recognition (typed fallback works).

## Next steps
- LLM-generated words and example sentences by level
- "Use it in a sentence" mode judged by an LLM
- Custom word lists and spaced repetition
