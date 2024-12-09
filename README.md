# Truth Sleuth &amp; Trend Bender
## AI Agents to fact-check YouTube videos \& influence opinions
CS224V Project | Fall 2024 


**Cecile Loge ep. Baccari** | ceciloge@stanford.edu | cecileloge@google.com

**Mohammad Rehan Ghori** | rghori@stanford.edu | rehang@google.com


---

**Motivation:** Misinformation is one of the most pressing threats of our time, and YouTube videos serve as a major platform through which it can spread. Providing fact-checked information to address misleading content has been shown to be more effective than simply removing it. But even beyond this, we want to use that information to interact with users, challenge the presented narrative, keep the discussion away from hate/conspiracy and ultimately even change their minds.

Our system comprises two main agents: **Truth Sleuth** and **Trend Bender**.

**Truth Sleuth** extracts claims from a YouTube video, uses a Retrieval-Augmented Generation (RAG) approach - drawing on sources like Wikipedia, Google Search, Google FactCheck - to accurately assess their veracity and generates a nuanced and comprehensive report. Through rigorous prompt engineering, **Trend Bender** leverages this report along with a curated corpus of relevant articles to generate insightful and persuasive comments designed to stimulate a productive debate. With a carefully set up self-evaluation loop, this agent is able to iteratively improve its style and refine its output.

---
We experimented with two themes:
**Theme 1**: Dangerous Diet Recommendations & Health Claims.
**Theme 2**: Manosphere & Misogynistic videos.

---
