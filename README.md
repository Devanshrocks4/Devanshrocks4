<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,100:2C5364&height=170&section=header&text=Devansh%20Gupta&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Software%20Engineer%20%C2%B7%20Full-Stack%20Developer&descAlignY=58&descSize=16" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1200&center=true&vCenter=true&width=650&lines=Software+Engineer;Full-Stack+Developer+(React+%E2%80%A2+Node.js+%E2%80%A2+MongoDB);AI-Powered+Web+Applications+(Google+Gemini);Learning+Java+%2B+Spring+Boot;Open+to+Software+Engineer+roles" />
</p>

<p align="center">🥇 TCS Ninja (SE track) — Selected &nbsp;|&nbsp; 🟢 Open to Software Engineer / Full-Stack roles</p>
<p align="center"><sub>📂 <a href="#featured-projects">View Projects</a> &nbsp;·&nbsp; 🛠 <a href="#tech-stack">Tech Stack</a> &nbsp;·&nbsp; 📬 <a href="#contact">Contact</a></sub></p>

<br>

---

## About Me

- I build complete products end-to-end — design, build, ship, and maintain — not isolated demos.
- I focus on backend engineering — REST APIs, authentication, and service-layer design.
- I enjoy integrating AI into practical software rather than bolting it on as a feature.
- Currently deepening backend fundamentals through Java, Spring Boot, and system design.

```java
public class DevanshGupta {
    String role        = "Software Engineer";
    String education   = "B.Tech, Computer Science";
    String currentRole  = "Associate Skills Counselor @ Physics Wallah";
}
```

<br>

---

## Current Focus

| Building Now | Learning Now |
|---|---|
| Full-stack apps — React + Node.js/Express | Spring Boot fundamentals |
| REST APIs with JWT-based auth | System design — scalability patterns |
| AI integrations (Google Gemini) | Docker & CI/CD |
| MongoDB schema design for production apps | DSA in Java |

<br>

---

## Tech Stack

**Languages**
<p><img src="https://skillicons.dev/icons?i=java,javascript,typescript,python,cpp,c,php"/></p>

**Frontend**
<p><img src="https://skillicons.dev/icons?i=react,astro,tailwind,html,css"/></p>

**Backend**
<p><img src="https://skillicons.dev/icons?i=nodejs,express,flask"/></p>

**Databases**
<p><img src="https://skillicons.dev/icons?i=mongodb,mysql"/></p> + Firestore

**Cloud & Deployment**
<p><img src="https://skillicons.dev/icons?i=firebase,netlify,vercel,cloudflare,linux"/></p>

**Developer Tools**
<p><img src="https://skillicons.dev/icons?i=git,github,postman,vscode"/></p>

<br>

---

## Featured Projects

### 🧠 MindEase — AI-Powered Mental Wellness Platform

<p>
  <img src="https://img.shields.io/badge/⭐-Recommended_First_Look-FFD43B?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Active-2EA44F?style=flat-square"/>
  <img src="https://img.shields.io/badge/Repository-Public-181717?style=flat-square"/>
  <img src="https://img.shields.io/badge/Deployment-Live-2EA44F?style=flat-square"/>
</p>

**Impact:** Combines self-assessment, AI-assisted support, and progress tracking into a single connected flow instead of separate tools.

<p>
  <a href="https://mindeasewell.netlify.app"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=netlify&logoColor=white"/></a>
  <a href="https://github.com/Devanshrocks4/MindEase"><img src="https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

**Overview**
Solves the friction of switching between separate apps for self-assessment, AI support, and progress tracking. Built for individuals who want lightweight, private check-ins rather than a full clinical platform. The engineering challenge was keeping AI conversation state in sync with structured, scored assessment data in real time. Implemented with Firebase Auth, JWT-protected REST APIs, and Socket.IO for live updates.

**Tech Stack:** React · Express · MongoDB · Firebase Auth · Google Gemini AI · Socket.IO · Tailwind CSS

**Key Features**
- Google Gemini AI integration for conversational support
- Firebase Authentication with JWT-protected API routes
- Real-time chat via Socket.IO
- Structured assessments with scoring logic
- Wellness dashboard with progress tracking
- Role-based access control

**Architecture**
```
Client (React) → Firebase Auth → Express API (JWT middleware) → Gemini AI / MongoDB → Dashboard Analytics
```

**Visual Placement Guide**
- 🖼 Hero screenshot — top of this card — *"MindEase dashboard overview"*
- 🖼 Dashboard screenshot — below Overview — *"Wellness tracking dashboard with progress charts"*
- 🗺 Architecture diagram (rendered image, replacing the block above) — *"Request flow from client to AI and database layers"*
- 🎥 10–15s demo GIF — directly above Key Features — *"Assessment → AI chat → dashboard update"*

<br>

### 🚀 DynoGix — Full-Stack Operations Platform

<p>
  <img src="https://img.shields.io/badge/⭐-Recommended_First_Look-FFD43B?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Active-2EA44F?style=flat-square"/>
  <img src="https://img.shields.io/badge/Repository-Public-181717?style=flat-square"/>
  <img src="https://img.shields.io/badge/Deployment-Not_Deployed-lightgrey?style=flat-square"/>
