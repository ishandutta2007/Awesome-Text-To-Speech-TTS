# Awesome-Text-To-Speech-TTS

# Top Text-to-Speech (TTS) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Neural Voice Synthesis, Voice Cloning & Self-Hosted TTS Models*  
**Last updated: October 2026**

This repository tracks notable **commercial TTS platforms** and **open-source projects** that convert text into natural-sounding speech. These tools range from cloud APIs with premium voices to fully local, offline models that run on your own hardware.

**Examples** include Amazon Polly, ElevenLabs, Google Cloud Text-to-Speech, Azure AI Speech, Murf.ai, WellSaid Labs, Play.ht, Resemble AI, Speechify Studio, and LOVO AI (the category leaders).

**Open-source emphasis**: TTS is one of the strongest open-source domains in 2026. **Kokoro-82M** leads as the best quality-to-size ratio at only 82M parameters, **Chatterbox** delivers MIT-licensed voice cloning, **XTTS-v2** remains the most downloaded voice cloning model, and **Fish-Speech** brings an 8B-parameter multilingual foundation. **Piper** and **MeloTTS** enable CPU real-time inference on edge devices. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ElevenLabs](https://elevenlabs.io/)**  
  **The commercial quality leader in TTS** — premium voice cloning, emotional range, and sub-200ms latency for real-time applications. **Best for production voice agents** where quality is the priority.

- **[Amazon Polly](https://aws.amazon.com/polly/)**  
  **AWS's neural TTS service** — 100+ voices across 40+ languages with SSML support, lexicons, and speech marks. **Best for AWS-native applications** .

- **[Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech)**  
  **Google's TTS with WaveNet and Neural2 voices** — 380+ voices across 50+ languages. **Best for Google Cloud users** .

- **[Azure AI Speech](https://azure.microsoft.com/en-us/products/ai-services/ai-speech)**  
  **Microsoft's TTS with neural voices** — 500+ voices across 140+ languages and locales. **Best for Microsoft ecosystem** .

- **[Murf.ai](https://murf.ai/)**  
  **AI voice generator for studios** — voiceovers, dubbing, and real-time voice changing. **Best for content creators** .

- **[WellSaid Labs](https://wellsaidlabs.com/)**  
  **Enterprise TTS with studio-quality voices** — AI voiceovers for corporate learning and marketing. **Best for enterprise content** .

- **[Play.ht](https://play.ht/)**  
  **AI voice generator with cloning** — 900+ voices across 142 languages. **Best for scalable content production** .

- **[Resemble AI](https://www.resemble.ai/)**  
  **Voice cloning and AI voice generation** — real-time voice cloning and deepfake detection. **Best for security-conscious voice applications** .

- **[Speechify Studio](https://speechify.com/studio/)**  
  **AI voiceover platform** — 120+ voices across 20+ languages with emotion control. **Best for audiobook and video production** .

- **[LOVO AI](https://lovo.ai/)**  
  **AI voice generator and video editor** — 500+ voices across 100+ languages. **Best for marketing and e-learning** .

## Open-Source GitHub Projects

- **[Kokoro-82M](https://github.com/hexgrad/kokoro)**  
  **The best open-source TTS model by quality-to-size ratio**, Apache-2.0 licensed . **Only 82M parameters** — achieves best MOS in its parameter class, outperforming models 10x larger . **Ranked #1 on TTS-Arena for quality/speed ratio** . **Studio-quality speech nearly 100x faster than real-time on GPU** . Supports **English, Japanese, Chinese, Korean, French, German, Italian, Portuguese, Spanish, Hindi, and Russian** . **The de facto open-source TTS standard** for most use cases . **Best for high-quality TTS with minimal compute** .

- **[Chatterbox (Resemble AI)](https://github.com/resemble-ai/chatterbox)**  
  **MIT-licensed TTS with emotion control and zero-shot voice cloning**, MIT licensed . **Chatterbox-Turbo** (350M params) delivers **sub-200ms latency** with paralinguistic tags (`[laugh]`, `[sigh]`, `[cough]`) . **Chatterbox-Multilingual** covers **23+ languages** . **Top scores on TTS-Arena** . **Built-in audio watermark** for responsible AI use . **The best open-source voice cloning model with permissive licensing** . **Best for real-time expressive speech and voice agents** .

- **[XTTS-v2 (Coqui)](https://github.com/coqui-ai/TTS)**  
  **The most downloaded open-source voice cloning model**, MPL-2.0 licensed . **Zero-shot multilingual voice cloning across 17 languages** . **Best MOS in voice cloning among public models** . **Streams with <200ms latency** . **The community standard for voice cloning** . **Best for multilingual voice cloning with established tooling** .

- **[Dia-1.6B (Nari Labs)](https://github.com/nari-labs/dia)**  
  **SOTA dialogal/conversational TTS**, Apache-2.0 licensed . **First open-source model with native multi-speaker dialogue synthesis** — including laughter, sighs, and emotions . **Outperforms ElevenLabs in conversational MOS** . **Best for podcast and dialogue generation** .

- **[Sesame CSM-1B](https://github.com/SesameAILabs/csm)**  
  **Conversational Speech Model focused on naturalness**, Apache-2.0 licensed . **Conversational Speech Model with long-horizon context** . **Rated as human in blind tests** . **Best for audiobooks and natural dialogue** .

- **[Fish-Speech](https://github.com/fishaudio/fish-speech)**  
  **SOTA multilingual TTS with LLM-based architecture**, open-source (review license) . **Dual-AR architecture** with slow and fast transformers . **Firefly-GAN vocoder** with ~100% codebook utilization . **Trained on 720,000 hours of multilingual data** . **~150ms time-to-first-audio** . **0.8% WER** — outperforms ground truth in some cases . **Best for production multilingual voice agents** .

- **[MeloTTS (MyShell)](https://github.com/myshell-ai/MeloTTS)**  
  **High-quality multilingual TTS with CPU real-time inference**, MIT licensed . **Supports English (US/UK/India/Australia), Spanish, French, Chinese (mixed EN), Japanese, and Korean** . **Fast enough for CPU real-time inference** . **Best for edge devices and low-resource environments** .

- **[Piper](https://github.com/rhasspy/piper)**  
  **Fast, local neural TTS optimized for Raspberry Pi**, MIT licensed . **Runs entirely offline** — no internet after setup . **~60MB voice models** . **Best for home automation, privacy-focused TTS, and embedded systems** .

- **[Coqui TTS](https://github.com/idiap/coqui-ai-TTS)**  
  **The comprehensive open-source TTS toolkit**, MPL-2.0 licensed . **Pretrained models in 1100+ languages** . **Training and fine-tuning tools for custom voices** . **Model implementations include XTTS, VITS, Bark, and more** . **Best for research and custom model training** .

- **[Bark (Suno)](https://github.com/suno-ai/bark)**  
  **Expressive TTS with non-speech sounds**, MIT licensed . **Generates laughter, sighs, music, and sound effects** . **Multilingual with creative output** . **Best for creative and experimental applications** .

- **[Orpheus-TTS](https://github.com/canopyai/Orpheus-TTS)**  
  **Emotional TTS built on Llama 3.2 architecture**, Apache-2.0 licensed . **SNAC audio tokens for high-fidelity output** . **Natural emotion tag handling** . **Best for emotionally expressive speech** .

- **[CosyVoice2 (Alibaba)](https://github.com/FunAudioLLM/CosyVoice)**  
  **Multilingual TTS with voice cloning**, Apache-2.0 licensed . **Exceptional multilingual quality with cloning support** . **Best for global applications** .

### Additional Strong Open-Source Options

- **KittenTTS** — Ultra-lightweight English TTS, MIT licensed, runs on CPU .
- **PocketTTS** — Low-memory TTS for CPU-only environments (EN/FR/DE/PT/IT/ES) .
- **Sherpa-ONNX** — ONNX-optimized TTS for 20+ languages, Apache-2.0 licensed .
- **MOSS-TTS** — 8B-parameter multilingual TTS, Apache-2.0 licensed .
- **GPT-SoVITS** — Voice cloning with 5 languages, MIT licensed .
- **VoxCPM2** — 30-language TTS with cloning, Apache-2.0 licensed .
- **Zonos** — Expressive TTS (upcoming) .
- **ChatTTS** — Optimized for conversational applications .
- **Mimic 3** — Privacy-friendly, offline TTS for embedded systems .
- **OmniVoice** — Local ElevenLabs alternative supporting 646 languages .

**Frameworks for building custom TTS solutions**: Combine **Kokoro-82M** for high-quality TTS with minimal compute . Use **Chatterbox** for MIT-licensed voice cloning with emotion tags . Deploy **XTTS-v2** for multilingual voice cloning with established tooling . Choose **Fish-Speech** for production multilingual voice agents with LLM-based synthesis . Use **Piper** for offline, edge-device TTS . Integrate **Coqui TTS** for research and custom model training . Note that true commercial TTS with premium voice quality, global language coverage, and vendor-supported SLAs (ElevenLabs, Amazon Polly, Azure AI Speech) remains primarily commercial territory; open-source stacks provide strong voice synthesis, cloning, and multilingual foundations that require integration for complete production deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- TTS platforms synthesize speech that may be used for impersonation or misinformation. **Use voice cloning responsibly** — obtain consent, respect local laws, and consider watermarking. Chatterbox includes built-in audio watermarking .
- **License considerations vary significantly** — Kokoro is Apache-2.0, Chatterbox is MIT, XTTS-v2 is MPL-2.0, and some models (Fish-Speech) may have commercial restrictions. Verify licensing before commercial deployment .
- **Open-source TTS quality approaches commercial** — models like Kokoro and Chatterbox produce speech nearly indistinguishable from human recordings . However, premium commercial voices (ElevenLabs) still lead in emotional range and consistency .
- **Hardware requirements vary** — Kokoro runs fast on CPU, while larger models (Fish-Speech 8B, Dia 1.6B) benefit from GPU. Plan infrastructure accordingly .
- The open-source ecosystem provides strong voice synthesis, cloning, and multilingual foundations, but **premium voice quality, global language coverage, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for developers, content creators, and organizations seeking TTS sovereignty.**
Let's make text-to-speech more open, transparent, and accessible.
