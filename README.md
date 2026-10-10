<!-- NotY215 profile README -->

<div align="center">

<img src="https://avatars.githubusercontent.com/u/180653079?v=4" alt="NotY215 avatar" width="120" height="120">

<img src="assets/logo.svg" alt="NotY215" width="760">

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=header&text=NotY215&fontSize=38&fontColor=ffffff&fontAlignY=35&animation=twinkling&color=0:7c3aed,50:06b6d4,100:22c55e" width="100%" alt="Animated NotY215 header">

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&duration=2600&pause=700&color=22D3EE&center=true&vCenter=true&width=800&lines=Programming+Languages+%7C+Compilers+%7C+Systems;AI+Tools+%7C+Game+Tools+%7C+Creative+Software;Building+Vayu+%2B+VCB+%2B+NotY+projects;Learning+by+building+the+whole+thing" alt="NotY215 animated introduction">

<p>
<a href="https://github.com/NotY215"><img src="https://img.shields.io/github/followers/NotY215?label=Followers&style=for-the-badge" alt="Followers"></a>
</p>

</div>

---

## $ whoami

I am **Shreyas Mishra**, also known as **NotY215**.

I am an independent developer working on programming languages, compilers, systems, AI, media, games and developer tools.

Instagram: **@mishra_shreyas215**

I like going below the surface. If something is interesting, I want to understand how it works and eventually build my own version.

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212749171-b84692a8-2b04-4e3b-93ca-ac14705da224.gif" width="420" alt="Animated coding GIF">
</div>

### What I work on

```text
NotY215
├── Vayu
│   └── Programming language and native compiler ecosystem
├── VCB
│   └── Native compiler backend for Vayu
├── NotYVOS
│   └── x86-64 operating system and PS3 runtime foundation
├── PPSX33
│   └── Experimental PlayStation 3 static recompiler
├── AI & Media
│   ├── NotY Caption
│   ├── NotY Upscaler
│   └── NotY Caption Official
├── Game & Minecraft
│   ├── NotY Game Repacker
│   ├── AutoTotem
│   └── HeartsPlugin
├── DXFS
│   └── C++ file format and terminal experiment
└── Websites
    ├── Vayu
    ├── VCB
    └── NotY Caption
```

---

---

# 🚀 Main Projects

## 🌪️ Vayu

<div align="center">
<a href="https://vayu.gt.tc">
<img src="https://raw.githubusercontent.com/NotY215/Vayu/master/assets/logo.svg" alt="Vayu logo" width="150">
</a>
</div>

**Vayu** is my main programming language project.

Vayu uses Python-inspired syntax with native compilation, static typing, type inference, low-level control, C/C++ interoperability, editor tooling, packages, GUI and application development, games, graphics and AI/ML support.

The current native compiler path is:

```text
.vyu source
   ↓
Vayu frontend
   ↓
VCBIR
   ↓
VCB
   ↓
x86-64 code generation
   ↓
PE or ELF executable
```

