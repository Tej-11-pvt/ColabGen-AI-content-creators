# PromptCraft AI — The AI Content Creator Marketplace

[![HacXLerate 2026](https://img.shields.io/badge/Hackathon-HacXLerate_2026-6366f1.svg)](https://hackathons.bytexl.ai)
[![Round 1](https://img.shields.io/badge/Round-01_Submission-06b6d4.svg)]()
[![Powered By](https://img.shields.io/badge/Powered_By-Kampus.VC-8b5cf6.svg)](https://kampus.vc)
[![Partner](https://img.shields.io/badge/Organized_By-byteXL-ec4899.svg)](https://bytexl.ai)
[![License](https://img.shields.io/badge/License-Apache_2.0-10b981.svg)]()

> **Built for HacXLerate 2026 Round 1 — NBKR Institute of Science & Technology**  
> **Challenge 2: AI Content Creator Marketplace (Kampus.VC)**  
> **Team: TEAM ECHELON**

---

## 🌟 Overview

Generative AI has spawned a new class of creative professionals: AI filmmakers, generative animators, neural audio designers, and prompt engineers. However, traditional freelance platforms (Upwork, Fiverr) fail because they treat deliverables as black-box files.

**PromptCraft AI** is an AI-native marketplace connecting brands and creative agencies with verified generative creators. It solves the three fundamental pain points of the generative revolution:
1. **Verifiable Workflow Transparency**: Deep inspector for ComfyUI node graphs, positive/negative prompts, seeds, samplers, and custom LoRA checkpoints.
2. **AI-Assisted Brief Builder (Bonus Credit)**: Synthesizes structured, production-ready creative briefs from rough brand ideas in seconds.
3. **Deterministic Delivery & IP Escrow**: Milestone pipeline with timestamped frame annotations, ComfyUI JSON schema verification, and commercial copyright transfer warranty.

---

## 🎯 Evaluation Rubric Alignment (100 Points + Bonus)

| Criteria | Weight | Implementation in PromptCraft AI |
| :--- | :---: | :--- |
| **Creator Profiles & AI Portfolios** | **30%** | 8 real creator personas with 24+ AI-generated works. Deep pipeline inspector revealing prompt parameters, seed, CFG, LoRA weights, multi-stage pipelines, and downloadable ComfyUI JSON workflows. |
| **Brief Definition** | **20%** | Full structured brief builder capturing Content Type (video, stills, 3D), Aspect Ratios (16:9, 9:16, 1:1), Aesthetic Styles, Tool preferences, and Commercial-use licensing terms. |
| **Discovery & Filtering** | **25%** | Instant search + multi-faceted filtering by AI tool (Runway, Flux, ComfyUI, etc.), specialization, rate, and verification badges. **Graceful handling of empty results** with recommendations. |
| **User Experience** | **15%** | Dual-persona mode switcher (**Brand View** vs. **Creator Studio**), dark-mode glassmorphic interface, milestone progress tracking, and live simulated messaging. |
| **Presentation & Demo** | **10%** | Working real-time prototype, self-contained architecture, comprehensive documentation, and zero-setup deployment. |
| **Bonus: Creator Verification Signals** | **+5 pts** | Visible trust indicators: "Tool Verified" (API benchmark), "Workflow Verified" (deterministic reproduction), and "Identity Verified". |
| **Bonus: AI Brief Copilot** | **+5 pts** | Intelligent semantic generator transforming vague ideas into structured production briefs with 1-click publishing. |

---

## 👥 Real Creator Personas Included

1. **Elena Rostova (@elena_ai)** — *Berlin, Germany*  
   *AI Filmmaker & Commercial VFX Director* | Runway Gen-3, Flux.1, ComfyUI | $145/hr | 4.98 ⭐ (52 reviews)
2. **Marcus Chen (@marcus_promptcraft)** — *San Francisco, USA*  
   *Generative 3D Artist & Game VFX Lead* | Flux.1 Pro, Kling AI 1.5, Blender | $160/hr | 4.96 ⭐ (39 reviews)
3. **Aria Thorne (@ariathorne_ai)** — *London, UK*  
   *Virtual Influencer & Character Consistency Specialist* | ComfyUI IP-Adapter, Flux.1, SDXL | $130/hr | 4.99 ⭐ (64 reviews)
4. **Devon Miller (@devon_motion)** — *Austin, Texas*  
   *Viral Social Reels & AI Animator* | Runway Gen-3, Pika 2.0, Topaz 4K | $115/hr | 4.94 ⭐ (78 reviews)
5. **Dr. Vikram Patel (@vikram_synth)** — *Bengaluru, India*  
   *AI Audio Architect & Multi-Modal Sound Designer* | ElevenLabs, Suno v3.5, Udio | $125/hr | 4.97 ⭐ (41 reviews)
6. **Sophie Laurent (@sophie_visuals)** — *Paris, France*  
   *E-Commerce & High-End Product CGI Specialist* | Flux.1, Midjourney v6.1, Magnific AI | $150/hr | 4.99 ⭐ (56 reviews)
7. **Kai Tanaka (@kai_anime_ai)** — *Tokyo, Japan*  
   *Anime Director & Cel-Shaded Storyboard Artist* | Niji v6, AnimateDiff, EbSynth | $120/hr | 4.95 ⭐ (48 reviews)
8. **Zoe Saldana-Cruz (@zoe_ai_story)** — *Toronto, Canada*  
   *Documentary AI Stills & Historical Worldbuilder* | Midjourney v6.1, Flux.1, Claude 3.5 | $135/hr | 4.97 ⭐ (35 reviews)

---

## 🛠️ Quick Start & Local Run

### Method 1: Using Python (Zero Dependencies)
```bash
python server.py 8000
```
Open [http://localhost:8000](http://localhost:8000) in your browser.

### Method 2: Direct Browser Launch
Simply double-click `index.html` in any modern web browser! The application is 100% self-contained and functions seamlessly via client-side storage and CDN assets.

---

## 🚀 How to Publish to GitHub with Real-Time Live Preview

### Step 1: Initialize Git and Commit
```bash
git init
git add .
git commit -m "feat: PromptCraft AI - AI Content Creator Marketplace for HacXLerate 2026"
```

### Step 2: Create a Public Repository on GitHub
1. Go to [https://github.com/new](https://github.com/new)
2. Repository Name: `promptcraft-ai` or `ai-content-creator-marketplace`
3. Set visibility to **Public**
4. Click **Create repository**

### Step 3: Push to GitHub
```bash
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/promptcraft-ai.git
git branch -M main
git push -u origin main
```

### Step 4: Enable 1-Click Free GitHub Pages (Real-Time Live URL!)
1. In your GitHub repository, click **Settings** → **Pages** (under Code and automation).
2. Under **Build and deployment** → **Source**, select **Deploy from a branch**.
3. Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
4. In ~60 seconds, your real-time live website will be published at:
   ```
   https://<YOUR_GITHUB_USERNAME>.github.io/promptcraft-ai/
   ```

### Step 5: (Alternative) 1-Click Vercel / Netlify Deploy
- **Vercel**: Import the GitHub repo at [vercel.com/new](https://vercel.com/new) → Click **Deploy**. Done!
- **Netlify**: Drag and drop the project folder directly onto [app.netlify.com/drop](https://app.netlify.com/drop) for an instant live URL!

---

## 📄 Deliverables Summary

- **Working Prototype**: Full creator discovery, portfolio pipeline inspector, brief posting, and milestone escrow workflow.
- **Data Model Specification**: See [DATA_MODEL.md](DATA_MODEL.md) for entity schemas and validation parameters.
- **Submission Information**: See [SUBMISSION_NOTES.md](SUBMISSION_NOTES.md) for draft copy-paste values into the byteXL submission portal.
