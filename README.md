<div align="center">

# Odai Gubran
### Systems & Full-Stack Software Engineer • AI & Hardware Security Researcher
**Ar-Rasheed Smart University • Sana'a, Yemen**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/odai-dev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:odai.gubran@gmail.com)

<br/>

> *Building high-performance software at the convergence of low-level systems, WebAssembly, and hardware/AI security.*

</div>

---

### About Me

I am an **IT & Systems Software Engineering Researcher** at Ar-Rasheed Smart University, focused on understanding computing systems from the hardware and byte-level up to distributed web architectures.

- **Accepted Author at IEEE IDEASET-2026**: Co-author of *"PIM-Cleanser: In-Memory Acceleration of Data-Intensive Confidential Data Sanitization"* (Sana'a). Implemented fixed-schedule side-channel mitigation inside Processing-in-Memory (PIM) architectures evaluated via cycle-accurate gem5 simulation.
- **AI & VLM Security Researcher**: Engineered an upstream ML security firewall defending Vision-Language Models (GPT-4V, Claude, Gemini) against adversarial typographic camouflage, evaluated on Meta's official `CyberSecEval 3` benchmark (100% precision, 97.4% ROC-AUC).
- **Systems & WebAssembly**: Architected desktop-grade web applications powered by high-speed native Rust constraint-satisfaction solvers compiled directly to WASM, featuring cleanroom binary reverse engineering (`.roz` file format parser).
- **Native Linux Virtualization in Rust**: Built multi-instance Android container management engines on System76's `libcosmic` desktop toolkit, Docker Bollard API, Linux BinderFS node isolation, and DRI GPU acceleration.
- 🖥️ **Operating Systems Internals**: Implemented classical CPU scheduling algorithms from scratch with custom binary min-heaps and circular queues in C++, visualized via real-time Dear ImGui OpenGL animations with a 45-page formal engineering specification.

---

### 🌟 Featured Flagship Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">PIM-Cleanser (IEEE IDEASET-2026)</h3>
      <p align="center">
        <a href="https://github.com/odai-dev/se-pim-data-cleansing">
          <img src="https://img.shields.io/badge/IEEE_IDEASET-2026-00629B?style=flat-square&logo=ieee&logoColor=white" />
          <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
          <img src="https://img.shields.io/badge/gem5-Simulator-orange?style=flat-square" />
          <img src="https://img.shields.io/badge/Security-PIM-red?style=flat-square" />
        </a>
      </p>
      <p>Accepted research paper and artifact evaluation for <b>IEEE IDEASET-2026</b>. Extends the SE-PIM confidential computing architecture with an in-memory data sanitization engine using fixed-schedule execution to prevent memory side-channel leakage. Verified through cycle-accurate gem5 simulations and strict reproducibility test harnesses.</p>
      <p><a href="https://github.com/odai-dev/se-pim-data-cleansing"><b>View Repository →</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Visual Prompt Injection Firewall</h3>
      <p align="center">
        <a href="https://github.com/odai-dev/visual_prompt_injection_detection">
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
          <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
          <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
          <img src="https://img.shields.io/badge/Meta_CyberSecEval_3-0081FB?style=flat-square&logo=meta&logoColor=white" />
        </a>
      </p>
      <p>Upstream multimodal machine learning security firewall defending Vision-Language Models against typographic camouflage and visual prompt injection attacks. Achieves <b>100% Precision</b> and <b>97.4% ROC-AUC</b> on Meta's official <code>CyberSecEval 3</code> benchmark. Backed by formal thesis paper and reproducible evaluation notebooks.</p>
      <p><a href="https://github.com/odai-dev/visual_prompt_injection_detection"><b>View Repository →</b></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">OpenTimetable</h3>
      <p align="center">
        <a href="https://github.com/odai-dev/opentimetable">
          <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
          <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white" />
          <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
          <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        </a>
      </p>
      <p>Academic Timetable Studio featuring a high-speed native <b>Rust constraint-satisfaction solver</b> compiled directly to <b>WebAssembly (WASM)</b> for zero-latency client-side solving. Includes a cleanroom reverse-engineered parser for aSc Timetables (<code>.roz</code>) archives, bilingual RTL Arabic / LTR English studio, and Dean-signature print exports.</p>
      <p><a href="https://github.com/odai-dev/opentimetable"><b>View Repository →</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">CosmicReDroid</h3>
      <p align="center">
        <a href="https://github.com/odai-dev/CosmicReDroid">
          <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
          <img src="https://img.shields.io/badge/libcosmic-System76-blue?style=flat-square" />
          <img src="https://img.shields.io/badge/Docker_Bollard-2496ED?style=flat-square&logo=docker&logoColor=white" />
          <img src="https://img.shields.io/badge/Android-ReDroid-3DDC84?style=flat-square&logo=android&logoColor=white" />
        </a>
      </p>
      <p>Native Linux Android multi-instance control center built with Rust on System76's <b>libcosmic</b> desktop toolkit. Manages isolated ReDroid containers via Docker Bollard, featuring real-time hardware identity spoofing (Galaxy S24 Ultra, Pixel 8 Pro), deterministic BinderFS node isolation, DRI GPU acceleration, and zstd CoW snapshots.</p>
      <p><a href="https://github.com/odai-dev/CosmicReDroid"><b>View Repository →</b></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">CPU Scheduling Simulator</h3>
      <p align="center">
        <a href="https://github.com/odai-dev/CPU-Scheduling-Algorithms-Simulation-Using-Data-Structures">
          <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
          <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" />
          <img src="https://img.shields.io/badge/Dear_ImGui-white?style=flat-square&logo=cplusplus&logoColor=black" />
          <img src="https://img.shields.io/badge/Operating_Systems-FF6F00?style=flat-square" />
        </a>
      </p>
      <p>Operating systems scheduling simulator in C++ implementing 6 classical algorithms (FCFS, SJF, SRTF, Preemptive/Non-preemptive Priority, Round Robin) with scratch-built heap and queue data structures. Features real-time animated Gantt charts via <b>Dear ImGui & OpenGL</b>, backed by a 45-page formal engineering specification.</p>
      <p><a href="https://github.com/odai-dev/CPU-Scheduling-Algorithms-Simulation-Using-Data-Structures"><b>View Repository →</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">InChatSight</h3>
      <p align="center">
        <a href="https://github.com/odai-dev/InChatSight">
          <img src="https://img.shields.io/badge/Chrome_Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
          <img src="https://img.shields.io/badge/Manifest_V3-34A853?style=flat-square" />
          <img src="https://img.shields.io/badge/AI_Assistant-OpenRouter-blueviolet?style=flat-square" />
          <img src="https://img.shields.io/badge/WhatsApp_Web-25D366?style=flat-square&logo=whatsapp&logoColor=white" />
        </a>
      </p>
      <p>Applied AI browser extension built on Chrome Manifest V3 that injects a context-aware conversational AI companion directly into web chat platforms (WhatsApp Web). Features dynamic DOM message extraction, sliding session memory, and asynchronous multi-LLM routing with zero telemetry leakage.</p>
      <p><a href="https://github.com/odai-dev/InChatSight"><b>View Repository →</b></a></p>
    </td>
  </tr>
</table>

---

### Commercial & Enterprise Systems (Proprietary / Client Work)

#### K9 Operations & Logistics Management Platform
*Enterprise operations management system engineered and deployed for commercial facility management.*

* **Confidentiality Notice**: Proprietary enterprise system (Source code private under client agreement; architecture presented with permission).
* **Core Architecture**: Modular Python backend built with Flask and SQLAlchemy, connected to a production PostgreSQL database with multi-stage Docker containerization.
* **Role-Based Access Control (RBAC)**: Fine-grained multi-tier permissions isolating command staff, veterinary teams, canine handlers, and administrative auditors.
* **Cryptographic Token Verification**: Implemented cryptographic security tokens to safeguard report generation and approval workflows against unauthorized state modification.
* **Complex Domain Modeling**: Comprehensive relational tracking for medical histories, vaccination regimens, genetic breeding lineage, and operational field assignments.

---

### Technical Arsenal

<div align="center">

| Domain | Technologies & Frameworks |
|:---|:---|
| **Core Languages** | `Rust` • `C++` • `Python` • `TypeScript` • `JavaScript (ES6+)` • `SQL` • `HTML5 / CSS3` |
| **Systems & Architecture** | `WebAssembly (WASM)` • `System76 libcosmic` • `Docker / Bollard` • `gem5 Simulator` • `Linux BinderFS / DRI` • `Dear ImGui` • `OpenGL` |
| **AI & Security** | `Multimodal VLM Defense` • `Meta CyberSecEval 3` • `Adversarial ML` • `OpenCV` • `Scikit-Learn` • `PIM Confidential Computing` |
| **Full-Stack & Web** | `Next.js 16` • `React 19` • `Flask` • `Django` • `PostgreSQL` • `Tailwind CSS` • `Chrome Extensions (MV3)` |
| **Methodologies & Tools** | `Cleanroom Reverse Engineering` • `Test-Driven Development (TDD)` • `Git` • `Linux Administration` • `Bilingual RTL/LTR UI` |

</div>

---

### GitHub Activity & Analytics

<div align="center">

<img src="https://github-readme-stats-fast.vercel.app/api?username=odai-dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="Odai's GitHub Stats" />
<img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=odai-dev&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&exclude_repo=TOP-curriculum,nearby" height="165" alt="Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=odai-dev&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

<div align="center">
  <sub>Crafted with precision by Odai Gubran • Sana'a, Yemen</sub>
</div>
