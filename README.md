# David Martinez Muelas

Software developer building complete products — mobile apps, cloud backends, edge devices, and AI integrations.

📧 [davidmartinezmuelas@gmail.com](mailto:davidmartinezmuelas@gmail.com) · 📍 Spain · 💼 Open to work

---

## Featured Work

### RITA — AI Elder Care Assistant · *Production*

End-to-end system for monitoring elderly people living alone. Built as primary developer and deployed for real users.

- **Raspberry Pi edge device** — voice assistant with wake word, Vosk speech recognition, fall and emergency detection via keyword + LLM semantic analysis, local event queue with offline retry
- **FastAPI backend** — PostgreSQL, 11 background workers (alert escalation, heartbeat monitor, reminders, daily AI scoring), Claude API integration, GitHub Actions CI
- **Flutter caregiver app** — real-time status dashboard, push notifications via Firebase FCM, alert management, multi-device support
- **MQTT over TLS** — real-time bidirectional messaging between edge device and cloud

`Python` `FastAPI` `Flutter` `PostgreSQL` `MQTT` `Raspberry Pi` `Claude` `Groq` `Vosk` `Firebase FCM`

*Code on company GitHub (private)*

---

### [GastroLink](https://github.com/davidmartinezmuelas-tech/GastroLink) — Android Food Ordering App

Android app with nutritional tracking, group orders, and AI meal recommendations. DAM final project.

- Kotlin + Jetpack Compose with MVVM and Clean Architecture (ui / domain / data / model)
- Room 2.6 persistence, Ktor networking, DataStore preferences, real-time macronutrient tracking
- AI assistant and meal recommendations via Groq Llama 3.3 70B through a Node.js proxy backend
- Detekt static analysis and domain layer unit tests

`Kotlin` `Jetpack Compose` `Clean Architecture` `Room` `Ktor` `Node.js` `Groq`

---

### [VAT-validator](https://github.com/davidmartinezmuelas-tech/VAT-validator) — EU VAT Bulk Validator

Desktop tool for validating EU VAT numbers against the official VIES service. Built during internship.

- Excel import with automatic VAT/NIF column detection
- Concurrent validation with rate limiting, exponential backoff, and throttling tolerance
- Tkinter interface with Validated/Pending tabs, activity log, and flexible export options
- Modular architecture: separate layers for UI, SOAP client, scheduling, retry logic, and models

`Python` `Tkinter` `SOAP` `openpyxl` `concurrent.futures`

---

### [broncola](https://github.com/davidmartinezmuelas-tech/broncola) — Flutter Party Game

Cross-platform party game with dynamic card packs, persistent player roster, and photo avatars.

- Card draw system with 3 content packs (49 tiles each) and dynamic question pools
- Per-player photo avatar via camera or gallery, roster persists across sessions
- SharedPreferences local storage, cross-platform Flutter codebase

`Flutter` `Dart` `SharedPreferences` `image_picker`

---

### [Vestigios](https://github.com/davidmartinezmuelas-tech/Vestigios) — Dark Fantasy RPG *(in development)*

Narrative RPG in Godot 4 with complete design foundation and implementation starting.

- Two kingdoms at war over a hidden cosmic conspiracy; 5 playable characters, 8+ NPCs, 4 regions
- Planned systems: tactical combat, skill-check dialogue, corruption zones, champion mechanics
- Full GDD, Game Dev Bible, lore docs, and Godot 4 architecture defined before first line of code

`Godot 4` `GDScript`

---

## Tech Stack

**Mobile** — Kotlin, Jetpack Compose, Flutter, Dart  
**Backend** — Python, FastAPI, Node.js, PostgreSQL, Alembic  
**AI / Voice** — Claude, Groq, Vosk STT, llama.cpp  
**Infrastructure** — Raspberry Pi, MQTT, Docker, Firebase FCM, GitHub Actions  
**Architecture** — Clean Architecture, MVVM, REST, background workers, event-driven systems

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=davidmartinezmuelas-tech&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=davidmartinezmuelas-tech&layout=compact&theme=github_dark&hide_border=true&count_private=true" height="150" />
</p>
