[![Follow on GitHub](https://img.shields.io/github/followers/taylordanger?label=Follow&style=social)](https://github.com/taylordanger)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/taylordanger)

# Taylor Danger — Embedded Systems Engineer

![terminal header](images/terminal-header.svg)

I design firmware and small-screen device UIs that feel polished and reliable. I focus on testable architecture, reproducible tooling, and UX that respects constrained hardware.

• Embedded systems (ESP32) • Modern C++ • e‑paper displays • Testable UI tooling

---

## Quick facts

- **Role:** Embedded Systems Engineer
- **Location:** Remote / Hybrid
- **Availability:** Open to collaboration & freelance

---

## Skills & tools

- **Languages:** C, C++ (modern), Python, TypeScript
- **Embedded:** ESP32, FreeRTOS, Arduino framework
- **Displays & UI:** GxEPD, Adafruit GFX, e‑paper UX patterns
- **Tooling:** CMake, Git, CI, automated asset generation

Proficiency: C/C++ · Embedded systems · Python/tooling · Rust (learning)

---

## Selected projects

- **ESP32-Virtualpet** — Virtual pet on ESP32: persistent state, efficient render loops, playful UX patterns.
  - https://github.com/taylordanger/ESP32-Virtualpet

- **GxEPD-Multiple-Epaper-Screen-Example** — Multi-screen patterns and transitions for e‑paper devices.
  - https://github.com/taylordanger/GxEPD-Multiple-Epaper-Screen-Example

- **Open-source contributions** — Small, high-impact PRs to improve e‑paper and embedded tooling reliability.

---

## How I work

- Build small, testable abstractions so UI logic can run on desktop and on-device.
- Prefer incremental changes, reproducible builds, and automated asset generation.
- Treat UX for constrained devices as a first-class engineering problem.

---

## Dev demo (simulated)

Example simulated terminal output from a local device simulator:

```bash
$ ./tools/sim --display=212x104 --profile=eink
[  OK  ] init: display driver GxEPD2
[  OK  ] load: assets (18 items)
[ INFO ] UI: home screen ready
[ INFO ] input: map keys -> {A:left, B:select, C:right}
[ READY] Simulation listening on http://127.0.0.1:8080
> press [A] [B] [C] to simulate button events
```

---

## Try / clone

```bash
git clone https://github.com/taylordanger/ESP32-Virtualpet
git clone https://github.com/taylordanger/GxEPD-Multiple-Epaper-Screen-Example
```

---

## Contact

- [LinkedIn](https://linkedin.com/in/taylordanger)
- [GitHub](https://github.com/taylordanger)
- Email: lauren.taylor.sheppard@gmail.com

---

If you'd like, I can:

- Add build/coverage badges and a resume link
- Create a short contributor guide or a pinned projects section
- Tweak tone/length for hiring vs. open-source audiences

Tell me which style you prefer (compact, friendly, or technical) and I will iterate.
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="240" viewBox="0 0 1200 240" preserveAspectRatio="xMidYMid slice">
  <defs>
    <linearGradient id="g" x1="0" x2="1">
      <stop offset="0" stop-color="#002200"/>
      <stop offset="1" stop-color="#003300"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- background -->
  <rect width="100%" height="100%" fill="black"/>

  <!-- subtle terminal grid lines -->
  <g fill="none" stroke="#052205" stroke-width="1">
    <pattern id="p" width="24" height="24" patternUnits="userSpaceOnUse">
      <path d="M0 24 H1200" stroke="#052205" stroke-opacity="0.15"/>
    </pattern>
    <rect width="100%" height="100%" fill="url(#p)" />
  </g>

  <!-- header text -->
  <g transform="translate(48,48)" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, 'Courier New', monospace" font-weight="700" text-anchor="start">
    <text x="0" y="42" font-size="44" fill="#00ff66" filter="url(#glow)" letter-spacing="1">taylordanger</text>
    <text x="0" y="90" font-size="18" fill="#9cffb2" opacity="0.95">Embedded Systems · ESP32 · Modern C++ · e‑paper UIs</text>
  </g>

  <!-- faux cursor -->
  <rect x="360" y="28" width="10" height="28" fill="#00ff66" opacity="0.95">
    <animate attributeName="opacity" values="0.95;0.15;0.95" dur="1.6s" repeatCount="indefinite"/>
  </rect>

  <!-- small status dots -->
  <g transform="translate(1040,36)" fill="#00ff66" opacity="0.9">
    <circle cx="0" cy="0" r="4"/>
    <circle cx="16" cy="0" r="4" fill="#00aa44" opacity="0.7"/>
    <circle cx="32" cy="0" r="4" fill="#007733" opacity="0.5"/>
  </g>
</svg>
[![Follow on GitHub](https://img.shields.io/github/followers/taylordanger?label=Follow&style=social)](https://github.com/taylordanger)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/taylordanger)
[![Email](https://img.shields.io/badge/Email-lauren.taylor.sheppard@gmail.com-blue?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lauren.taylor.sheppard@gmail.com)

<p align="center">
  <img src="images/terminal-header.svg" alt="terminal header" width="900"/>
</p>

# Taylor Danger
Embedded Systems Engineer · ESP32 · Modern C++ · e‑paper UIs

> I design and ship firmware and device UIs that feel polished on tiny screens. My focus: testable architecture, reproducible tooling, and UX that respects constrained hardware.

---

## Quick facts
| Role | Location | Availability |
|---|---|---:|
| Embedded Systems Engineer | Remote / Hybrid | Open to collaboration & freelance |

---

## Tech & proficiency
| Core | Tools & Frameworks |
|---|---|
| C / C++ / Embedded | ESP32 · FreeRTOS · Arduino framework |
| UI / Displays | GxEPD · Adafruit GFX · e‑paper UX |
| Scripting & Tools | Python · TypeScript · CMake · Git · CI |

Proficiency snapshot (visual):
- C/C++ ▉▉▉▉▉▉▉▉▉▉  
- Embedded systems ▉▉▉▉▉▉▉▉▉◻  
- Python / Tooling ▉▉▉▉▉▉▉▉◻◻  
- Rust (learning) ▉▉▉◻◻◻◻◻◻◻

---

## Projects (high signal)
| Project | Highlights |
|---|---|
| [ESP32-Virtualpet](https://github.com/taylordanger/ESP32-Virtualpet) | Virtual pet on ESP32 — persistent state, efficient render loops, playful UX patterns. |
| [GxEPD-Multiple-Epaper-Screen-Example](https://github.com/taylordanger/GxEPD-Multiple-Epaper-Screen-Example) | Multi-screen patterns and transitions for e‑paper devices. |
| Open source contributions | Focused PRs and fixes to improve e‑paper and embedded tooling reliability. |

---

## How I work
- Design small, testable abstractions so UI logic can run on desktop and on-device.
- Prefer incremental changes, reproducible builds, and automated asset generation.
- Treat UX for constrained devices as a first-class engineering problem.

---

## Dev terminal — device simulator (flavor)
```bash
$ ./tools/sim --display=212x104 --profile=eink
[  OK  ] init: display driver GxEPD2
[  OK  ] load: assets (18 items)
[ INFO ] UI: home screen ready
[ INFO ] input: map keys -> {A:left, B:select, C:right}
[ READY] Simulation listening on http://127.0.0.1:8080
> press [A] [B] [C] to simulate button events
```

---

## Try / clone
```bash
git clone https://github.com/taylordanger/ESP32-Virtualpet
git clone https://github.com/taylordanger/GxEPD-Multiple-Epaper-Screen-Example
```

---

## Contact
- LinkedIn: https://linkedin.com/in/taylordanger  
- GitHub: https://github.com/taylordanger  
- Email: lauren.taylor.sheppard@gmail.com


