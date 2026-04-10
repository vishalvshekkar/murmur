# Murmur

**Voice-to-text for Mac. Private by default.**

Murmur is a native macOS app for voice-to-text dictation, meeting transcription, voice notes, and teleprompter. Work fully offline with local models, or use cloud transcription with your own API keys. Your data, your choice.

**Website:** [murmur.you](https://murmur.you) · **Docs:** [murmur.you/docs](https://murmur.you/docs/)

---

## Features

### Dictate in Every App

Press a keyboard shortcut, speak, and text appears at your cursor. Works in any app: Slack, Notion, VS Code, your browser, email drafts, anywhere. Three dictation modes:

- **Push-to-talk** — hold to record, release to transcribe
- **Toggle** — press once to start, again to stop
- **Auto** — quick tap toggles, longer hold is push-to-talk

Text is pasted directly into the active app or copied to your clipboard. 99 languages with auto-detection.

### Context-Aware AI

Murmur detects what app you're using and adapts AI refinement to match. In a code editor, it preserves technical terms. In email, it produces polished prose. It reads browser URLs, window titles, and editor context (project, file, language) to get the tone right. Four permission levels with graceful degradation. Off by default.

### Meetings & Import

Record entire meetings with speaker diarization and automatic chunked transcription. Meetings are saved in 5-minute chunks for crash recovery. A menu bar indicator shows recording status across all apps.

- **AI summaries** with key points and action items
- **Auto-generated titles** and timestamped transcripts
- **Import audio/video** files (M4A, MP3, WAV, MP4, MOV, up to 60 min)

### Voice Notes

A separate hotkey for quick voice capture. Notes are saved with audio playback and optional AI refinement. The **AI Librarian** automatically builds a running summary of your notes collection, tracking recurring topics, people, and projects.

### Teleprompter (Beta)

Paste a script and read it while Murmur follows along with your voice. Three modes:

- **Live** — highlights words as you speak in real time
- **Voice-Activated** — scrolls while you talk, pauses on silence
- **Auto-Scroll** — moves at a fixed words-per-second rate

### 30+ Transcription Models

- **WhisperKit** — multiple Whisper model sizes (tiny to large-v3), 99 languages
- **NVIDIA Parakeet** — fastest and most accurate for English (V2 and V3)
- **Apple Speech** — system-managed, no download needed (macOS Tahoe)
- **OpenAI API** — cloud-based, highest accuracy, requires API key

Every model shows real benchmark data (WER, speed ratings). Download only what you need.

### AI Cleanup & Refinement

Optional post-processing that fixes punctuation, strips filler words, and adjusts tone. Works with:

- **Ollama** — free, local, runs on your Mac
- **OpenAI** — cloud, requires API key
- **Cloudflare AI Gateway** — cloud, flexible routing
- **OpenAI-compatible APIs** — any provider with a compatible endpoint

### Export & Playback

Export transcriptions as **SRT** (subtitles), **WebVTT** (web video), or **timestamped text**. Meeting exports include speaker labels. Play back any recording with seek and speed control (0.5x to 2x).

### Statistics Dashboard

Track time saved, words per minute, usage heatmaps, app distribution, streaks, personal records, and AI refinement stats. Filter by source and time range.

### Streaming Transcription

See words appear in real time as you speak. Partial results display during recording so you know it's working.

---

## Requirements

- **Apple Silicon** (M-series) Mac
- **macOS 15** (Sequoia) or later

> macOS 26 (Tahoe) adds Apple SpeechAnalyzer and Liquid Glass effects. All other features work fully on Sequoia.

---

## Download

**[Download Murmur 1.3](https://github.com/vishalvshekkar/murmur/releases/latest/download/Murmur-1.3.dmg)** · [Release notes & older versions](https://github.com/vishalvshekkar/murmur/releases)

### Pricing

- **$29** one-time purchase, lifetime updates
- **7-day free trial** with full access, no credit card
- **2 Mac licenses** included
- No subscription, no account required

---

## Editions

| Feature | Direct Download | App Store |
|---------|:-:|:-:|
| Local + cloud transcription | ✓ | ✓ |
| 99 languages, auto-detect | ✓ | ✓ |
| Streaming results | ✓ | ✓ |
| Meeting recording + diarization | ✓ | ✓ |
| Voice notes + AI Librarian | ✓ | ✓ |
| Teleprompter (beta) | ✓ | ✓ |
| AI refinement | ✓ | ✓ |
| Export (SRT, WebVTT, text) | ✓ | ✓ |
| Statistics dashboard | ✓ | ✓ |
| **Auto-paste to any app** | ✓ | — |
| **Context-aware AI** | ✓ | — |

The App Store version (coming soon) is sandboxed — you paste manually from the clipboard.

---

## Privacy

With local models, your audio stays on your Mac. No server, no upload, no internet required. Cloud models send audio to the provider you choose, using your own API key. Murmur never collects audio, transcription content, or personal data. [Privacy Policy](https://murmur.you/privacy.html)

---

## Links

- **Website:** [murmur.you](https://murmur.you)
- **Help Center:** [murmur.you/docs](https://murmur.you/docs/)
- **Privacy Policy:** [murmur.you/privacy.html](https://murmur.you/privacy.html)
- **Terms of Service:** [murmur.you/terms.html](https://murmur.you/terms.html)
- **Refund Policy:** [murmur.you/refunds.html](https://murmur.you/refunds.html)
- **Contact:** [hello@murmur.you](mailto:hello@murmur.you)

---

*Built for Apple Silicon. Requires macOS Sequoia or later.*
