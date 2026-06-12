# 01. Project Title & Tagline

## Research Agent 

### AI-Powered Research Assistant for Knowledge Discovery, Literature Reviews, Trend Analysis, and Research Insights using IBM watsonx Orchestrate

Research Agent AI is an intelligent research assistant that helps researchers, students, and professionals analyze topics, summarize documents, identify research gaps, discover emerging trends, and generate structured research reports through natural language interaction.

---

# 02. Problem Statement

The rapid growth of academic, scientific, and technical information has made it increasingly difficult for researchers to efficiently discover, analyze, and organize relevant knowledge. Traditional research workflows require significant manual effort in searching literature, reviewing documents, identifying trends, and generating reports.

Research Agent AI addresses this challenge by providing an AI-powered platform that automates research assistance, document analysis, knowledge extraction, and report generation, enabling users to focus on innovation and decision-making rather than information gathering.

---
## 3. Domain

**Primary Domain:** Artificial Intelligence for Research & Education

This project falls under the **Artificial Intelligence for Research & Education** domain, specifically focused on **Agentic AI for Research Assistance**, built using **IBM watsonx Orchestrate**.

### Sub-Domains Covered
- Literature Review & Synthesis
- Trend Analysis & Discovery
- Research Gap Identification
- Innovation & Idea Generation
- Document Analysis (RAG-based)
- Natural Language Processing (NLP)

### Target Users
- Researchers & Academics
- Students
- Industry R&D Teams
- Innovators exploring new technology directions

This project falls under the **Artificial Intelligence / Machine Learning** domain, specifically focused on **Agentic AI for Research Assistance**, built using **IBM watsonx Orchestrate**.

---
## 04. Features / Capabilities

### 🔍 Literature Review
Synthesizes methodologies, outcomes, and findings across research papers into clear, structured summaries.

### 📈 Trend Discovery
Identifies emerging research signals, topic velocity, and clustering across academic domains.

### 🧩 Gap Analysis
Maps unexplored areas, limitations, and open research questions within any subject.

### 💡 Innovation Suggestions
Generates novel research ideas with:
- Novelty Score (Low / Medium / High)
- Research Potential assessment
- Feasibility, impact, and challenges
- Real-world applications

### 📄 Document Analysis
Reads and analyzes uploaded PDFs, DOCX, spreadsheets, and presentations — extracting key findings, gaps, and follow-up answers.

### 🎯 Topic Relevance Enforcement
Keeps every response strictly focused on the user's requested topic — no unrelated drift.

### 🪜 Progressive Research Exploration
Starts with a concise Executive Summary, then offers a detailed 10-section analysis on request.

### 🎛️ Selective & Full Analysis Modes
- **Selective:** Request only specific sections (e.g., "Give Research Gaps")
- **Full Analysis:** Request the complete structured report with all 10 sections

### ✅ Evidence-Based Accuracy
- No invented statistics or benchmark numbers
- Confidence levels (High / Medium / Low) for every major finding
- APA-format source citations

### 🌐 Multilingual Support
Responds in the same language the user writes in.

### 🚫 Out-of-Scope Handling
Politely redirects off-topic questions toward related research angles.

---
## 5. Technology Stack

| Component | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| AI Platform | IBM watsonx Orchestrate |
| AI Services | IBM watsonx.ai |
| AI Model | GPT-OSS 120B |
| Research Engine | Research Agent |
| Version Control | Git & GitHub |
| Development Environment | Visual Studio Code |
| Hosting | GitHub Pages |
| Security | IBM Embed Security |

---
## 06. Architecture / How It Works

User

↓

Research Agent Website (HTML/CSS/JS)

↓

IBM watsonx Web Chat Widget

↓

IBM watsonx Orchestrate Agent

↓

GPT-OSS 120B Model

↓

Research Analysis & Response Generation

↓

Structured Research Insights

↓

User

### Workflow