**Source:** [NotY215/Vayu](https://github.com/NotY215/Vayu)  
**Website:** [vayu.gt.tc](https://vayu.gt.tc)  
**Syntax:** [Vayu Syntax](https://github.com/NotY215/Vayu/blob/master/docs/syntax.md)  
**Benchmarks:** [Vayu Website](https://vayu.gt.tc/speed)  
**VS Code:** [Vayu on VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=Fliczo.vayu)

### Vayu ecosystem

| Project | Role |
|---|---|
| **Vayu** | Language, compiler, runtime and tooling |
| **VCB** | Native compiler backend |
| **Vayu Website** | Website, documentation, roadmap and benchmarks |
| **VS Code tooling** | Language support, LSP, formatter and linter |

---

## ⚙️ VCB

<div align="center">
<a href="https://vayu.gt.tc/VCB">
<img src="https://raw.githubusercontent.com/NotY215/VCB/master/Assets/VCB_banner.svg" alt="VCB banner" width="900">
</a>
</div>

**VCB** means **Vayu Compiler Backend**.

VCB is a standalone C++20 native backend for Vayu. Vayu lowers supported programs into VCBIR, then VCB handles native code generation and executable output.

### Current status

**VCB 0.5.3**

Phase 27 Parts 1 to 17 are complete. The current backend includes:

- VCBIR parsing and printing
- SSA-style typed IR
- x86-64 native code generation
- PE executable generation
- ELF executable generation
- Windows runtime imports
- Linux syscall based runtime support
- Linux bump allocation
- List and map runtime support
- String and collection printing
- Demand driven runtime emission
- PE and ELF inspection
- Output directory creation
- PE image padding and diagnostics

The next backend work is the object and external linker path.

**Repository:** [NotY215/VCB](https://github.com/NotY215/VCB)  
**Website:** [vayu.gt.tc/VCB](https://vayu.gt.tc/VCB)

---

## 🖥️ NotYVOS

<div align="center">
<a href="https://github.com/NotY215/NotYVOS">
<img src="https://raw.githubusercontent.com/NotY215/NotYVOS/main/Assets/Neon%20Blue%20NotYVOS%20Tech%20Logo.png" alt="NotYVOS logo" width="220">
</a>
</div>

**NotYVOS** is a development-stage x86-64 operating system with a desktop environment, persistent storage, native hardware drivers and an integrated PlayStation 3 runtime foundation.

The current codebase includes:

- x86-64 kernel and CPU support
- User processes and syscalls
- ELF64 program loading
- Scheduler and context switching
- VFS and persistent NYFS storage
- Desktop compositor
- Explorer, Settings and Bin applications
- Graphics API and graphics HAL
- Software and VBE graphics backends
- TrueType font rendering
- USB and input integration
- PS3 runtime foundation
- RSX compatibility foundation
- GameRunner foundation
- Native GPU backend
- Extended desktop interaction work through Phases 11–18, including networking, Wi-Fi and Bluetooth

**Current focus:** Phase 19, NYFS maturity. Windows application compatibility remains outside the current roadmap.

Current platform work uses C++20, C17, x86-64 Assembly, Clang/LLVM, LLD, CMake, Ninja and Limine.

**Repository:** [NotY215/NotYVOS](https://github.com/NotY215/NotYVOS)  
**Web project:** [NotY215/NotYVOS-Web](https://github.com/NotY215/NotYVOS-Web)

---

## 🎮 PPSX33

<div align="center">
<a href="https://github.com/NotY215/PPSX33">
<img src="https://raw.githubusercontent.com/NotY215/PPSX33/main/assets/ppsx33-banner.png" alt="PPSX33 banner" width="100%">
<br>
<img src="https://raw.githubusercontent.com/NotY215/PPSX33/main/assets/ppsx33-logo.png" alt="PPSX33 circular logo" width="140">
</a>
</div>

**PPSX33** is an experimental static recompiler for decrypted 64-bit big-endian PowerPC ELF input from PlayStation 3 software. Its Windows output includes a native `game.exe` and `ps3rt.dll`. The project uses C++, C and C#.

### Current status

- ELF64 big-endian loading is implemented.
- PPU instruction translation is partial, with coverage tracked in the repository documentation.
- The native MSVC build can produce `game.exe` and `ps3rt.dll`.
- Runtime execution is still incomplete.
- SPU execution and RSX graphics rendering are not implemented.
- Full commercial-game compatibility has not been established.

Current lifting reports include snapshots for God of War III, Uncharted 2 and Demon's Souls. These are static translation counts, not proof of correct runtime behavior or commercial-game compatibility. PPU semantics remain partial, SPU execution is incomplete, and RSX host rendering is not yet implemented. Use only game data and software you own or are legally authorized to process.

**Repository:** [NotY215/PPSX33](https://github.com/NotY215/PPSX33)  
**Build guide:** [PPSX33 README](https://github.com/NotY215/PPSX33#build-on-windows)  
**PPU coverage:** [PPU coverage notes](https://github.com/NotY215/PPSX33/blob/main/docs/PPU_COVERAGE.md)

---

# 🤖 AI & Media

| Project | Focus |
|---|---|
| <img src="https://raw.githubusercontent.com/NotY215/NotYCaptionGenAi-Light-weight/main/resources/logo.ico" alt="NotY Caption Generator logo" width="48"> **NotYCaptionGenAi-Light-weight** | v7.1 Whisper-based CLI for transcription and captions, vocal separation, YouTube/local media, translation and subtitle formatting |
| **NotYUpscalerZAI** | AI based video and image upscaling |
| <img src="https://raw.githubusercontent.com/NotY215/NotyCaption-Official/refs/heads/Website/Logo.ico" alt="NotyCaption Pro logo" width="48"> **NotyCaption-Official** | NotyCaption Pro with Whisper, Google Colab and Google Drive workflows |

**Caption Generator:** [Repository](https://github.com/NotY215/NotYCaptionGenAi-Light-weight)  
**Upscaler:** [Repository](https://github.com/NotY215/NotYUpscalerZAI)  
**NotyCaption Pro:** [Repository](https://github.com/NotY215/NotyCaption-Official)  
**NotyCaption Website:** [notycaptiongen.free.nf](https://notycaptiongen.free.nf)

---

# 🎮 Game & Minecraft

### 📦 NotYGameRepacker

<div align="center">
<a href="https://github.com/NotY215/NotYGameRepacker">
<img src="https://raw.githubusercontent.com/NotY215/NotYGameRepacker/master/resources/logo.png" alt="NotYGameRepacker logo" width="140">
</a>
</div>

A Windows-first game packaging and installation project for files the user legitimately owns.

The current codebase is an active C/C++ project using C++20, C17, the Windows SDK, native Win32 UI, CMake and MSVC. The core Windows x64 foundation and build architecture are present; the complete package, repack and install pipeline is still in development. Cryptography is not implemented yet, so the project does not claim to provide encryption or authenticated package security.

[Repository](https://github.com/NotY215/NotYGameRepacker)

### 🛡️ AutoTotem

<div align="center">
<a href="https://github.com/NotY215/AutoTotem">
<img src="https://raw.githubusercontent.com/NotY215/AutoTotem/master/26.3/src/main/resources/assets/autototem/icon.png" alt="AutoTotem logo" width="120">
</a>
</div>

A Fabric client-side Minecraft mod for automatic Totem of Undying management. The current README lists Minecraft 1.21.9 through 26.3, with separate builds for the Yarn-based 1.21.x line and Mojang-mapped 26.x versions.

[Repository](https://github.com/NotY215/AutoTotem)

### ❤️ HeartsPlugin

A Minecraft plugin project.

[Repository](https://github.com/NotY215/HeartsPlugin)

---

# 🧪 DXFS

**DXFS** is a C++17 file format and terminal editor experiment focused on compact representations of large digit sequences using packed data and generators.

[Repository](https://github.com/NotY215/DXFS)

---

# 🌐 Websites

| Project | Website |
|---|---|
| **Vayu** | [vayu.gt.tc](https://vayu.gt.tc) |
| **VCB** | [vayu.gt.tc/VCB](https://vayu.gt.tc/VCB) |
| **NotyCaption Pro** | [notycaptiongen.free.nf](https://notycaptiongen.free.nf) |

The Vayu website is the main place for current language information, documentation, roadmap and benchmark information.

---

---

# 🧰 Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=cpp,c,python,java,cmake,git,github,vscode,linux,windows&perline=10" alt="NotY215 technology stack">

</div>

**Languages:** C++ • C • Python • Java • Vayu • x86-64 Assembly  
**Systems:** CMake • Ninja • LLVM • Clang • Git  
**AI & Media:** Whisper • Spleeter • FFmpeg • Nuitka • PyInstaller  
**Application & Game:** Qt • Fabric • Minecraft • OpenGL • Windows

---

# 🎯 Current Goals

### Vayu

Finish the language and native compiler ecosystem around VCBIR, VCB, tooling, packages, LSP, formatter, linter, runtime and native interoperability.

### VCB

Complete the object emitter and external linker path, then continue the backend roadmap toward more language features and self hosting.

### NotYVOS

Continue kernel, desktop, storage, hardware, graphics and PS3 runtime development.

### PPSX33

Expand PPU translation coverage, improve runtime control flow and continue validating the recompiler with synthetic tests. SPU, RSX and broader compatibility remain future work.

### Keep building

I learn by making things, breaking them, fixing them and trying again.

---

---

# 📊 GitHub

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=NotY215&amp;show_icons=true&amp;hide_border=true&amp;rank_icon=github&amp;theme=transparent" alt="NotY215 GitHub statistics">

<br>

<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=NotY215&amp;layout=compact&amp;hide_border=true&amp;theme=transparent" alt="NotY215 top languages">

<br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=NotY215&amp;hide_border=true&amp;bg_color=00000000&amp;color=22d3ee&amp;line=7c3aed&amp;point=22c55e&amp;area=true&amp;area_color=7c3aed" alt="NotY215 GitHub activity">

</div>

---

# htop Activity

```text
 NotY215 activity monitor
 ─────────────────────────────────────────────────────────

 PID   PROJECT              STATE
 001   Vayu                 BUILDING
 002   VCB                  PHASE 27 COMPLETE
 003   NotYVOS              RUNNING
 004   PPSX33               IN DEVELOPMENT
 005   NotY Caption         ACTIVE
 006   NotYGameRepacker     ACTIVE
 007   AutoTotem            ACTIVE
 008   DXFS                 EXPERIMENT

 STATUS  : building
 FOCUS   : languages • compilers • systems • tools
```

---

---

# 🧭 Current Direction

```text
Vayu
 │
 ├── Frontend
 │    ├── Syntax
 │    ├── Types
 │    └── VcbLower
 │
 ├── VCB
 │    ├── VCBIR
 │    ├── x86-64
 │    ├── PE
 │    ├── ELF
 │    └── Object + linker path
 │
 └── Ecosystem
      ├── LSP
      ├── Formatter
      ├── Linter
      ├── Packages
      └── Native tooling

NotYVOS
 │
 ├── Kernel
 ├── Desktop
 ├── Storage
 ├── Graphics
 ├── Hardware
 └── PS3 runtime
```

---

---

# 🎨 Outside Code

I also spend time on:

- 🎬 Video editing
- 🎞️ Anime edits
- 🖼️ Visual design
- 🎮 Gaming
- 🧩 Game development
- 🧪 Technical experimentation

Creative work and programming often overlap in the same projects.

---

# 📚 How I Learn

I learn by building.

```text
Question
   ↓
Research
   ↓
Prototype
   ↓
Break it
   ↓
Understand why
   ↓
Rebuild it
   ↓
Keep going
```

---

# 🔭 Long-Term

The bigger direction is an ecosystem where the pieces connect:

```text
Language
   ↓
Compiler
   ↓
Backend
   ↓
Runtime
   ↓
Tools
   ↓
Applications
   ↓
Systems
```

Vayu is the center of that direction. The other projects let me explore different layers of software engineering.

---

# 🔗 Find Me

<div align="center">

[GitHub](https://github.com/NotY215) • [Vayu](https://vayu.gt.tc) • [VCB](https://vayu.gt.tc/VCB) • [Modrinth](https://modrinth.com/user/NotY215) • [Instagram](https://www.instagram.com/mishra_shreyas215/) • [Telegram](https://t.me/Noty_215) • [YouTube: NotY215](https://www.youtube.com/@NotY215) • [YouTube: Aayush Crossing](https://www.youtube.com/@AayushCrossing)

<br><br>

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=18&duration=2400&pause=700&color=7C3AED&center=true&vCenter=true&width=720&lines=Build+it.;Understand+it.;Break+it.;Rebuild+it.;Ship+it." alt="NotY215 closing animation">

<br>

<img src="assets/favicon.svg" alt="NotY215 icon" width="64">

### NotY215

**Independent developer • Editor • Gamer • Programmer • Game developer**

</div>


## Project policies

- [Contributing](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Security](SECURITY.md)
- [Support](SUPPORT.md)
- [Citation](CITATION.cff)
- [Governance](GOVERNANCE.md)
- [License](LICENSE)
