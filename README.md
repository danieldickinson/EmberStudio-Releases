# Ember Studio downloads

[Download Ember Studio 1.3.0](https://github.com/danieldickinson/EmberStudio-Releases/releases/tag/v1.3.0) — Apple Silicon (M1 or newer), macOS 27+.

This public repository holds release notes, checksums and the signed automatic-update feed. Version 1.3.0 installers are hosted at https://downloads.ngen.uk/ember/. Application source is maintained separately in a private repository.

Version 1.3.0 is Developer ID-signed and Apple-notarised. Open the DMG, drag Ember Studio to Applications, eject the image, then launch. No separate developer tools, Python, VLC or Ollama installation is needed. Normal macOS folder-access prompts may still appear. Older test releases remain unnotarised.

AI Chat provides local streaming conversations, saved history, image/text attachments and actual HTML, script and text files with preview and export. The model manager browses public Hugging Face GGUF models, shows estimated memory fit for this Mac and tests local text generation. Fit estimates do not guarantee every context size or vision workload. Start the engine and select or download a model from Chat → Models. Image attachments require a vision-capable model.

Speech models download on first use and stay on this Mac across app updates. Settings → Offline AI → Enable offline AI prepares all three speech models plus Gemma 3 4B (about 8 GB) for local speech, prompts, image chat and media descriptions. Media enhancement, transcription and audio-isolation assets are included. Offline setup does not block networking; browsing, website downloads and updates still require a connection.

Settings → AI processing lets you compare CPU only, Prefer GPU and Automatic. Settings → Updates controls signed daily checks and automatic downloads. Ember Studio → Check for Updates checks manually. Updates wait for active jobs before relaunch.

Use INSTALL.txt and SHA256SUMS.txt attached to the release for installation guidance and checksum verification. appcast.xml is cryptographically signed and must not be manually edited.

Create VR includes Metal rendering, concurrent depth inference and folder conversion. Fix VR has been removed. Embedded Apple Passwords/passkey support remains deferred.

Local image and video generation includes LTX 2.5 MLX Q4 and experimental MiniMax H3 MLX with video/audio, configurable duration and resolution, and Library generation metadata. H3 runtime: [appautomaton/mlx-h3](https://github.com/appautomaton/mlx-h3). Model weights download separately and their access/licence terms apply. H3 needs at least 48 GB unified memory in this experimental configuration and about 74 GB of model storage; LTX Q4 needs at least 32 GB and about 28.8 GB. Longer clips are allowed with guidance, but fit and quality are not guaranteed.
