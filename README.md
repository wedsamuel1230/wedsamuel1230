# Hi, I'm Samuel F.

Student developer building practical projects across embedded systems, robotics, and AI-assisted developer tooling.

I work across hardware and software—from Arduino, ESP32, and Raspberry Pi Pico firmware to desktop apps, mobile integrations, and reusable workflow tools. This profile is a record of learning through projects that are documented, testable, and useful.

[About Me](#about-me) · [Learning](#what-im-currently-learning) · [Skills](#technical-skills) · [Projects](#featured-projects) · [Interests](#areas-of-interest)

## About Me

- I enjoy connecting sensors, devices, applications, and automation into one understandable system.
- My public work includes embedded libraries, robotics prototypes, cross-platform applications, and Python-based developer tools.
- I’m open to collaborating on thoughtful projects involving embedded systems, robotics, IoT, or practical AI.

## What I'm Currently Learning

Recent projects show me exploring:

- Cross-platform desktop development with SvelteKit, TypeScript, Tauri, and Rust, including PDF parsing and Notion integrations.
- Reliable embedded workflows: non-blocking sensor parsers, OTA updates, board-specific examples, and hardware-aware CI.
- Reusable AI and agent tooling with MCP, local document retrieval, stable JSON output, validation, and evaluation workflows.

## How I Work

Across recent repositories, I practice:

- documenting hardware assumptions and the boundary between compile evidence and real-device behavior;
- adding repeatable checks with GitHub Actions, Arduino CLI, unit tests, and end-to-end tests; and
- turning recurring lessons into reusable libraries, skills, scripts, and clear documentation.

## Technical Skills

These are technologies and tools used or explored in my public repositories:

- **Languages:** C++, Python, TypeScript, JavaScript, Kotlin, Rust, HTML, and CSS
- **Embedded:** Arduino-compatible boards, ESP32/ESP32-S3, Raspberry Pi Pico W/Pico 2 W, UART, I2C, Wi-Fi, BLE, OTA, sensors, and motor control
- **Applications:** SvelteKit, Tauri 2, Vite, Jetpack Compose, Room, Firebase, and Notion API integrations
- **AI and tooling:** MCP servers, local RAG workflows, agent skills, document processing, and automation
- **Quality and delivery:** Arduino CLI, GitHub Actions, CMake, Gradle, `uv`, pytest, Vitest, and Playwright

## Featured Projects

### [PDF to Calendar](https://github.com/wedsamuel1230/pdf-to-calendar)

A cross-platform desktop app that parses timetable PDFs and imports event rows into Notion databases.

- **Tech:** SvelteKit, TypeScript, Tauri 2, Rust, `pdfjs-dist`, Zod, and OS keychain storage
- **Notable:** GitHub Actions validates the frontend and backend across macOS, Windows, and Linux, with Playwright end-to-end tests included

### [BottleSumo 2026](https://github.com/wedsamuel1230/BottleSumo-2026)

An ESP32-S3 BottleSumo robotics project containing firmware, PCB, 3D model, and competition documentation. Its test firmware brings together QRE1113 line sensors, VL53L0X time-of-flight sensing, motor PWM/direction, and feedback interrupts.

- **Tech:** C++, Arduino, ESP32-S3, I2C, PWM, interrupts, and hardware documentation
- **Notable:** GitHub Actions compiles the Arduino sketches with pinned Arduino CLI and ESP32 toolchain versions

### [LD2402](https://github.com/wedsamuel1230/LD2402)

A non-blocking Arduino library for the HLK-LD2402 mmWave presence and distance sensor.

- **Tech:** C++, Arduino `Stream`, UART, fixed-size buffers, moving-average filtering, and GPIO debouncing
- **Notable:** board-specific examples cover Pico, ESP32, ESP32-S3, UNO, UNO R4, and UNO Q without blocking reads or dynamic allocation

### [PICO_OTA](https://github.com/wedsamuel1230/Pico_OTA)

An MIT-licensed Arduino library for wireless updates on Raspberry Pi Pico W and Pico 2 W, with optional ESP32 support.

- **Tech:** C++, Arduino-Pico, Wi-Fi, LittleFS, ArduinoOTA, HTTP, and GitHub Releases
- **Notable:** one API supports runtime OTA handling, HTTP pull updates, browser uploads, release updates, reconnect callbacks, and a multi-board compile workflow

### [SmartRacket (SFT)](https://github.com/wedsamuel1230/SFT)

A hardware-and-mobile sports project combining 3D CAD, Arduino BLE IMU sender/receiver sketches, and a Kotlin Android app.

- **Tech:** Kotlin, Jetpack Compose, Room, Hilt, Firebase, Health Connect, Wear OS, and TensorFlow Lite
- **Notable:** connects embedded motion data with mobile training sessions, storage, synchronization, and analytics workflows

### [arduino-skills](https://github.com/wedsamuel1230/arduino-skills)

A toolchain-neutral Agent Skills package for Arduino and embedded development.

- **Tech:** Markdown-based Agent Skills, Python scripts, JSON fixtures, and GitHub Actions
- **Notable:** packages board support, code generation, project scaffolding, non-blocking patterns, OTA guidance, sensor filtering, and validation/evaluation workflows

## Areas of Interest

- Embedded systems, IoT, and hardware/software integration
- Robotics, sensing, motion, and hardware-aware testing
- Developer tools, agent workflows, MCP, and local document automation
- Cross-platform interfaces and learning-oriented technical documentation

## Connect

- [GitHub](https://github.com/wedsamuel1230)
