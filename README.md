<div align="center">

  <h1>dubbr.</h1>
  <p><strong>A modern, collaborative web & desktop audio/video editor built for creators.</strong></p>

  <p>
    <a href="https://github.com/RybsonBybson/dubbr-releases/releases"><img src="https://img.shields.io/github/v/release/RybsonBybson/dubbr-releases?style=flat-square&color=blue" alt="Release"></a>
    <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=flat-square" alt="Platforms">
    <img src="https://img.shields.io/badge/stack-React%20%7C%20Tauri%20%7C%20Node.js-informational?style=flat-square" alt="Tech Stack">
    <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="License">
  </p>

  <br>
</div>

## ✨ What is dubbr.?

**dubbr.** is a lightning-fast, web-first and desktop-ready audio/video timeline editor designed for smooth collaboration. Whether you are cutting clips, separating vocal stems with AI, syncing multiple tracks, or working live with a team in a lobby — `dubbr.` provides a clean, distraction-free interface powered by modern web tech and native Tauri capabilities.

---

## 🚀 Key Features

*   **🎬 Advanced Timeline & Cutting:** Frame-accurate video/audio trimming, multi-clip selection, and a smooth **Glue (`G`)** tool to merge continuous tracks instantly.
*   **🤖 AI Stem Separation (Demucs):** Local, high-performance vocal and instrument separation directly in the desktop app via context menu (PPM).
*   **⚡ Native FFmpeg Integration:** Zero bloat. Automatically fetches and utilizes native FFmpeg binaries in Tauri for blazing-fast rendering and format conversions without browser memory limits.
*   **👥 Real-Time Collaboration Rooms:** Create lobbies, invite teammates, see active roles via sleek status icons, and enjoy automatic host migration if the original host leaves.
*   **🎵 Reaper (`.rpp` & `.zip`) Support:** Full project importing with automatic asset mapping, fallback track colors matching the `dubbr.` palette, and proper `.mp3`/`.mkv` handling.
*   **🎤 Custom Input Devices:** Choose your preferred microphone input directly from your browser or desktop settings (`navigator.mediaDevices`).
*   **🎨 Minimalist UI / UX:** Built with Tailwind CSS and `shadcn/ui` components, featuring dark mode support and multilingual layout (EN/PL) with crisp flag indicators.

---

## 🛠️ Tech Stack

*   **Frontend:** React, Vite, TypeScript, Tailwind CSS, `shadcn/ui`.
*   **Desktop Wrapper:** Tauri (Rust backend for system integration, native processes, and file system access).
*   **Backend & Realtime:** Node.js, WebSockets, Supabase (Database & Storage with metadata TTL).
*   **Media Processing:** FFmpeg, Demucs (htdemucs).

---

## 📥 Download & Installation

Get the latest installer for your operating system from our public releases repository:

👉 **[Download dubbr. Releases](https://github.com/RybsonBybson/dubbr-releases/releases)**

---

## 💻 Running for Development

If you want to run or contribute to the source code locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/RybsonBybson/dubbr.git](https://github.com/RybsonBybson/dubbr.git)
   cd dubbr
