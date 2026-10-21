# Ember Studio downloads

[Download Ember Studio 1.0.1](https://github.com/danieldickinson/EmberStudio-Releases/releases/tag/v1.0.1) — Apple Silicon (M1 or newer), macOS 27+.

This public repository holds compiled test releases and the signed automatic-update feed. Application source is maintained separately in a private repository.

Open the DMG, drag Ember Studio to Applications, eject the image, then launch. No separate developer tools, Python, VLC or Ollama installation is needed. These test releases are not Apple-notarised; see the release's INSTALL.txt for installation guidance.

Speech models download on first use and stay on this Mac across app updates. Settings → Offline AI → Enable offline AI prepares all three speech models plus Gemma 3 4B (about 8 GB) for local speech, prompts and media descriptions. Media enhancement, transcription and audio-isolation assets are included. Offline setup does not block networking; browsing, website downloads and updates still require a connection.

Settings → AI processing lets you compare CPU only, Prefer GPU and Automatic. Settings → Updates controls signed daily checks and automatic downloads. Ember Studio → Check for Updates checks manually. Updates wait for active jobs before relaunch.

Use INSTALL.txt and SHA256SUMS.txt attached to the release for installation guidance and checksum verification. appcast.xml is cryptographically signed and must not be manually edited.

Version 1.0.1 is an unnotarised public test release. Developer ID signing and Apple notarisation will follow in a new version once enrolment is resolved. Create VR includes Metal rendering, concurrent depth inference and folder conversion; Fix VR has been removed.

Version 1.0.1 fixes Settings responsiveness, improves Chromium event scheduling, and adds clearer update and model-download activity in Settings.
