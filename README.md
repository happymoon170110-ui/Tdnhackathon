# TDNHackathon Project - 3rd Prize Winner

A rapid AI integration project developed in 6 hours for TDNHackathon, deploying global AI models via Google Colab, Claude, and Canva.

## Project Links and Demos
* Technical AI Demo: [Open Google Colab Notebook](https://colab.research.google.com/drive/1NH51SPexjWIF4Pr_QvDn9EYejZL0ueIo?usp=sharing)
* Web UI and system prototype: [Open Web Demo Link](https://traffic-solver-platf-n27x.bolt.host)
   * Reviewer Account - Email: `smartsignal@outliers.com` | Password: `smartsignal#123`
* Presentation and Pitch Deck: [View Canva Presentation](https://canva.link/s37759dz893h8yu)
## 🚀 Quick Start & Demo Instructions
Because the computer vision model requires backend computing resources to process traffic camera feeds in real-time, the AI engine must be initialized before using the Web UI.

**Step 1: Initialize the AI Backend (Google Colab)**
1. Open the **Technical AI Demo** (Google Colab Notebook) linked above.
2. Click `Runtime` > `Run all` (or press `Ctrl + F9`) to install dependencies and start the YOLOv8 model.
3. Scroll to the bottom of the notebook and wait for a public `gradio.live` URL to be generated. You can test the AI logic directly via this link.

**Step 2: Experience the Web UI**
1. Once the backend is running, open the **Web UI and System Prototype** link.
2. Log in using the reviewer account provided above: 
   * **Email:** `smartsignal@outliers.com`
   * **Password:** `smartsignal#123`
3. 3. Make sure you reload the page or click f5 to reload. Then, navigate directly to tab **"Hệ Thống AI"** (AI System) on the navigation bar to experience the integrated dashboard.
4. **Testing Tip:** You can download a sample traffic image, upload the image to the web, and click Phân tích ảnh and Tính đèn xanh. Now, explore it seemlessly.

## Project Overview and Methodology
* Time Constraint: Built, tested, and finalized the prototype within a strict 6-hour limit under hackathon pressure.
* Core Approach: Instead of training machine learning models from scratch, the team focused on integrating global AI models using prompt engineering, workflow logic, and rapid prototyping.
* System Workflow:
    * Google Colab: Developed the technical demo and backend logic.
    * Claude (Interface): Deployed as the conversational AI prototype.
    * Claude (Synthesis): Utilized to compile data and refine system logic.
    * Canva: Used to structure the project results and create the final pitch.

## Tech Stack and Tools
* AI Foundation: Anthropic Claude, Python AI ecosystem, Antigravity ADE, AI studio
* Development Environment: Google Colab
* Design and Presentation: Canva

## Core Team & Contribution Breakdown
* Nguyen Dang Minh - Team Leader, Lead AI Architect, Vibe coder,and Co-Presenter
    * Responsibilities: Spearheaded the entire project development; engineered the core AI pipeline (YOLOv8 deployment, camera feed processing, and Singapore's Cosnos model integration); independently architecture the system integration post-hackathon to unify the web UI and simulation modules into a single framework
* Nguyen Viet Hung - Web UI/UX Designer, vibe coder, and Co-Presenter
    * Responsibilities: Architected the main web interface, designed custom feature modules, and integrated live external APIs for weather and road surface conditions.
* Tran Huu Tho - Simulation Engineer (Part 2), vibe coder, and Co-Presenter
    * Responsibilities: Designed and developed the independent traffic congestion simulation system analyzing vehicle quantities versus velocity.
* Du My Nghi - Researcher, Presentation Builder, and Co-Presenter
    * Responsibilities: Conducted background research on traffic data, structured analytical findings, and co-built the presentation.
* Nguyen Le Mai Anh - Researcher, Presentation Builder, and Co-Presenter
    * Responsibilities: Conducted background research on smart city frameworks, compiled system documentation, and co-built the presentation.