1. **User submits a research query** through the chat interface on the website.
2. The query is sent through the **embedded IBM watsonx chat widget**.
3. **IBM watsonx Orchestrate** processes the request and applies the configured agent guidelines (tone, response structure, evidence rules).
4. **GPT-OSS 120B** analyzes the research topic using structured reasoning.
5. The system generates **structured insights and recommendations** (Executive Summary, Key Findings, Research Gaps, Innovation Ideas, etc.).
6. **Results are displayed to the user** in the chat widget, with options to request detailed or selective sections.

---
## 07. Screenshots
## Interface Preview

**Main Landing Page**
![Research Agent Landing Page powered by IBM Watsonx](./assets/landing-page.png)

**Active Chat Interface**
![Research Agent Chat showing a React and FastAPI deployment query](./assets/agent-chat.png)


## 8  Setup

### Prerequisites
- A modern web browser (Chrome, Edge, Firefox)
- Internet connection (for IBM watsonx Orchestrate widget and Google Fonts)

### Steps

1. **Download the file**
   - Save `Landing_Page.html` to your computer.

2. **Open it**
   - Double-click `Landing_Page.html` to open it directly in your browser.
   - That's it — no installation, no build tools, no dependencies.

3. **Agent is pre-configured ✅**
   The IBM watsonx Orchestrate agent connection is already embedded in the file (see `<script>` near the bottom). The chat widget loads automatically when the page opens.

4. **Test it**
   - Scroll to the **Ask Agent** section
   - Type a research question and press Enter

5. **(Optional) Host it online**
   To share via a link instead of a local file, upload `Landing_Page.html` to:
   | Platform | How |
   |---|---|
   | GitHub Pages | Upload as `index.html` in a repo → enable Pages |
   | Netlify | Drag and drop the file into Netlify's dashboard |
   | Vercel | Drag and drop or run `vercel` |

---
## 09.Agent Behavior / Guidelines

The Research Agent is configured in **IBM watsonx Orchestrate** with the following behavior guidelines that govern how it responds:

### 1. Clear Professional Communication
Ensures responses are professional, clear, and academically oriented. Avoids jargon, slang, and casual language. Adjusts response length based on question complexity.

### 2. Innovation and Future Directions
Requires the agent to generate at least 3 novel research ideas when asked, each with a Novelty Score (Low/Medium/High), Research Potential, feasibility, impact, and real-world applications.

### 3. Evidence-Based Analysis
Enforces strict accuracy rules:
- Never invents statistics, percentages, or benchmark scores
- Uses qualitative language when verified data is unavailable
- Indicates Confidence Level (High/Medium/Low) for major findings
- Cites sources in APA format where possible

### 4. Research Response Structure
Defines a **Progressive Research Exploration** model:
- Starts with a concise Executive Summary
- Offers a detailed 10-section analysis on request:
  1. Current Research Landscape
  2. Key Findings
  3. Applications
  4. Research Gaps
  5. Innovation Opportunities
  6. Future Directions
  7. Recommended Technologies & Tools
  8. Potential Challenges
  9. Innovation Ideas
  10. Key Takeaways
- Supports **Selective Mode** (specific sections only) and **Full Analysis Mode** (all sections)

### Additional Behaviors
- **Topic Relevance Enforcement** — stays strictly on-topic, no unrelated drift
- **Out-of-Scope Handling** — politely redirects non-research queries
- **Multilingual Support** — responds in the user's input language
- **Document Analysis** — reads and summarizes uploaded PDFs, DOCX, and spreadsheets

---
## 10.Sample Queries / Usage Examples

Example Queries:

- Give me a complete analysis of Federated Learning.
- Summarize the latest trends in Artificial Intelligence.
- Identify research gaps in Blockchain Technology.
- Generate innovation ideas for Healthcare AI.
- Compare Machine Learning and Deep Learning methodologies.
- Create a literature review on Computer Vision.
- Analyze uploaded research papers and summarize key findings.