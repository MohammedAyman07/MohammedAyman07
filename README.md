<div align="center">

<img src="./banner.svg" alt="Mohammed Ayman S — Full-Stack & AI Software Engineer" width="100%" />

# Mohammed Ayman S
### **Full-Stack Software Engineer · AI Systems & WebGL · Production-Ready Applications**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-ayman-s-661396289)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MohammedAyman07)
[![Live Deployments](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/MohammedAyman07)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohammedayman770@gmail.com)

<p align="center">
  <strong>Building reliable, user-first web applications with modern TypeScript/React, multi-model AI architectures, cryptographic security, and hardware-accelerated 3D graphics.</strong>
</p>

</div>

---

## 👨‍💻 About Me

I am a software engineer focused on turning complex engineering challenges into clean, accessible, and high-performance digital products. My work spans the full lifecycle of software development: from architecting serverless cloud backends and integrating cryptographic payment pipelines to orchestrating multi-LLM AI models and crafting 60fps WebGL interactive experiences.

- 🔭 **What I’m Building:** Full-stack AI applications, production e-commerce architectures, and developer tooling.
- ⚙️ **Core Engineering Focus:** Zero-latency UX, multi-provider API failovers, cryptographic signature verification (HMAC-SHA256), and responsive, accessible interfaces.
- 💼 **Career Goal:** Open for **Full-Stack Software Engineer**, **Frontend Engineer (React/TypeScript)**, and **AI Application Engineer** roles.

---

## 🛠 Technical Skills & Ecosystem

<table>
  <tr>
    <td width="25%"><strong>Frontend & UI</strong></td>
    <td>
      <code>TypeScript</code> · <code>JavaScript (ES6+)</code> · <code>React 19</code> · <code>Next.js / Vite</code> · <code>Tailwind CSS</code> · <code>KaTeX Math Engine</code> · <code>HTML5 / CSS3</code> · <code>Framer Motion</code>
    </td>
  </tr>
  <tr>
    <td><strong>Backend & APIs</strong></td>
    <td>
      <code>Node.js</code> · <code>Python (Flask)</code> · <code>Express.js</code> · <code>Vercel Serverless Functions</code> · <code>RESTful APIs</code> · <code>JWT Authentication</code> · <code>CORS / Webhooks</code>
    </td>
  </tr>
  <tr>
    <td><strong>AI / ML & Orchestration</strong></td>
    <td>
      <code>Google Gemini 2.5 Flash</code> · <code>Groq Cloud (Llama 3.3 70B, Qwen)</code> · <code>Hugging Face (FLUX.1 Diffusion)</code> · <code>Multi-LLM Fallback Architecture</code> · <code>Prompt Engineering</code>
    </td>
  </tr>
  <tr>
    <td><strong>Security & Payments</strong></td>
    <td>
      <code>Razorpay Payment Gateway</code> · <code>HMAC-SHA256 Cryptographic Verification</code> · <code>Google OAuth 2.0</code> · <code>Zero-Trust API Key Isolation</code> · <code>Rate Limiting</code>
    </td>
  </tr>
  <tr>
    <td><strong>3D Graphics & E-Commerce</strong></td>
    <td>
      <code>Three.js</code> · <code>WebGL Shader / Canvas Optimization</code> · <code>Shopify Liquid</code> · <code>Storefront APIs</code> · <code>Godot Engine (GDScript)</code>
    </td>
  </tr>
  <tr>
    <td><strong>DevOps & Tools</strong></td>
    <td>
      <code>Git</code> · <code>GitHub Actions (CI/CD)</code> · <code>Vercel Cloud</code> · <code>npm</code> · <code>Postman</code> · <code>Lighthouse Auditing (95+ Scores)</code>
    </td>
  </tr>
</table>

---

## 🚀 Featured Production Projects

### 1. [AYMAN STUDY AI — Full-Stack AI STEM Learning Platform](https://github.com/MohammedAyman07/ayman-study-ai)
> **Multi-LLM educational platform with real-time KaTeX mathematical rendering, Google OAuth authentication, and cryptographically verified payment processing.**

- **Architecture & System Design:**
  - Implemented an automated multi-model fallback pipeline: if the primary high-throughput LLM (`Groq Llama-3.3-70b`) experiences rate limits or network latency, queries seamlessly transition to `Google Gemini 2.5 Flash` with zero client interruption.
  - Engineered a mathematical parsing engine transforming LaTeX formatting into responsive, real-time math notation via `rehype-katex` and `remark-math`.
  - Built full serverless backend endpoints (`/api/auth`, `/api/chat`, `/api/payment`) featuring strict JWT token validation, user state persistence, and credit-metered access.