</p>

**Impact:** Centralizes asset tracking and issue management for teams currently splitting that work across spreadsheets and ticket threads.

<p>
  <a href="https://github.com/Devanshrocks4/DynoGix"><img src="https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

**Overview**
Solves the lack of a single source of truth for internal asset and issue tracking at small/mid-size teams. Built for ops and engineering teams who need role-based visibility, not an open-access spreadsheet. Models how internal tools are actually used — status workflows, RBAC, and analytics — instead of a basic CRUD demo. Built on a layered REST API (controllers/services/models) with JWT middleware.

**Tech Stack:** React · Node.js · Express · MongoDB · JWT

**Key Features**
- JWT authentication with middleware-protected routes
- Role-based access control (RBAC)
- Asset management module
- Issue tracking with status workflows
- Analytics dashboard
- Modular REST API (controllers / services / models)

**Architecture**
```
Client (React) → Express API → JWT Middleware → Business Logic Layer → MongoDB
```

**Visual Placement Guide**
- 🖼 Hero screenshot — top of this card — *"DynoGix dashboard overview"*
- 🖼 Dashboard screenshot — below Overview — *"Asset and issue tracking dashboard"*
- 🗺 Architecture diagram (rendered image, replacing the block above) — *"Request flow through JWT middleware and business logic layer"*
- 🎥 10–15s demo GIF — directly above Key Features — *"Creating an issue → status update → dashboard refresh"*

<br>

### 💼 SkillSnap — AI-Assisted Recruitment Platform

<p>
  <img src="https://img.shields.io/badge/Status-Completed-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Repository-Public-181717?style=flat-square"/>
  <img src="https://img.shields.io/badge/Deployment-Live-2EA44F?style=flat-square"/>
</p>

**Impact:** Gives candidates and recruiters dedicated dashboards with AI-assisted matching instead of a generic job-board listing.

<p>
  <a href="https://skillsnapon.netlify.app"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=netlify&logoColor=white"/></a>
  <a href="https://github.com/Devanshrocks4/SkillSnap"><img src="https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

**Overview**
Solves the generic, one-size-fits-all experience of typical job boards. Built for candidates and recruiters who want role-specific dashboards rather than a shared inbox. The matching logic on top of a Firestore-backed data model is what separates it from a plain listings app. Built with Firebase Authentication and TypeScript throughout.

**Tech Stack:** React · TypeScript · Firebase · Firestore · Tailwind CSS

**Key Features**
- Firebase Authentication
- Firestore-backed data model
- Recruiter dashboard
- Candidate dashboard
- AI-assisted job matching workflow

**Architecture**
```
Client (React) → Firebase Auth → Firestore → AI Matching Logic → Recruiter / Candidate Dashboards
```

**Visual Placement Guide**
- 🖼 Hero screenshot — top of this card — *"SkillSnap landing / dashboard view"*
- 🖼 Dashboard screenshot — below Overview — *"Recruiter dashboard with candidate matches"*
- 🗺 Architecture diagram (rendered image, replacing the block above) — *"Data flow from Firestore to matching logic"*
- 🎥 10–15s demo GIF — directly above Key Features — *"Candidate profile → AI match → recruiter view"*

<br>

### 🌍 Fluent Voices — Organization Website Rebuild

<p>
  <img src="https://img.shields.io/badge/Status-Completed-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Repository-Public-181717?style=flat-square"/>
  <img src="https://img.shields.io/badge/Deployment-Live-2EA44F?style=flat-square"/>
</p>

**Impact:** Cut load times and simplified content updates by replacing a legacy Wix site with a component-based Astro build.

<p>
  <a href="https://fluentvoices.pages.dev"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=cloudflare&logoColor=white"/></a>
  <a href="https://github.com/Devanshrocks4/fluentvoices"><img src="https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

**Overview**
Solves slow load times and limited maintainability of a legacy Wix site. Built for a non-profit whose staff need to update content without touching code. Rebuilt the entire site in Astro + React instead of patching the existing setup — the differentiator is long-term maintainability, not just a visual refresh. Built with TypeScript, deployed redundantly across Cloudflare Pages and Netlify.

**Tech Stack:** Astro · React · TypeScript · Cloudflare Pages · Netlify

**Key Features**
- Migrated legacy Wix site to Astro + React
- Responsive layout across devices
- Improved page-load performance over the legacy site
- Deployed on Cloudflare Pages, mirrored on Netlify
- Component-based architecture for easier content updates
- TypeScript used throughout

**Architecture**
N/A — static site, no backend architecture to diagram.

**Visual Placement Guide**
- 🖼 Hero screenshot — top of this card — *"Fluent Voices homepage"*
- 🖼 Dashboard screenshot — N/A, no dashboard (static site)
- 🗺 Architecture diagram — N/A
- 🎥 10–15s demo GIF — directly above Key Features — *"Old Wix site vs. new Astro build, side by side"*

<br>

### 💻 Portfolio — Personal Site

