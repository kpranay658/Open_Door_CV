# 🚪 OpenDoorCV

> **The CV Builder Born from Frustration.**
> Free. Powerful. For everyone. Forever.

![OpenDoorCV Banner](https://img.shields.io/badge/OpenDoorCV-Free%20Forever-7c5cfc?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xOSAzSDVhMiAyIDAgMDAtMiAydjE0YTIgMiAwIDAwMiAyaDE0YTIgMiAwIDAwMi0yVjVhMiAyIDAgMDAtMi0yem0tNyAxM0g3di0yaDV2MnptNS00SDd2LTJoMTB2MnptMC00SDd2LTJoMTB2MnoiLz48L3N2Zz4=)
![Status](https://img.shields.io/badge/Status-Live-14b8a6?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-ec4899?style=for-the-badge)
![Made in India](https://img.shields.io/badge/Made%20in-India%20🇮🇳-f59e0b?style=for-the-badge)

---

## ✨ What is OpenDoorCV?

For years, building a clean, genuinely custom resume meant hitting a paywall. Every tool charged ₹800–₹2000/month just to download your own resume.

**So I built the solution.**

OpenDoorCV combines the internet's most effective, recruiter-tested CV prompts into a single, powerhouse AI tool. No subscriptions. No watermarks. No paywalls. Just you and your best resume.

---

## 🔥 What makes OpenDoorCV different?

| Feature | OpenDoorCV | Other CV tools |
|---|---|---|
| Price | **Free** | ₹800–₹2000/month |
| ATS Score & Analysis | ✅ | Paywalled |
| Cover Letter Generator | ✅ | Paywalled |
| Interview Prep | ✅ | Paywalled |
| LinkedIn About Generator | ✅ | Not available |
| Watermark-free download | ✅ | Paywalled |
| Custom color & font | ✅ | Limited |
| Single/Double column layout | ✅ | Limited |
| Industry-specific tailoring | ✅ | Not available |
| Upload PDF/DOCX or paste | ✅ | Limited |
| Drag-and-drop section reorder | ✅ | Not available |
| Prompt-engineered for recruiters | ✅ ← **This is the edge** | Generic AI |

### 🧠 The real difference — the prompts

Anyone can ask an AI to "write my resume." What makes OpenDoorCV genuinely better is that every generation runs through **battle-tested, recruiter-aligned prompts** that have been researched, refined, and engineered specifically to:

- Pass ATS (Applicant Tracking Systems) filters
- Use the right action verbs for each industry — never repeated, never generic
- Quantify achievements the way hiring managers actually read them
- Match the tone and language of the job description
- Flag and fix red flags like gaps and vague job titles
- Avoid the generic "AI-sounding" phrasing that's easy to spot from a mile away (no "results-driven," "detail-oriented," or other resume clichés)

You get expert-level prompting baked in — **without needing to know how to prompt AI yourself.**

---

## 🛠️ Features

- **🤖 AI Resume Builder** — Paste your details + job description, get a fully tailored resume in seconds
- **📎 Upload or paste** — Drop in a PDF, Word (`.docx`), or `.txt` file, or just paste your CV text directly
- **📊 ATS Score** — Know exactly how your resume performs before you send it
- **📝 Cover Letter Generator** — Role-specific, not generic
- **🎤 Interview Prep** — STAR-format answers tailored to your role
- **💼 LinkedIn About Generator** — Turn your CV into a magnetic LinkedIn profile
- **🎨 Full customization** — Colors, fonts, single/double column layouts
- **🔀 Drag-and-drop section reordering** — Rearrange Summary, Experience, Education, and other sections by hand before exporting (with arrow buttons too, for touch devices)
- **🏷️ Industry-aware generation** — Pick your field (Data, VFX, Design, Finance, Academic, and more) and the AI adapts tone and structure accordingly
- **✍️ Custom style requests** — Tell it what you want (specific tool names, a particular tone, layout quirks) and it'll work that in
- **📚 Resume History** — Access and prefill from past resumes
- **📄 One-click download** — Clean, print-ready PDF, Word, or text — no watermarks, ever

---

## 🚀 How to use

1. Visit **[OpenDoorCV](https://kpranay658.github.io/Open_Door_CV/)**
2. Upload your existing CV (PDF/DOCX) or paste it directly, then paste the job description
3. Customize colors, fonts, layout, and industry if you'd like
4. Hit generate — your first resume is **free, no setup required**
5. From your second resume onward, you'll be asked for your own free Gemini API key (see below) — this keeps the tool sustainable for everyone

> **Why do I need my own API key after the first try?**
> OpenDoorCV runs entirely in your browser with no backend server — which is what keeps it free and open source. Your first generation runs on a small shared key built into the tool. After that, you'll need your own free Gemini key (no credit card required) so the tool doesn't run out of shared capacity. Your key stays in your browser only — it's never sent to or stored on any OpenDoorCV server, only to Google's own API.

---

## ⚙️ Built with

- Vanilla HTML, CSS, JavaScript — zero frameworks, zero dependencies
- **Google Gemini API** — for resume, cover letter, and interview prep generation
- **pdf.js** and **mammoth.js** — for reading uploaded PDF and Word files client-side
- **docx** (docx-js) — for generating downloadable Word documents
- GitHub Pages — for free hosting

> **A note on the AI provider:** OpenDoorCV originally used the Anthropic Claude API, but Anthropic's free tier was discontinued, requiring a minimum $5 paid credit purchase to use. To keep this tool genuinely accessible with **zero cost barrier**, it now runs on Google's Gemini API, which offers a generous free tier with no credit card required to get started.

---

## 🤝 Built with Claude

While the app itself calls the Gemini API at runtime, OpenDoorCV's code — the UI, the feature set, and the resume-writing prompts — was built through conversation with **[Claude](https://www.anthropic.com/claude)**, iterating feature by feature (file upload, section reordering, ATS scoring, etc.) rather than writing every line by hand.

A big part of what made this work was **prompt engineering** — describing each feature precisely, giving concrete examples of the desired behavior, and iterating in small, testable steps instead of asking for everything at once. The same discipline carries through into the app itself: the resume-generation prompts baked into OpenDoorCV are themselves a product of that process, refined specifically to produce ATS-friendly, recruiter-aligned output instead of generic AI-sounding text.

If you're curious about prompting AI tools effectively for your own projects, Anthropic's [prompt engineering guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview) is a solid place to start.

---

## 💬 A note on the future

This is the **free, open trial version** of OpenDoorCV.

If this project gains traction and real users find genuine value in it, I plan to:
- Move the API key off the client entirely using a lightweight serverless proxy (Cloudflare Workers), so usage limits can be enforced properly and no key needs to live in the browser
- Possibly launch a hosted version where API costs are covered — at a **nominal charge far below any competitor.** Think ₹99/month or a ₹499 lifetime deal, not the ₹2000/month other CV tools charge

The goal has always been the same: **a better career shouldn't cost a thing.** Any future pricing will only exist to keep the lights on — never to profit off job seekers.

---

## 👤 About the creator

**Pranay Kumar** — Data Analyst & Developer

With a foundation in engineering and hands-on experience in data annotation, I bridge the gap between raw data and strategic decisions. I build practical web tools to solve everyday career bottlenecks because I believe data and great career tools should be accessible to everyone.

- 🔗 [LinkedIn](https://www.linkedin.com/in/kpranay658/)
- 🐙 [GitHub](https://github.com/kpranay658)
- 📸 [Instagram](https://www.instagram.com/pk_thehuman_658/?hl=en)

---

## ⭐ Support the project

If OpenDoorCV helped you land an interview or saved you money on a CV tool, consider:
- **Starring this repo** ⭐ — it helps more people find it
- **Sharing it** with someone job hunting right now
- **Opening an issue** if you find a bug or have a feature idea

---

## 📄 License

MIT — free to use, fork, and build upon. Just don't charge people for it. 🙏

---

<div align="center">
  <strong>Made with ❤️ in India · Free forever · No paywalls</strong>
</div>
