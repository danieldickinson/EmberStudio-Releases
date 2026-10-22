# Ember Studio downloads

[Download Ember Studio 1.1.0](https://github.com/danieldickinson/EmberStudio-Releases/releases/tag/v1.1.0) — Apple Silicon (M1 or newer), macOS 27+.

This public repository holds compiled releases and the signed automatic-update feed. Application source is maintained separately in a private repository.

Version 1.1.0 is Developer ID-signed and Apple-notarised. Open the DMG, drag Ember Studio to Applications, eject the image, then launch. No separate developer tools, Python, VLC or Ollama installation is needed. Normal macOS folder-access prompts may still appear. Older test releases remain unnotarised.

AI Chat provides local streaming conversations, saved history, model selection and image attachments. Start the engine and select or download a model from Chat → Models. Image attachments require a vision-capable model.

Speech models download on first use and stay on this Mac across app updates. Settings → Offline AI → Enable offline AI prepares all three speech models plus Gemma 3 4B (about 8 GB) for local speech, prompts, image chat and media descriptions. Media enhancement, transcription and audio-isolation assets are included. Offline setup does not block networking; browsing, website downloads and updates still require a connection.

Settings → AI processing lets you compare CPU only, Prefer GPU and Automatic. Settings → Updates controls signed daily checks and automatic downloads. Ember Studio → Check for Updates checks manually. Updates wait for active jobs before relaunch.

Use INSTALL.txt and SHA256SUMS.txt attached to the release for installation guidance and checksum verification. appcast.xml is cryptographically signed and must not be manually edited.

Create VR includes Metal rendering, concurrent depth inference and folder conversion. Fix VR has been removed. Embedded Apple Passwords/passkey support remains deferred.
