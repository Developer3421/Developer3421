<!-- PORTFOLIO – Oleg Kurylo | Developer3421 -->

<div align="center">

# Oleg Kurylo — Developer Portfolio

**🇺🇦 From Ukraine · 🇩🇪 Based in Germany · 💻 C# · Avalonia UI · .NET · React · PHP**

[![GitHub](https://img.shields.io/badge/GitHub-Developer3421-181717?style=flat&logo=github)](https://github.com/Developer3421)
[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-My%20Apps-0078D4?style=flat&logo=microsoft)](https://apps.microsoft.com)
[![Insait Apps Website](https://img.shields.io/badge/Website-Insait%20Apps-6A0DAD?style=flat&logo=googlechrome)](http://linsaitplatform.mywebcommunity.org)

</div>

---

# 🇬🇧 English

## About Me

I'm **Oleg Kurylo**, a self-taught C# desktop developer originally from **Ukraine**, currently living in **Germany**.

My journey started in **2021** with small C# **WinForms** applications. After moving to Germany in **2022**, I continued evolving and spent **2023–2024** building more advanced C# **WPF** applications. In **2025** I migrated everything to the cross-platform **Avalonia UI** framework, completing and polishing all my desktop apps. In winter **2025** I began publishing my apps to the **Microsoft Store**.

Today I have **11 unique desktop applications** available on the Microsoft Store, all built around a *multi-window philosophy* and integrating either **external APIs** or **local AI** components. My flagship project is **Vetale Browser** — a full-featured Avalonia/Chromium browser with an embedded **Gemma 3 1B** local AI model that runs even on older hardware. The official **Insait Apps** platform website is at [linsaitplatform.mywebcommunity.org](http://linsaitplatform.mywebcommunity.org).

Most recently I created my first **web applications** (React + TypeScript) and built a **hybrid Avalonia C# + React** desktop application. In early **2026** I also developed a **PHP portfolio website** featuring five interactive mini-applications (Calculator, To-Do, Quiz, BMI Calculator, Unit Converter) — all built in pure PHP without any external frameworks.

---

## 🛠️ Tech Stack

| Area | Technologies |
|---|---|
| **Primary language** | C# |
| **Desktop UI** | Avalonia UI 11, WPF, WinForms |
| **Web / Hybrid** | React 19, TypeScript, Vite, Tailwind CSS |
| **Server-side web** | PHP 8.0+, HTML5, CSS3, vanilla JavaScript |
| **Runtime** | .NET 10, .NET 9, .NET Framework 4.8 |
| **Web rendering** | WebViewControl-Avalonia (Chromium), CefSharp, Microsoft WebView2 |
| **Local AI** | LLamaSharp, Gemma 3 1B, Whisper.net |
| **Automation** | Microsoft Playwright |
| **Database** | LiteDB, Windows DPAPI (AES-256) |
| **Compiler tools** | Microsoft Roslyn, MSBuild |
| **Media** | LibVLCSharp |
| **Hardware monitoring** | LibreHardwareMonitor, WMI |
| **Source control** | LibGit2, Octokit |

---

## 📅 Developer Journey

```
2021  ──▶  First C# WinForms apps (Ukraine)
2022  ──▶  Moved to Germany · continued C# development
2023  ──▶  Switched to C# WPF · growing app complexity
2024  ──▶  WPF apps refined · Vetale Browser (WPF legacy) released
2025  ──▶  Migrated all projects to Avalonia UI
            Gemma 3 1B local AI integrated
            11 apps published to Microsoft Store (winter 2025)
            First React web apps & hybrid Avalonia + React app
2026  ──▶  PHP portfolio website with 5 interactive mini-apps
```

---

## 🖥️ Desktop Applications (Microsoft Store)

### 🌐 Vetale Browser *(Flagship)*
> A modern Windows browser with local AI, a highly customizable UI, and built-in tools for power users.

- Avalonia UI + WebViewControl-Avalonia (Chromium-based rendering)
- **Embedded Gemma 3 1B local AI** — runs offline, even on older hardware
- Voice input via Whisper.net pipeline
- Multi-window tab workflow with drag & drop
- Built-in DevTools / automation via Microsoft Playwright
- GDPR-style user agreement & local-only data storage
- **Target:** .NET 10 · `win-x64`, `win-x86`, `win-arm64`

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20Vetale%20Browser-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9P2XG1K9CVMH)
[![GitHub](https://img.shields.io/badge/GitHub-Vetale--Browser--Official-181717?logo=github)](https://github.com/Developer3421/Vetale-Browser-Official)
[![Source Code](https://img.shields.io/badge/GitHub-VetaleBrowserCode-181717?logo=github)](https://github.com/Developer3421/VetaleBrowserCode)

---

### 📝 Insait Text Editor
> Intelligent text editor with an offline-first local AI assistant.

- Full MVVM architecture with modular services
- Local AI inference (LLamaSharp) — no cloud dependency
- Multilingual UI
- **Stack:** C# · .NET 10 · Avalonia UI · LLamaSharp · LiteDB · SkiaSharp

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20Insait%20Text%20Editor-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PMDTL9PRP7J)
[![GitHub](https://img.shields.io/badge/GitHub-Insait--Text--Editor-181717?logo=github)](https://github.com/Developer3421/Insait-Text-Editor)

---

### 🛠️ Insait Edit — C# IDE
> A modern, cross-platform IDE for C# and .NET development built on Avalonia UI and the Roslyn compiler platform.

- Full Roslyn integration: IntelliSense, code fixes, rename refactoring
- MSBuild integration: build, run, and publish .NET projects
- Embedded ConPTY terminal emulator with ANSI rendering
- Git & GitHub integration (commit, push, pull, diff, clone)
- NuGet package manager & MSIX manager built in
- ESP32 / nanoFramework support with visual LED panel designer
- AXAML live preview for Avalonia UI files
- Multilingual UI (English, Ukrainian, German, Russian, Turkish)
- Gemini AI assistant for code help and translation
- **Stack:** C# · .NET 10 · Avalonia UI 11.3 · Roslyn 5.0 · MSBuild · LibGit2 · NuGet.Protocol · Octokit · LiteDB · nanoFramework

[![GitHub](https://img.shields.io/badge/GitHub-Insait--Edit--C--Sharp-181717?logo=github)](https://github.com/Developer3421/Insait-Edit-C-Sharp)

---

### 🎬 Insait Video Player
> Feature-rich desktop video player with session management and encrypted data storage.

- Tab interface with drag-to-reorder and overflow menu
- Session management with Windows DPAPI-encrypted storage
- Subtitle management and audio track selection
- **Stack:** C# · .NET 10 · Avalonia UI 11.3 · LibVLCSharp · LiteDB · Windows DPAPI

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20Insait%20Video%20Player-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PKXCQFWDNFQ)
[![GitHub](https://img.shields.io/badge/GitHub-Insait--Video--Player-181717?logo=github)](https://github.com/Developer3421/Insait-Video-Player)

---

### 🌍 Insait Translator: German *(Hybrid App)*
> Hybrid Avalonia C# + React app that translates any language into German with optional Text-to-Speech.

- **Hybrid architecture:** Avalonia desktop shell with embedded React web UI
- Multi-provider fallback system (MyMemory → Google Translate → Gemini API)
- Local HTTP backend server for the React UI — no Node.js runtime required
- German TTS via Piper — playback and MP3 export
- AES-256 + Windows DPAPI encrypted settings
- **Stack:** C# · .NET 10 · Avalonia UI 11 · ReactiveUI · React/Vite · LiteDB · Piper TTS · NAudio · AES-256

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20Insait%20Translator-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PH8XTJ8BCJ7)
[![GitHub](https://img.shields.io/badge/GitHub-Insait_Translator_German-181717?logo=github)](https://github.com/Developer3421/Insait_Translator_German)

---

### 📅 German B1 – Step Further
> Structured German-language learning app (B1 level) with integrated AI assistant.

- 4 sections × 18 topics: vocabulary, conversation, grammar, exercises
- Session management with bookmark functionality
- Gemma-3-270m local AI for personalized learning support
- **Stack:** C# · .NET 10 · Avalonia UI · LiteDB · LLamaSharp

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20German%20B1-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9P6F8KJJWTJ5)
[![GitHub](https://img.shields.io/badge/GitHub-german--b1--step--further-181717?logo=github)](https://github.com/Developer3421/german-b1-step-further)

---

### 📁 FileManager
> Modern, lightweight file manager with multi-tab navigation.

- Multi-tab navigation with persistent tab restore on startup
- Native Windows Shell context menus
- Built-in image viewer · Drive usage display
- Multilingual (English, Ukrainian, German)
- **Stack:** C# · .NET · Avalonia UI

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20FileManager-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PH9GFGXJDHK)
[![GitHub](https://img.shields.io/badge/GitHub-FileManager-181717?logo=github)](https://github.com/Developer3421/FileManager)

---

### 📊 V-Task — System Resource Monitor
> Slim, modern real-time system monitor for CPU, RAM, GPU, disk, and network.

- Configurable refresh rate · 5 languages
- No telemetry, no network access — all data stays local
- **Stack:** C# · .NET 10 · Avalonia UI 11.3 · LibreHardwareMonitor · LiteDB · WMI

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20V--Task-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9P405177WBX9)
[![GitHub](https://img.shields.io/badge/GitHub-V--Task-181717?logo=github)](https://github.com/Developer3421/V-Task)

---

### ⏱️ VRelaxTimer
> Lightweight focus and relaxation timer with a local AI text assistant.

- Minimalist UX · Single-file deployment · Fully offline
- **Stack:** C# · .NET 9 · WPF · LLamaSharp

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20VRelaxTimer-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PBNDBFZ1JKK)
[![GitHub](https://img.shields.io/badge/GitHub-VRelaxTimer-181717?logo=github)](https://github.com/Developer3421/VRelaxTimer)

---

### 🧮 VCalc — Scientific Calculator
> Elegant scientific calculator with full keyboard support and multi-window mode.

- sin, cos, tan, log, ln, power, π, e · Numpad support
- Multiple windows open simultaneously
- No network access, no telemetry
- **Stack:** C# · .NET 10 · WPF

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20VCalc-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9NCBKT3KXS5F)
[![GitHub](https://img.shields.io/badge/GitHub-VCalc-181717?logo=github)](https://github.com/Developer3421/VCalc)

---

### 🌐 Vetale Browser Super Lite
> Minimalist Chromium-based desktop browser focused on stability and low resource usage.

- Built on CefSharp (embedded Chromium)
- **Stack:** C# · WPF · .NET Framework 4.8 · CefSharp

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Get%20Super%20Lite-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9NZPNGDCQX2P)
[![GitHub](https://img.shields.io/badge/GitHub-Vetale--Browser--SuperLite-181717?logo=github)](https://github.com/Developer3421/Vetale-Browser-SuperLite)

---

## 🌍 Web Applications

### 📝 WebInsait Text Editor
Rich-text editor in the browser — the web counterpart of the desktop Insait Text Editor.
- React 19 · TypeScript · Vite · Tailwind CSS · shadcn/ui

🔗 [webinsaittexteditor--Developer3421.github.app](https://webinsaittexteditor--Developer3421.github.app)

### ♟️ Chess & Translate
Chess game with integrated real-time multilingual translation — powered by an LLM.
- React 19 · TypeScript · Spark Runtime SDK (LLM + KV Storage)

🔗 [chess-translator-app--Developer3421.github.app](https://chess-translator-app--Developer3421.github.app)

### 🔑 Password Generator
Secure, client-side password generator — no data leaves the browser.
- React 19 · TypeScript · Vite · Tailwind CSS

🔗 [password-generator--Developer3421.github.app](https://password-generator--Developer3421.github.app)

---

## 🐘 PHP Web Applications

### 🌐 PHP Portfolio Website
> Personal portfolio website built with pure PHP — no frameworks, bilingual (EN/DE), dark theme, and five interactive mini-apps.

- **Bilingual interface** — switch between English and German (session-based)
- **Dark theme** — purple/orange colour scheme with CSS custom properties
- **Responsive layout** — fluid grids and `clamp()` typography
- **Stack:** PHP 8.0+, HTML5, CSS3, vanilla JavaScript

**Interactive Mini-Apps:**

| App | Description |
|---|---|
| 🧮 Calculator | Arithmetic calculator with operator precedence — custom expression parser, no `eval()` |
| 📋 To-Do List | Task manager with localStorage persistence, timestamps and completion toggling |
| 🎯 PHP Quiz | 10-question PHP knowledge quiz with server-side session state and progress bar |
| ⚖️ BMI Calculator | Metric & imperial BMI calculator with category classification and health tips |
| 🔄 Unit Converter | Converts temperature, length, weight and volume using PHP 8 `match` expressions |

[![GitHub](https://img.shields.io/badge/GitHub-PhpPortfolioWebsite-181717?logo=github)](https://github.com/Developer3421/PhpPortfolioWebsite)

---

## 🏛️ Legacy / Historical Projects

| Project | Year | Description |
|---|---|---|
| [Vetale Browser Legacy (WPF, 2024)](https://github.com/Developer3421/Vetale-Browser-Legacy-WPF-2024-) | 2024 | First-generation WPF browser using Microsoft WebView2 — foundation for all later versions |
| [Test](https://github.com/Developer3421/Test) | 2021 | First repository ever created — a historic milestone |

---

## 📊 All Repositories

| Repository | Language | Description |
|---|---|---|
| [Vetale-Browser-Official](https://github.com/Developer3421/Vetale-Browser-Official) | — | Flagship browser (docs & distribution) |
| [VetaleBrowserCode](https://github.com/Developer3421/VetaleBrowserCode) | C# | Vetale Browser source code |
| [Insait-Text-Editor](https://github.com/Developer3421/Insait-Text-Editor) | C# | AI-powered text editor |
| [Insait-Edit-C-Sharp](https://github.com/Developer3421/Insait-Edit-C-Sharp) | C# | Full-featured C# IDE |
| [Insait-Video-Player](https://github.com/Developer3421/Insait-Video-Player) | C# | Desktop video player |
| [Insait_Translator_German](https://github.com/Developer3421/Insait_Translator_German) | C# | Hybrid translator (Avalonia + React) |
| [german-b1-step-further](https://github.com/Developer3421/german-b1-step-further) | C# | German B1 learning app |
| [FileManager](https://github.com/Developer3421/FileManager) | C# | Multi-tab file manager |
| [V-Task](https://github.com/Developer3421/V-Task) | C# | System resource monitor |
| [VRelaxTimer](https://github.com/Developer3421/VRelaxTimer) | C# | Relaxation timer with AI |
| [VCalc](https://github.com/Developer3421/VCalc) | C# | Scientific calculator |
| [Vetale-Browser-SuperLite](https://github.com/Developer3421/Vetale-Browser-SuperLite) | C# | Minimal Chromium browser |
| [Vetale-Browser-Legacy-WPF-2024-](https://github.com/Developer3421/Vetale-Browser-Legacy-WPF-2024-) | — | Historical WPF browser |
| [Web-Projects](https://github.com/Developer3421/Web-Projects) | — | React web apps collection |
| [PhpPortfolioWebsite](https://github.com/Developer3421/PhpPortfolioWebsite) | PHP | PHP portfolio with 5 interactive mini-apps |
| [CSharp-Portfolio](https://github.com/Developer3421/CSharp-Portfolio) | — | HR portfolio with Store statistics |

---

---

# 🇩🇪 Deutsch

## Über mich

Ich bin **Oleg Kurylo**, ein autodidaktischer C#-Desktop-Entwickler aus der **Ukraine**, der aktuell in **Deutschland** lebt.

Meine Entwicklerreise begann **2021** mit kleinen C#-**WinForms**-Anwendungen. Nach meiner Übersiedlung nach Deutschland im Jahr **2022** entwickelte ich mich weiter und arbeitete **2023–2024** an fortgeschritteneren C#-**WPF**-Projekten. Im Jahr **2025** migrierte ich alle Projekte auf das plattformübergreifende **Avalonia UI**-Framework und schloss alle Desktop-Apps ab. Im Winter **2025** begann ich, meine Apps im **Microsoft Store** zu veröffentlichen.

Heute verfüge ich über **11 einzigartige Desktop-Anwendungen** im Microsoft Store, die alle auf einer *Multi-Window-Philosophie* basieren und entweder **externe APIs** oder **lokale KI**-Komponenten integrieren. Mein Hauptprojekt ist **Vetale Browser** — ein vollwertiger Avalonia/Chromium-Browser mit eingebettetem **Gemma 3 1B**-KI-Modell, das auch auf älterer Hardware offline läuft. Die offizielle **Insait Apps**-Plattform-Website ist unter [linsaitplatform.mywebcommunity.org](http://linsaitplatform.mywebcommunity.org) erreichbar.

Kürzlich habe ich meine ersten **Web-Anwendungen** (React + TypeScript) sowie eine **hybride Avalonia C# + React**-Desktop-Applikation entwickelt. Anfang **2026** entwickelte ich zusätzlich eine **PHP-Portfolio-Website** mit fünf interaktiven Mini-Apps (Rechner, Aufgabenliste, Quiz, BMI-Rechner, Einheitenkonverter) — ausschließlich in reinem PHP ohne externe Frameworks.

---

## 🛠️ Technologie-Stack

| Bereich | Technologien |
|---|---|
| **Hauptsprache** | C# |
| **Desktop-UI** | Avalonia UI 11, WPF, WinForms |
| **Web / Hybrid** | React 19, TypeScript, Vite, Tailwind CSS |
| **Serverseitiges Web** | PHP 8.0+, HTML5, CSS3, vanilla JavaScript |
| **Laufzeit** | .NET 10, .NET 9, .NET Framework 4.8 |
| **Web-Rendering** | WebViewControl-Avalonia (Chromium), CefSharp, Microsoft WebView2 |
| **Lokale KI** | LLamaSharp, Gemma 3 1B, Whisper.net |
| **Automatisierung** | Microsoft Playwright |
| **Datenbank** | LiteDB, Windows DPAPI (AES-256) |
| **Compiler-Tools** | Microsoft Roslyn, MSBuild |
| **Medien** | LibVLCSharp |
| **Hardware-Monitoring** | LibreHardwareMonitor, WMI |
| **Versionskontrolle** | LibGit2, Octokit |

---

## 📅 Entwickler-Zeitlinie

```
2021  ──▶  Erste C# WinForms-Projekte (Ukraine)
2022  ──▶  Umzug nach Deutschland · C#-Entwicklung fortgesetzt
2023  ──▶  Wechsel zu C# WPF · wachsende App-Komplexität
2024  ──▶  WPF-Apps verfeinert · Vetale Browser (WPF Legacy) veröffentlicht
2025  ──▶  Alle Projekte auf Avalonia UI migriert
            Gemma 3 1B lokal-KI integriert
            11 Apps im Microsoft Store veröffentlicht (Winter 2025)
            Erste React-Web-Apps & hybride Avalonia + React App
2026  ──▶  PHP-Portfolio-Website mit 5 interaktiven Mini-Apps
```

---

## 🖥️ Desktop-Anwendungen (Microsoft Store)

### 🌐 Vetale Browser *(Flagship)*
> Moderner Windows-Browser mit lokaler KI, hochgradig anpassbarer Benutzeroberfläche und integrierten Tools für Power-User.

- Avalonia UI + WebViewControl-Avalonia (Chromium-basiertes Rendering)
- **Eingebettetes Gemma 3 1B lokal-KI-Modell** — offline, auch auf älterer Hardware
- Spracheingabe via Whisper.net-Pipeline
- Multi-Window-Tab-Workflow mit Drag & Drop
- Integrierte DevTools / Automatisierung via Microsoft Playwright
- DSGVO-konformes Benutzerabkommen & lokale Datenspeicherung
- **Ziel:** .NET 10 · `win-x64`, `win-x86`, `win-arm64`

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Vetale%20Browser%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9P2XG1K9CVMH)
[![GitHub](https://img.shields.io/badge/GitHub-Vetale--Browser--Official-181717?logo=github)](https://github.com/Developer3421/Vetale-Browser-Official)
[![Quellcode](https://img.shields.io/badge/GitHub-VetaleBrowserCode-181717?logo=github)](https://github.com/Developer3421/VetaleBrowserCode)

---

### 📝 Insait Text Editor
> Intelligenter Texteditor mit offline-fähigem KI-Assistenten (Offline-First).

- Vollständige MVVM-Architektur mit modularen Services
- Lokale KI-Inferenz (LLamaSharp) — keine Cloud-Abhängigkeit
- Mehrsprachige Benutzeroberfläche
- **Stack:** C# · .NET 10 · Avalonia UI · LLamaSharp · LiteDB · SkiaSharp

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Insait%20Text%20Editor%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PMDTL9PRP7J)
[![GitHub](https://img.shields.io/badge/GitHub-Insait--Text--Editor-181717?logo=github)](https://github.com/Developer3421/Insait-Text-Editor)

---

### 🛠️ Insait Edit — C#-IDE
> Moderne, plattformübergreifende Entwicklungsumgebung für C# und .NET auf Basis von Avalonia UI und der Roslyn-Compiler-Plattform.

- Vollständige Roslyn-Integration: IntelliSense, Code-Fixes, symbolweites Umbenennen
- MSBuild-Integration zum Erstellen, Ausführen und Veröffentlichen von .NET-Projekten
- Eingebetteter ConPTY-Terminal-Emulator mit ANSI-Rendering
- Git- und GitHub-Integration (Commit, Push, Pull, Diff, Klonen)
- NuGet-Paketverwaltung und MSIX-Manager direkt in der IDE
- ESP32-/nanoFramework-Unterstützung mit visuellem LED-Panel-Designer
- AXAML-Live-Vorschau für Avalonia-UI-Dateien
- Mehrsprachige Oberfläche (Englisch, Ukrainisch, Deutsch, Russisch, Türkisch)
- Gemini-KI-Assistent für Code-Unterstützung
- **Stack:** C# · .NET 10 · Avalonia UI 11.3 · Roslyn 5.0 · MSBuild · LibGit2 · NuGet.Protocol · Octokit · LiteDB · nanoFramework

[![GitHub](https://img.shields.io/badge/GitHub-Insait--Edit--C--Sharp-181717?logo=github)](https://github.com/Developer3421/Insait-Edit-C-Sharp)

---

### 🎬 Insait Video Player
> Funktionsreicher Desktop-Videoplayer mit Sitzungsverwaltung und verschlüsselter Datenspeicherung.

- Tab-Interface mit Drag-to-Reorder und Überlaufmenü
- Sitzungsverwaltung mit Windows-DPAPI-verschlüsselter Speicherung
- Untertitelverwaltung und Audiospurauswahl
- **Stack:** C# · .NET 10 · Avalonia UI 11.3 · LibVLCSharp · LiteDB · Windows DPAPI

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Insait%20Video%20Player%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PKXCQFWDNFQ)
[![GitHub](https://img.shields.io/badge/GitHub-Insait--Video--Player-181717?logo=github)](https://github.com/Developer3421/Insait-Video-Player)

---

### 🌍 Insait Translator: German *(Hybrid-App)*
> Hybride Avalonia C# + React App zum Übersetzen beliebiger Sprachen ins Deutsche mit optionaler Text-to-Speech-Funktion.

- **Hybride Architektur:** Avalonia-Desktop-Shell mit eingebettetem React-Web-UI
- Anbieter-Fallback-System (MyMemory → Google Translate → Gemini API)
- Lokaler HTTP-Backend-Server für die React-UI — kein Node.js zur Laufzeit erforderlich
- Deutsch-TTS via Piper — Wiedergabe und MP3-Export
- AES-256 + Windows-DPAPI-verschlüsselte Einstellungen
- **Stack:** C# · .NET 10 · Avalonia UI 11 · ReactiveUI · React/Vite · LiteDB · Piper TTS · NAudio · AES-256

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Insait%20Translator%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PH8XTJ8BCJ7)
[![GitHub](https://img.shields.io/badge/GitHub-Insait_Translator_German-181717?logo=github)](https://github.com/Developer3421/Insait_Translator_German)

---

### 📅 German B1 – Ein Schritt weiter
> Strukturierte Deutschlern-App (B1-Niveau) mit integriertem KI-Assistenten.

- 4 Abschnitte × 18 Themen: Wortschatz, Konversation, Grammatik, Übungen
- Sitzungsverwaltung mit Lesezeichenfunktion
- Gemma-3-270m lokale KI für personalisierte Lernunterstützung
- **Stack:** C# · .NET 10 · Avalonia UI · LiteDB · LLamaSharp

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-German%20B1%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9P6F8KJJWTJ5)
[![GitHub](https://img.shields.io/badge/GitHub-german--b1--step--further-181717?logo=github)](https://github.com/Developer3421/german-b1-step-further)

---

### 📁 FileManager
> Moderner, leichtgewichtiger Dateimanager mit Multi-Tab-Navigation.

- Multi-Tab-Navigation mit persistenter Tab-Wiederherstellung beim Start
- Native Windows-Shell-Kontextmenüs
- Eingebetteter Bildbetrachter · Laufwerksanzeige mit Nutzungsinformationen
- Mehrsprachig (Englisch, Ukrainisch, Deutsch)
- **Stack:** C# · .NET · Avalonia UI

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-FileManager%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PH9GFGXJDHK)
[![GitHub](https://img.shields.io/badge/GitHub-FileManager-181717?logo=github)](https://github.com/Developer3421/FileManager)

---

### 📊 V-Task — Systemressourcen-Monitor
> Schlanker, moderner Echtzeit-Systemmonitor für CPU, RAM, GPU, Festplatte und Netzwerk.

- Konfigurierbare Aktualisierungsrate · 5 Sprachen
- Keine Telemetrie, kein Netzwerkzugriff — alle Daten verbleiben lokal
- **Stack:** C# · .NET 10 · Avalonia UI 11.3 · LibreHardwareMonitor · LiteDB · WMI

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-V--Task%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9P405177WBX9)
[![GitHub](https://img.shields.io/badge/GitHub-V--Task-181717?logo=github)](https://github.com/Developer3421/V-Task)

---

### ⏱️ VRelaxTimer
> Leichtgewichtige Desktop-Anwendung für Fokus und Entspannung mit lokalem KI-Textassistenten.

- Minimalistisches UX · Single-File-Deployment · Vollständig offline
- **Stack:** C# · .NET 9 · WPF · LLamaSharp

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-VRelaxTimer%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9PBNDBFZ1JKK)
[![GitHub](https://img.shields.io/badge/GitHub-VRelaxTimer-181717?logo=github)](https://github.com/Developer3421/VRelaxTimer)

---

### 🧮 VCalc — Wissenschaftlicher Taschenrechner
> Eleganter wissenschaftlicher Taschenrechner mit vollständiger Tastaturunterstützung und Multi-Window-Modus.

- sin, cos, tan, log, ln, Potenz, π, e · Nummernblock-Unterstützung
- Mehrere Fenster gleichzeitig geöffnet
- Kein Netzwerkzugriff, keine Telemetrie
- **Stack:** C# · .NET 10 · WPF

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-VCalc%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9NCBKT3KXS5F)
[![GitHub](https://img.shields.io/badge/GitHub-VCalc-181717?logo=github)](https://github.com/Developer3421/VCalc)

---

### 🌐 Vetale Browser Super Lite
> Minimalistischer Chromium-basierter Desktop-Browser mit Fokus auf Stabilität und geringer Ressourcennutzung.

- Basiert auf CefSharp (eingebettetes Chromium)
- **Stack:** C# · WPF · .NET Framework 4.8 · CefSharp

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Super%20Lite%20herunterladen-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9NZPNGDCQX2P)
[![GitHub](https://img.shields.io/badge/GitHub-Vetale--Browser--SuperLite-181717?logo=github)](https://github.com/Developer3421/Vetale-Browser-SuperLite)

---

## 🌍 Web-Anwendungen

### 📝 WebInsait Text Editor
Rich-Text-Editor im Browser — die Web-Version des Desktop Insait Text Editors.
- React 19 · TypeScript · Vite · Tailwind CSS · shadcn/ui

🔗 [webinsaittexteditor--Developer3421.github.app](https://webinsaittexteditor--Developer3421.github.app)

### ♟️ Chess & Translate
Schachspiel mit integrierter Echtzeit-Mehrsprachen-Übersetzung — KI-gestützt.
- React 19 · TypeScript · Spark Runtime SDK (LLM + KV Storage)

🔗 [chess-translator-app--Developer3421.github.app](https://chess-translator-app--Developer3421.github.app)

### 🔑 Password Generator
Sicherer, clientseitiger Passwort-Generator — keine Daten verlassen den Browser.
- React 19 · TypeScript · Vite · Tailwind CSS

🔗 [password-generator--Developer3421.github.app](https://password-generator--Developer3421.github.app)

---

## 🐘 PHP-Webanwendungen

### 🌐 PHP-Portfolio-Website
> Persönliche Portfolio-Website in reinem PHP — kein Framework, zweisprachig (EN/DE), Dark Theme und fünf interaktive Mini-Apps.

- **Zweisprachige Oberfläche** — jederzeit zwischen Englisch und Deutsch wechselbar (session-basiert)
- **Dark Theme** — lila/orangefarbenes Farbschema mit CSS Custom Properties
- **Responsives Layout** — Fluid Grids und `clamp()`-Typografie für alle Bildschirmgrößen
- **Stack:** PHP 8.0+, HTML5, CSS3, vanilla JavaScript

**Interaktive Mini-Apps:**

| App | Beschreibung |
|---|---|
| 🧮 Rechner | Arithmetischer Rechner mit Operatorpriorität — sicherer benutzerdefinierter Parser, kein `eval()` |
| 📋 Aufgabenliste | Aufgabenmanager mit localStorage-Persistenz, Zeitstempeln und Erledigungsfunktion |
| 🎯 PHP-Quiz | 10-Fragen-PHP-Quiz mit serverseitigem Session-Tracking und Fortschrittsanzeige |
| ⚖️ BMI-Rechner | BMI-Rechner für metrische & imperiale Einheiten mit Kategorieklassifizierung und Gesundheitstipps |
| 🔄 Einheitenkonverter | Konvertiert Temperatur, Länge, Gewicht und Volumen mit PHP 8 `match`-Ausdrücken |

[![GitHub](https://img.shields.io/badge/GitHub-PhpPortfolioWebsite-181717?logo=github)](https://github.com/Developer3421/PhpPortfolioWebsite)

---

## 🏛️ Legacy- / Historische Projekte

| Projekt | Jahr | Beschreibung |
|---|---|---|
| [Vetale Browser Legacy (WPF, 2024)](https://github.com/Developer3421/Vetale-Browser-Legacy-WPF-2024-) | 2024 | Erste WPF-Browser-Generation mit Microsoft WebView2 — Grundlage für alle späteren Versionen |
| [Test](https://github.com/Developer3421/Test) | 2021 | Allererste Repository — ein historischer Meilenstein |

---

## 📊 Alle Repositories

| Repository | Sprache | Beschreibung |
|---|---|---|
| [Vetale-Browser-Official](https://github.com/Developer3421/Vetale-Browser-Official) | — | Flagship-Browser (Docs & Distribution) |
| [VetaleBrowserCode](https://github.com/Developer3421/VetaleBrowserCode) | C# | Vetale Browser Quellcode |
| [Insait-Text-Editor](https://github.com/Developer3421/Insait-Text-Editor) | C# | KI-gestützter Texteditor |
| [Insait-Edit-C-Sharp](https://github.com/Developer3421/Insait-Edit-C-Sharp) | C# | Vollständige C#-IDE |
| [Insait-Video-Player](https://github.com/Developer3421/Insait-Video-Player) | C# | Desktop-Videoplayer |
| [Insait_Translator_German](https://github.com/Developer3421/Insait_Translator_German) | C# | Hybrid-Übersetzer (Avalonia + React) |
| [german-b1-step-further](https://github.com/Developer3421/german-b1-step-further) | C# | Deutschlern-App B1 |
| [FileManager](https://github.com/Developer3421/FileManager) | C# | Multi-Tab-Dateimanager |
| [V-Task](https://github.com/Developer3421/V-Task) | C# | Systemressourcen-Monitor |
| [VRelaxTimer](https://github.com/Developer3421/VRelaxTimer) | C# | Entspannungstimer mit KI |
| [VCalc](https://github.com/Developer3421/VCalc) | C# | Wissenschaftlicher Taschenrechner |
| [Vetale-Browser-SuperLite](https://github.com/Developer3421/Vetale-Browser-SuperLite) | C# | Minimaler Chromium-Browser |
| [Vetale-Browser-Legacy-WPF-2024-](https://github.com/Developer3421/Vetale-Browser-Legacy-WPF-2024-) | — | Historischer WPF-Browser |
| [Web-Projects](https://github.com/Developer3421/Web-Projects) | — | React-Web-App-Sammlung |
| [PhpPortfolioWebsite](https://github.com/Developer3421/PhpPortfolioWebsite) | PHP | PHP-Portfolio mit 5 interaktiven Mini-Apps |
| [CSharp-Portfolio](https://github.com/Developer3421/CSharp-Portfolio) | — | HR-Portfolio mit Store-Statistiken |

---

<div align="center">

**© 2021–2026 Oleg Kurylo** · 🇺🇦 Ukraine · ��🇪 Germany

*Self-taught · Privacy-first · Local-AI advocate*

</div>
