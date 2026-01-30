https://github.com/codinit-dev/.github/tree/main/profile/README.md
# 
codinit-dev
Repository navigation
Code
Issues
5
 (5)
Local-First Open Source web & mobile AI app builder — install on MacOS, Windows & Linux

codinit.dev/download
License
 MIT license
Code of conduct
 Code of conduct
Contributing
 Contributing
 190 stars
 69 forks
 6 watching
 Branches
 Tags
 Activity
 Custom properties
Public repository
codinit-dev/codinit-dev
Name	
Gerome-Elassaad
Gerome-Elassaad
last week
.github
last month
.husky
3 months ago
__tests__
last month
app
last week
assets
last month
electron
last month
functions
last month
icons
2 months ago
public
last month
scripts
last month
Repository files navigation
README
CodinIT.dev Hero

Fazier badge         CodinIT.dev badge

CodinIT.dev — Open‑Source AI App Builder
Build, manage, and deploy intelligent applications faster — directly from your browser or desktop.

Overview
CodinIT.dev is an open‑source, AI full‑stack development platform designed to help developers build modern Node.js applications with speed and precision. It combines code generation, project management, and deployment tools into a single workflow, powered by your choice of AI providers.

Whether you are prototyping, scaling a SaaS product, or experimenting with local LLMs, CodinIT.dev adapts to your stack and workflow.

Quick Start
Run as a Desktop App
Download the latest prebuilt release for macOS, Windows, and Linux.

Download Latest Release

Get up and running in minutes.

1. Clone the Repository
git clone https://github.com/codinit-dev/codinit-dev.git
cd codinit-dev
2. Install Dependencies
# npm
npm install

# or pnpm
pnpm install
3. Configure Environment
Create a .env file and add your preferred AI provider keys. You can mix and match multiple providers depending on your requirements.

4. Run the Development Server
pnpm run dev
The application will be available at: http://localhost:5173

Core Capabilities
Automated Full-Stack Engineering: Streamline the creation and management of complex Node.js architectures using intelligent generation.
Universal Model Integration: Seamlessly connect with over 19 cloud and local AI providers.
Hybrid Environment Support: native compatibility for both Web browsers and Desktop (Electron) environments.
Production-Ready Containerization: Fully Dockerized workflow with preset configurations for Vercel, Netlify, and GitHub Pages.
Integrated Development Suite: Includes robust utilities such as semantic search, diff visualization, and concurrency file-locking.
Expanded Ecosystem Connectivity: Native integration with Supabase, real-time data visualization tools, and voice-command interfaces.
Vendor-Neutral Infrastructure: A flexible architecture designed to prevent vendor lock-in, allowing dynamic switching between backend providers.
Supported AI Providers
CodinIT.dev allows you to use one provider or switch dynamically per task.

Cloud Providers
OpenAI, Anthropic, Google, Groq, xAI, DeepSeek, Cohere, Mistral, Together, Perplexity, HuggingFace, OpenRouter, and more.

Local Providers
Ollama, LM Studio, and OpenAI‑compatible local endpoints.

Deployment & Desktop Usage
Run with Docker
npm run dockerbuild
docker compose --profile development up
