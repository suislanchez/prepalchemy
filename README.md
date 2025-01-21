# PrepAlchemy: Emotionally Intelligent Professional Skills Trainer

PrepAlchemy is an AI-driven tool designed to enhance professional communication skills by simulating realistic interactions such as interviews, salary negotiations, performance reviews, investor pitches, and conflict resolution. It integrates emotional analysis and contextual tailoring to offer a comprehensive preparation experience.

---

## Features

### Emotionally Responsive AI
- **Multimodal Emotion Analysis**: Uses the Hume API to analyze text, audio, and video for emotional granularity.
- **Dynamic Response**: Adapts based on user emotions (e.g., confidence, fear, anxiety) to simulate realistic scenarios.

### Tailored Practice Sessions
- **Context-Aware Preparation**: Integrates the Google Jobs API to retrieve job descriptions, company details, and requirements.
- **Personalized Scenarios**: Customizes sessions based on user input (e.g., job role, company, prior interactions).

### Advanced Emotional Insights
- **Post-Session Analysis**: Provides detailed emotional metrics, graphs, and summaries of mood fluctuations.
- **Prosody Analysis**: Tracks vocal elements like "uhh," "umm," sighs, and more.

### Immersive UI
- **Realistic Interface**: Zoom-like experience with speaking icons and optional real-time emotion displays.
- **Adjustable Notifications**: Toggle features like mood alerts or low-confidence indicators for focus or distraction-free practice.

### Customizable Scenarios
- Multiple personalities (e.g., stern, relaxed) and the ability to simulate:
  - Behavioral and technical interviews
  - Salary negotiations
  - Investor pitches
  - Conflict resolution

---

## Core Technologies
- **[Hume API](https://github.com/HumeAI/hume-api-examples)**: Emotion analysis via multimodal inputs (text, audio, video).
- **[Google Jobs API](https://serpapi.com/google-jobs-api)**: Real-time job data for tailored interview sessions.
- **[Next.js](https://nextjs.org/)**: Frontend framework for an interactive user experience.
- **LLMs (e.g., GPT-4)**: Advanced conversational capabilities, tailored to resumes, LinkedIn profiles, and portfolios.

---

## Example Use Cases

### Job Interview Practice
- Receive company insights and context-specific questions for a role at JP Morgan.  
- Identify emotional triggers during tough questions and practice responses.

### Investor Pitch Preparation
- Simulate high-stakes presentations with an emotionally responsive audience.  
- Get feedback on confidence levels, vocal delivery, and clarity.

---

## Benefits Over Traditional Methods
- **Cost-Effective**: Affordable compared to mock interviews.  
- **Unbiased Feedback**: AI provides objective emotional insights.  
- **Realistic Simulation**: Emulates real-world stressors better than friends or family.  

---

## Future Plans
1. Add more personality types and situational templates.
2. Expand to simulate **panel interviews** with multiple interviewers.  
3. Implement advanced analytics with real-time emotion tracking and comprehensive post-session reports.  

---

## Getting Started

### Prerequisites
- Node.js and npm installed on your machine.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PrepAlchemy.git
   cd PrepAlchemy
