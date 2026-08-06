<div align="center">

```text
   ╔══════════════════════════════════════════════════════════╗
   ║                                                          ║
   ║     ███████╗██╗   ██╗███╗   ██╗███████╗███████╗████████╗ ║
   ║     ██╔════╝██║   ██║████╗  ██║██╔════╝██╔════╝╚══██╔══╝ ║
   ║     ███████╗██║   ██║██╔██╗ ██║███████╗█████╗     ██║    ║
   ║     ╚════██║██║   ██║██║╚██╗██║╚════██║██╔══╝     ██║    ║
   ║     ███████║╚██████╔╝██║ ╚████║███████║███████╗   ██║    ║
   ║     ╚══════╝ ╚═════╝ ╚═╝  ╚═══╝╚══════╝╚══════╝   ╚═╝    ║
   ║                                                          ║
   ║        Sejong University Network for                     ║
   ║        Science & Engineering Thinkers                    ║
   ║                                                          ║
   ║              · student-built systems after sunset ·      ║
   ╚══════════════════════════════════════════════════════════╝
```

# We build after class.

**Independent student engineering collective** formed by students at Sejong University.<br/>
Software · hardware · experiments — documented like real systems, because they are.

[![GitHub org](https://img.shields.io/badge/GitHub-SUNSET--Sejong--University-181717?style=for-the-badge&logo=github)](https://github.com/SUNSET-Sejong-University)
[![Public repos](https://img.shields.io/badge/public_repos-18-c45c2a?style=for-the-badge)](https://github.com/orgs/SUNSET-Sejong-University/repositories)
[![Location](https://img.shields.io/badge/Seoul-South_Korea-3ecf5c?style=for-the-badge)](https://github.com/SUNSET-Sejong-University)
[![Discussions](https://img.shields.io/badge/Discussions-open-0d1117?style=for-the-badge&logo=github)](https://github.com/orgs/SUNSET-Sejong-University/discussions)

<br/>

| [Projects](#-on-the-bench) · [How we work](#-how-a-build-happens) · [Join](#-start-here-new-members) · [Contribute](#-contribute-like-an-engineer) · [Stack](#-tools-on-the-bench) · [Website](https://github.com/SUNSET-Sejong-University/sunset-web) |

</div>

---

<details open>
<summary><strong>📌 What is SUNSET?</strong> <sup>click to collapse</sup></summary>

<br/>

SUNSET is a student-run **engineering archive and project laboratory**. We keep builds alive after the demo — with repositories, honest status labels, architecture notes, and limitations written in the open.

> Most class projects die in a final ZIP file.<br/>
> **Ours keep running.**

| | |
|:--|:--|
| **Full name** | Sejong University Network for Science & Engineering Thinkers |
| **What we are** | Independent student engineering collective |
| **What we are not** | An official university body, lab, club office, or endorsed organization |
| **Where** | Seoul · after-hours benches, dorm desks, shared lab time |
| **GitHub activity since** | 2024 |

> **Independent status.** SUNSET is an independent student-led collective. References to Sejong University describe the students’ academic community and do not imply official university endorsement.

</details>

---

<div align="center">

## ✦ On the bench

*Real pipelines. Real hardware. Real limitations.*

</div>

### Flagship

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SUNSET-Sejong-University/GRIP-5">GRIP-5</a></h3>
      <p>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img alt="Arduino" src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white"/>
        <img alt="status" src="https://img.shields.io/badge/status-working_prototype-3ecf5c?style=flat-square"/>
      </p>
      <p>Gesture-responsive 5-DOF hand prototype: MediaPipe landmarks → joint angles → discrete finger states → servo control.</p>
      <p><code>CV → MCU → hardware</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SUNSET-Sejong-University/Helios">Helios</a></h3>
      <p>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img alt="CSI" src="https://img.shields.io/badge/WiFi_CSI-c45c2a?style=flat-square"/>
        <img alt="status" src="https://img.shields.io/badge/status-working_prototype-3ecf5c?style=flat-square"/>
      </p>
      <p>Camera-free activity sensing with WiFi CSI + PIR on Arduino Nano 33 IoT, classified locally and published over oneM2M.</p>
      <p><code>RF → classify → IoT log</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SUNSET-Sejong-University/MoodFlix">MoodFlix</a></h3>
      <p>
        <img alt="JS" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img alt="status" src="https://img.shields.io/badge/status-prototype-d4a017?style=flat-square"/>
      </p>
      <p>Multimodal movie-recommendation research prototype combining visual, audio, environmental, and local-model context.</p>
      <p><code>sense → infer → recommend</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SUNSET-Sejong-University/Tolqyn">Tolqyn</a></h3>
      <p>
        <img alt="Processing" src="https://img.shields.io/badge/Processing-P3D-c45c2a?style=flat-square"/>
        <img alt="status" src="https://img.shields.io/badge/status-working_prototype-3ecf5c?style=flat-square"/>
      </p>
      <p>Audio-responsive generative visual system — thousands of nodes driven by FFT, camera motion, and orientation input.</p>
      <p><code>signal → graph → render</code></p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>
        <a href="https://github.com/SUNSET-Sejong-University/NaeonAir">NaeonAir</a> /
        <a href="https://github.com/SUNSET-Sejong-University/wisdrone-interface">WisDrone</a>
      </h3>
      <p>
        <img alt="TS" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img alt="status" src="https://img.shields.io/badge/status-working_prototype-3ecf5c?style=flat-square"/>
      </p>
      <p>UAV / AIoT observation prototype: ESP32-CAM streaming, ground-control gateway, React monitoring UI, and experimental AI path (<a href="https://github.com/SUNSET-Sejong-University/wisdrone-ai-drone">wisdrone-ai-drone</a>).</p>
      <p><code>airframe → gateway → dashboard</code></p>
    </td>
  </tr>
</table>

### Supporting & incubator

| Project | One-liner | Stack signals |
|:--------|:----------|:--------------|
| [Intellichair](https://github.com/SUNSET-Sejong-University/Intellichair) | Load-cell + IMU smart-chair sensing for seated balance / posture signals | C++ · embedded |
| [BuildIn](https://github.com/SUNSET-Sejong-University/BuildIn) | Desk LED “traffic semaphore” for GitHub Actions build status | Arduino · CI |
| [DSNSim](https://github.com/SUNSET-Sejong-University/DSNSim) | Hardware Arduino simulation of NASA Deep Space Network coordination | C++ · RF metaphor |
| [IKUMPlay](https://github.com/SUNSET-Sejong-University/IKUMPlay) | Terminal karaoke machine | Python |
| [roastivator](https://github.com/SUNSET-Sejong-University/roastivator) | Playful web experiment | TypeScript |
| [aura](https://github.com/SUNSET-Sejong-University/aura) | Concept: tangible “smart surfaces” triggering digital workflows | incubator |

<details>
<summary><strong>Learning archive</strong> — data-structure practice repos</summary>

<br/>

Course / structure practice kept as a learning archive (not flagship case studies):

- [Trees](https://github.com/SUNSET-Sejong-University/Trees)
- [Queues](https://github.com/SUNSET-Sejong-University/Queues)
- [Linked-Lists](https://github.com/SUNSET-Sejong-University/Linked-Lists)

</details>

<p align="center">
  <a href="https://github.com/orgs/SUNSET-Sejong-University/repositories">Browse all public repositories →</a>
  &nbsp;·&nbsp;
  <a href="https://sunset-web-sju.vercel.app/" target="_blank">Official website →</a>&nbsp;·&nbsp
  <a href="https://github.com/SUNSET-Sejong-University/sunset-web">Official website source (sunset-web) →</a>
</p>

---

<div align="center">

## ✦ How a build happens

</div>

```text
  ┌─────────┐     ┌─────────┐     ┌──────────────┐     ┌──────────────┐
  │ 1 PITCH │ ──▶ │ 2 TEAM  │ ──▶ │ 3 BUILD OPEN │ ──▶ │ 4 HAND OFF   │
  │ idea +  │     │ fill the│     │ push early,  │     │ docs, limits,│
  │ why     │     │ gaps    │     │ broken OK    │     │ next owner   │
  └─────────┘     └─────────┘     └──────────────┘     └──────────────┘
```

| Step | Title | Bar |
|:----:|:------|:----|
| **1** | Pitch it | Can we actually make this? — not “is this impressive enough?” |
| **2** | Team up | Pair across gaps: CS × mechanical × electronics × ML × frontend |
| **3** | Build in the open | Early commits welcome. README must say what works *and* what doesn’t |
| **4** | Document & hand off | Architecture, wiring, limitations — so the next cohort starts cold |

### Operating principles

```text
  U1 BUILD ──────── hardware-first when the idea is physical
  U2 DOCUMENT ───── READMEs, diagrams, protocols, cited sources
  U3 SHIP TOGETHER ─ cross-major by design; nobody only touches what they already know
```

We prefer **show the system, not only the screenshot** — and we keep incomplete work visible when it helps the next contributor.

---

<div align="center">

## ✦ Start here · new members

</div>

Welcome. You do not need to be “senior” to belong here. You need curiosity, honesty about what you don’t know yet, and willingness to leave the work better documented than you found it.

<details open>
<summary><strong>Beginner path (first two weeks)</strong></summary>

<br/>

1. **Star / watch** this organization and skim 2–3 repos that interest you.
2. Read a project README end-to-end — especially **Limitations**.
3. Run or flash something small (Blink-level comfort is enough to start).
4. Open a [Discussion](https://github.com/orgs/SUNSET-Sejong-University/discussions) or talk to a current contributor about what you want to learn.
5. Pick a first contribution: typo fix, wiring note, diagram, issue reproduction, or a tiny PR.

</details>

<details>
<summary><strong>Who can participate</strong></summary>

<br/>

Students interested in collaborative engineering — software, hardware, creative coding, or experimental systems — can propose or join a build. Course exercises may live in the learning archive rather than as flagship stories.

</details>

<details>
<summary><strong>Propose a project · checklist</strong></summary>

<br/>

Bring a short brief (not a pitch deck):

- [ ] Problem or experiment question
- [ ] Expected output
- [ ] Likely technologies
- [ ] Hardware needs
- [ ] Contributor needs
- [ ] Safety / privacy concerns
- [ ] Demonstration plan
- [ ] Repository owner
- [ ] Documentation owner

Then discuss it with current SUNSET contributors through your existing collaboration channels or org Discussions.

</details>

---

<div align="center">

## ✦ Contribute like an engineer

</div>

| Do | Don’t |
|:---|:------|
| Label status honestly (`concept` / `prototype` / `working-prototype` / …) | Claim production, clinical, or university-official status without proof |
| Document architecture + limitations in the same PR as behavior | Leave “works on my machine” as the only truth |
| Prefer small, reviewable PRs with a clear why | Dump secrets, tokens, private IPs, or `.env` values into git |
| Credit contributors fairly; use **Contributor** when role isn’t verified | Rank people by commit count |
| Keep READMEs runnable for the next student | Invent metrics, awards, or deployment claims |

### Suggested first PR shapes

```text
  docs    → clarify setup, wiring, or limitations
  fix     → reproduce + patch a known fragile path
  chore   → improve CI hygiene, ignore rules, folder clarity
  feat    → smallest vertical slice that proves the next question
```

Security note for every member: **never commit credentials**. If you discover secrets in history, rotate them and clean history — do not paste values into issues or docs.

---

<div align="center">

## ✦ Tools on the bench

</div>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img alt="Arduino" src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img alt="Processing" src="https://img.shields.io/badge/Processing-1B1625?style=for-the-badge"/>
  <img alt="MediaPipe" src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge"/>
  <img alt="oneM2M" src="https://img.shields.io/badge/oneM2M-c45c2a?style=for-the-badge"/>
</p>

| Discipline | How it shows up |
|:-----------|:----------------|
| Physical computing | Servos, load cells, PIR, CSI, flight controllers, MCU firmware |
| Systems software | Gateways, clients, pipelines between devices and interfaces |
| Creative experiments | Generative visuals, multimodal prototypes, playful tools |

---

<div align="center">

## ✦ People

</div>

Public organization members build across cohorts. Roles on the website archive use verified titles where known; otherwise **Contributor**.

<p align="center">
  <a href="https://github.com/orgs/SUNSET-Sejong-University/people">
    <img alt="Org members" src="https://img.shields.io/badge/People-org_roster-181717?style=for-the-badge&logo=github"/>
  </a>
</p>

Want to be listed with a project? Ship documentation and a working path first — the archive follows evidence.

---

<div align="center">

## ✦ Signal

</div>

```text
  18:00  classes end
  18:40  tools open
  21:20  first prototype
  01:10  still debugging
         ───────────────
         AFTER-HOURS · SEOUL · UTC+9
```

<p align="center">
  <strong>WE BUILD AFTER CLASS.</strong><br/>
  <sub>Student-built systems after sunset.</sub>
</p>

---

<details>
<summary><strong>Org profile maintainers</strong></summary>

<br/>

This README lives in the special [`SUNSET-Sejong-University/.github`](https://github.com/SUNSET-Sejong-University/.github) repository at `profile/README.md`.

To update the public org landing page: edit that file on `main`. The `.github` repository must be **public** for GitHub to render the organization profile README.

</details>

<p align="center">
  <sub>
    © SUNSET contributors · Independent student collective at Sejong University ·
    Not an official university endorsement
  </sub>
</p>