<p>
  <img src="https://img.shields.io/badge/Status-Active-2EA44F?style=flat-square"/>
  <img src="https://img.shields.io/badge/Repository-Not_Public-lightgrey?style=flat-square"/>
  <img src="https://img.shields.io/badge/Deployment-Live-2EA44F?style=flat-square"/>
</p>

**Impact:** Primary landing point for recruiters and collaborators to review projects and experience.

<p>
  <a href="https://devanshgupta.netlify.app"><img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=flat-square&logo=netlify&logoColor=white"/></a>
</p>

**Overview**
Solves the need for a single, controlled space to present projects rather than relying only on LinkedIn or a resume PDF. Built for recruiters and collaborators doing a first-pass review. Uses Three.js and Framer Motion for an interactive feel without becoming a heavy SPA. Built with React and Tailwind CSS, deployed on Netlify.

**Tech Stack:** React · Three.js · Framer Motion · Tailwind CSS · EmailJS

**Key Features**
- Three.js for interactive visuals
- Framer Motion page transitions
- Dark / light theme toggle
- Contact form via EmailJS
- Responsive layout for mobile and desktop

**Architecture**
N/A — client-side site, no backend to diagram.

**Visual Placement Guide**
- 🖼 Hero screenshot — top of this card — *"Hero section with 3D element in motion"*
- 🖼 Dashboard screenshot — N/A
- 🗺 Architecture diagram — N/A
- 🎥 10–15s demo GIF — directly above Key Features — *"Theme toggle and page transition in action"*

<br>

### 🏥 Medoc Health — OPD Token Allocation Engine

<p>
  <img src="https://img.shields.io/badge/Status-Completed-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Repository-Not_Public-lightgrey?style=flat-square"/>
  <img src="https://img.shields.io/badge/Deployment-Not_Deployed-lightgrey?style=flat-square"/>
</p>

**Impact:** A simulated backend for hospital OPD token issuance that prioritizes emergency cases ahead of a standard FIFO queue.

*(Backend service — repository not yet public)*

**Overview**
Solves manual, error-prone token allocation in outpatient departments. Built for hospital front-desk/OPD staff who need fast, priority-aware token issuance. Separates emergency-case handling into its own priority queue instead of a single FIFO queue — the priority logic is the core engineering piece. Built with Python and Flask, with simulated patient flow for testing.

**Tech Stack:** Python · Flask

**Key Features**
- Priority queue for emergency case handling
- Doctor scheduling logic
- REST API for token issuance and queue status
- Simulated patient flow for testing
- Modular structure separating scheduling, queue, and API logic

**Architecture**
```
Front-Desk Client → Flask REST API → Priority Queue Logic → Doctor Scheduler
```

**Visual Placement Guide**
- 🖼 Hero screenshot — N/A, no UI (backend service)
- 🖼 Dashboard screenshot — N/A
- 🗺 Architecture diagram — top of this card — *"Token request flow from API to priority queue"*
- 🎥 10–15s demo GIF — N/A; consider a short terminal/API-call walkthrough instead

<br>

---

## 🚀 Currently Building

| Project | Focus | Status |
|---|---|---|
| MindEase v2 | Next iteration of the AI wellness platform | 🟢 In Progress |
| DynoGix | Expanding asset & issue management features | 🟢 In Progress |
| Java + Spring Boot Backend | REST APIs & service-layer patterns | 📘 Learning |
| DSA in Java | Problem-solving fundamentals | 📘 Learning |

<br>

---

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Devanshrocks4&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Devanshrocks4&theme=tokyonight&hide_border=true"/>
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Devanshrocks4&theme=tokyo-night&hide_border=true"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Devanshrocks4/Devanshrocks4/output/github-contribution-grid-snake-dark.svg"/>
</p>
<!-- Requires a one-time GitHub Action (snake.yml) in this repo to create the "output" branch. Until that workflow has run once, the image above will be broken. -->

**Recent Activity**
<!--START_SECTION:activity-->
<!-- Requires a one-time GitHub Action (activity.yml) in this repo. Until it runs once, this section stays empty. -->
<!--END_SECTION:activity-->

<br>

---

## Experience

**Associate Skills Counselor — Physics Wallah** *(Current)*
- Advise students on technical learning paths, translating individual goals into structured plans — similar to scoping requirements with stakeholders.
- Diagnose gaps in understanding and break down complex topics into actionable steps — analytical thinking applied daily.
- Communicate technical concepts to non-technical audiences, a skill that carries over directly to writing docs and explaining design decisions.
- Build and ship full-stack and AI-integrated side projects outside working hours.

**TCS Ninja** — Selected (Software Engineer track)

<br>

---

## Contact

<p align="center">
  <a href="https://devanshgupta.netlify.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="https://linkedin.com/in/devansh-gupta-559107255"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/Devanshrocks4"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="mailto:devanshgupta923@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
I'm actively looking for Software Engineer / Full-Stack roles where I can keep working across the stack — backend systems, APIs, and AI-assisted features. Feel free to reach out by email or LinkedIn, or look through the repositories above for a closer look at how I build.
</p>

<p align="center"><sub>Thanks for visiting 👋</sub></p>