- **Cryptographic Security:** End-to-end Razorpay integration with server-side HMAC-SHA256 signature verification matching `crypto.createHmac('sha256', secret)` against webhooks before crediting transactions.
- **Stack:** `React 19` · `TypeScript` · `Tailwind CSS` · `Vite` · `Vercel Serverless` · `Google OAuth 2.0` · `Razorpay` · `KaTeX`
- 🌐 **Live Demo:** [ayman-study-ai.vercel.app](https://ayman-study-ai.vercel.app)

---

### 2. [DailyScroll — 3D WebGL Hardware-Accelerated Shopify Storefront](https://github.com/MohammedAyman07/dailyscroll-shopify-theme)
> **Ultra-responsive dark-mode e-commerce storefront driven by an interactive 3D WebGL hero orb and dependency-free Vanilla JS architecture.**

- **Architecture & Performance:**
  - Designed an interactive 3D procedural sphere using `Three.js` and WebGL with custom lighting, point lights, and dynamic mouse-tracking physics.
  - Maintained 60fps animations by managing render loops with `requestAnimationFrame` and clamping WebGL canvas pixel ratios for lower-end hardware.
  - Utilized `IntersectionObserver` for non-blocking scroll reveal animations and zero-layout-shift UI interactions.
  - Built a Node.js static generation pipeline (`build.js`) extracting native `.liquid` templates into lightweight HTML previews for instant public accessibility.
- **Stack:** `Shopify Liquid` · `JavaScript (ES6+)` · `Three.js / WebGL` · `CSS3 Grid/Flexbox` · `Node.js` · `Vercel`
- 🌐 **Live Demo:** [dailyscroll-shopify-theme.vercel.app](https://dailyscroll-shopify-theme.vercel.app/)

---

### 3. [AI Image Generator — Generative Diffusion Web App](https://github.com/MohammedAyman07/ai-image-generator)
> **Lightweight text-to-image application generating high-resolution digital art using the state-of-the-art FLUX.1 diffusion model.**

- **Architecture & Highlights:**
  - Built a clean Python & Flask backend interfacing with the Hugging Face Serverless Inference API for low-latency image generation.
  - Developed a modern, glassmorphic UI with prompt sanitization, real-time loading feedback, and direct one-click asset downloads.
  - Packaged and configured for instant zero-cold-start cloud deployment on Vercel.
- **Stack:** `Python` · `Flask` · `Hugging Face API (FLUX.1)` · `HTML5 / CSS3` · `Vercel Cloud`
- 🌐 **Live Demo:** [ai-image-generator-three-iota.vercel.app](https://ai-image-generator-three-iota.vercel.app/)

---

### 4. [AY WebSelling — Digital Asset Marketplace](https://github.com/MohammedAyman07/aywebselling-marketplace)
> **High-speed static digital marketplace and SSG pipeline for responsive web templates and developer assets.**

- **Architecture & Highlights:**
  - Optimized client-side template discovery with instant category filtering, real-time modal previews, and cart drawer management.
  - Scored 99+ on Google Lighthouse across Performance, Accessibility, Best Practices, and SEO.
- **Stack:** `JavaScript (ES6+)` · `HTML5 Semantic Markup` · `Modular CSS` · `SSG Pipeline` · `Vercel CDN`
- 🌐 **Live Demo:** [aywebselling-marketplace.vercel.app](https://aywebselling-marketplace.vercel.app)

---

### 5. [Padimachi — Engineering & Academic Resource Portal](https://github.com/MohammedAyman07/padimachi-education-portal)
> **Curriculum-aligned educational platform providing structured study guides, chapter solutions, and synthesized audio walkthroughs for university students.**

- **Architecture & Highlights:**
  - Built an integrated audio answer player utilizing the Web Speech API to provide auditory accessibility for technical textbook questions.
  - Organized hierarchical subject trees for engineering mathematics, physics, and programming foundations.
- **Stack:** `HTML5` · `CSS3` · `JavaScript` · `Web Speech API` · `Responsive UI Design`
- 🌐 **Live Demo:** [padimachi-education-portal.vercel.app](https://padimachi-education-portal.vercel.app/)

---

## 💡 Engineering Philosophy & Coding Standards

```text
┌────────────────────────────────────────────────────────────────────────┐
│ 1. PRODUCTION OVER PROTOTYPES                                         │
│    Code is only as valuable as its reliability in the hands of users. │
│    Every project is deployed live with zero console errors.           │
│                                                                        │
│ 2. DEFENSIVE SECURITY BY DEFAULT                                       │
│    Zero client-side secrets. Cryptographic validation (HMAC-SHA256)   │
│    for all financial webhooks, sanitized inputs, and isolated tokens. │
│                                                                        │
│ 3. PERFORMANCE & ACCESSIBILITY FIRST                                  │
│    Sub-second load times, 60fps animations with requestAnimationFrame, │
│    semantic HTML, and strict Lighthouse optimization (95+ score).     │
│                                                                        │
│ 4. RESILIENT ARCHITECTURE                                              │
│    Always build multi-provider failover strategies for external APIs  │
│    so users never see a broken screen when a third party is down.     │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=MohammedAyman07&show_icons=true&theme=tokyonight&hide_border=true" height="165" alt="Mohammed Ayman's GitHub Stats" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=MohammedAyman07&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="165" alt="Top Languages" />
</div>

---

## 🤝 Let's Connect & Collaborate

I am actively open to discussing **Software Engineering**, **Full-Stack Development**, and **Frontend Engineering** opportunities. Whether you have an open role, an interesting technical challenge, or want to discuss system architecture, feel free to reach out!

<div align="center">

[![LinkedIn Profile](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-ayman-s-661396289)
[![GitHub Profile](https://img.shields.io/badge/Follow%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MohammedAyman07)
[![Send an Email](https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohammedayman770@gmail.com)

**Mohammed Ayman S · Chennai, India**

</div>
