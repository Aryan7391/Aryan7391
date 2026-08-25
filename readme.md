<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F3864,100:00D4FF&height=200&section=header&text=Aryan%20Chand&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20%7C%20Backend-First%20Builder&descAlignY=55&descSize=20" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=00D4FF&center=true&vCenter=true&width=650&lines=Building+PAT_7+%E2%80%94+a+leader-orchestrator+agent+runtime;Shipped+a+delivery+dispatch+engine+at+94%25%2B+accuracy;Not+everyone+has+a+GPU.+Building+AI+that+doesn't+care." alt="Typing SVG" />
</a>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Aryan7391-181717?style=for-the-badge&logo=github)](https://github.com/Aryan7391)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aryan%20Chand-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/aryanchand7391/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aryanchand7391@gmail.com)

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Aryan7391&theme=tokyonight&hide_border=true&background=0D1117" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api?username=Aryan7391&show_icons=true&theme=tokyonight&hide_border=true&background=0D1117&count_private=true&include_all_commits=true" width="48%"/>

</div>

---

### 👋 About

MCA student at Birla Global University, Bhubaneswar (Batch 2025–27 · CGPA 8.18) who builds backend-first and treats AI models as tools, not magic. I plan architecture in a physical notebook before I touch a keyboard, and I'd rather ship something that works than something that demos well.

- 🔭 **Currently building:** [`PAT_7`](https://github.com/Aryan7391/PAT-AI) v2 — a leader-orchestrator agent runtime with task delegation, standardized agent/tool contracts, and a persisted execution trace
- 🧪 **Researching:** domain-specific knowledge distillation so ~3B-parameter models can match larger ones on constrained hardware — motivated by getting [`Darshan-3`](https://github.com/Aryan7391/Darshan_3) under 100ms on a Raspberry Pi
- 💬 **Ask me about:** RAG pipelines, agent orchestration, or backend architecture for real-time systems
- ⚡ **Outside code:** essay writing and quiz competitions — old habits from before I started shipping software

---

### 🧠 Flagship: PAT_7 — Hybrid Personal AI Assistant

**v1 — shipped.** Voice activation (OpenWakeWord), XTTS v2 speech synthesis, persistent cross-session memory across 10+ project contexts. Hybrid by design — runs locally, calls out to Groq/Gemini/GPT-4o for heavy compute.

**v2 — in design, build starting.** Moving from single-agent voice control to a leader-based runtime that plans before it executes:

```
                         PAT_7
                           │
                    ┌──────▼──────┐
                    │    LEADER   │
                    │ Orchestrator│
                    └──────┬──────┘
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
        Delegation     Tool Calling   Direct Answer
             │             │
       ┌─────┼─────┐       │
       ▼     ▼     ▼       ▼
     Code  Data  Research  MCP/Tools
     Agent Agent   Agent
       │     │       │
       └─────┴───────┘
               │
               ▼
        Results / Artifacts → Leader → Final Synthesis
```

Every `Agent` and `Tool` implements the same contract, so the Leader can delegate or call a tool without hard-coded logic per agent — and every run persists an execution trace (`decision → delegation → tool call → result → synthesis`), so the system is inspectable, not just a chat log.

**Milestone order:** `AgentRuntime → LeaderAgent → AgentRegistry → ToolRegistry → Delegation → Tool Calling → Execution Trace → Final Synthesis`

`Python` `Ollama` `TypeScript` `Next.js` `Vercel`
[![Live](https://img.shields.io/badge/Live-pat--ai--eight.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white)](https://pat-ai-eight.vercel.app/)
[![GitHub](https://img.shields.io/badge/Code-PAT--AI-181717?style=flat-square&logo=github)](https://github.com/Aryan7391/PAT-AI)

---

### 🛡️ AI Defender — Security Platform *(private, in progress)*

```
[M1: Data Gen] ──▶ [M2: Static Scanner] ──▶ [M3: Runtime]
     DONE               IN PROGRESS          43 JSONL files
Groq · Llama-3.3      Flask / Express       MITRE ATT&CK
  70b-versatile        OWASP Top 10        8 Attack Categories
                            │
              ┌─────────────┴─────────────┐
              ▼                           ▼
      VS Code Extension          CI/CD Integration
        (distribution)      GitHub Actions / Jenkins · shared REST API
```

`Python` `Groq API` `Llama-3.3-70b` `Flask` `OWASP` `MITRE ATT&CK`

---

### 👁️ Darshan-3 — Edge Vision for Visually Impaired Users

On-device, offline, sub-100ms — no cloud in the loop.

```
Raspberry Pi + Wearable Camera
        │
        ▼
YOLOv8 Nano (detection) → OpenCV (frames) → pyttsx3/gTTS (audio guidance)
```

`YOLOv8 Nano` `OpenCV` `Python` `Raspberry Pi` `pyttsx3`
[![GitHub](https://img.shields.io/badge/Code-Darshan__3-181717?style=flat-square&logo=github)](https://github.com/Aryan7391/Darshan_3)

---

### 📦 More projects

| Project | What it does | Tech | Link |
|---|---|---|---|
| **SmartRoute** | Last-mile delivery dispatch — solo-built backend, heuristic (Clarke-Wright) routing at 94%+ accuracy | FastAPI, Supabase, OSRM | — |
| **PTJP** | Part-time job platform, deployed as a signed production Android app | React Native, Expo, Supabase | [→](https://github.com/Aryan7391/PTJP-D1) |
| **CivicConnect** | Civic engagement PWA with 4-role auth (citizen/volunteer/institution/government) | Next.js, Supabase, RLS | [→](https://ama-kachra.vercel.app/) |
| **PS Predictor** | Process-failure prediction — RF + SVM ensemble with rule-based override, Flask dashboard | scikit-learn, Flask | [→](https://github.com/Aryan7391/PS_Predict) |
| **Image Caption Generator** | ResNet-50 encoder → LSTM decoder, trained on COCO | PyTorch, HuggingFace, Flask | [→](https://github.com/Aryan7391/image_caption) |

---

### 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/Aryan7391/Aryan7391/output/github-contribution-grid-snake.svg" width="100%"/>

*(auto-updates every 12h once the included GitHub Action is enabled — see `snake.yml`)*

---

### 🛠️ Stack

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,ts,js,c&theme=dark"/>

**AI / ML**
<br/>
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,opencv,huggingface&theme=dark"/>

**Frameworks & Infra**
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,flask,fastapi,supabase,vercel&theme=dark"/>

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aryan7391&layout=compact&theme=tokyonight&hide_border=true&background=0D1117" width="48%"/>
<img src="https://github-profile-trophy.vercel.app/?username=Aryan7391&theme=tokyonight&no-frame=true&column=4&margin-w=8" width="48%"/>

</div>

---

<div align="center">

**Open to:** Collaborations · Research Partnerships · Internship Opportunities · Open Source

*"Not everyone has a GPU. Building AI that doesn't care."*

<img src="https://komarev.com/ghpvc/?username=Aryan7391&color=00D4FF&style=for-the-badge&label=PROFILE+VIEWS"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D4FF,100:1F3864&height=100&section=footer" width="100%"/>

</div>
