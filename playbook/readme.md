# AI Search (AEO/GEO) Playbook
 
**Author:** Anuj Singh <br>
**Sources reviewed:** video interviews+ podcasts + LinkedIn posts (major sources listed below)
## Sources
 
| # | Expert | Role | Source | Date |
|---|--------|------|--------|------|
| 1 | Chris Long | Co-founder, Nectiv | [YouTube interview](https://www.youtube.com/watch?v=XvN2uW4Fj2Q) (Athena HQ podcast, w/ Andrew Jan) | 12-05-2026 |
| 2 | Aleyda Solis | SEO Consultant & Founder | [YouTube interview](https://www.youtube.com/watch?v=B53DjAE8IK4) ("SEO in 2026" series, w/ David Bain) | 22-12-2025 |
| 3 | Ryan Law | Director of Content Marketing, Ahrefs | [YouTube interview](https://www.youtube.com/watch?v=mL1W1SMtTT4) (Ahrefs podcast) | 28-10-2025 |
| 4 | Mike King | — | [LinkedIn post 1](https://www.linkedin.com/posts/michaelkingphilly_a-few-years-ago-i-made-a-free-tool-for-the-activity-7472356605599039488-doIf) / [post 2](https://www.linkedin.com/posts/michaelkingphilly_beyond-rag-why-every-ai-search-platform-activity-7462828552837820416-NHCA) 
| 5 | Aleyda Solis | — | [LinkedIn post](https://lnkd.in/p/gBKJBHAR) 
| 6 | Ryan Law | — | [LinkedIn post](https://www.linkedin.com/posts/thinkingslow_many-companies-are-unwilling-to-publish-ai-activity-7487429197578080256-ONfO)
| 7 | Chris Long | — | [post 1](https://www.linkedin.com/posts/chris-long-marketing_new-seo-research-this-study-found-that-reddit-activity-7486419937591484417-9tsj) / [post 2](https://www.linkedin.com/posts/chris-long-marketing_seo-tip-crawl-your-landing-pages-with-screaming-activity-7486110395955359745-opol) 

## 1. Objective
 
**What AI search optimization (AEO/GEO) is.**
AEO/GEO is best understood as an evolution of traditional SEO rather than a break from it. AI-powered-SEO inherits the underlying discipline (technical health, authoritative content, off-page authority) and layers AI-specific tactics on top, with the goal of getting a brand recommended and directly cited inside AI-generated chat answers (ChatGPT, Claude, Perplexity, Google AI Mode/Overviews, Gemini), not just ranked in a list of blue links. The inheritance is not just conceptual, Chris Long notes that many of these AI systems are still fundamentally built on top of Google's own indexing and search infrastructure, and that improving standard Google rankings measurably improves visibility in AI search as well, because tools like ChatGPT largely rely on a web index (likely Google's) rather than pure internal knowledge to generate answers. On top of that inherited SEO foundation, most AI systems add a retrieval-augmented generation (RAG) layer; a large language model paired with a live search layer that fetches documents and synthesizes an answer from them,<br> which is the "AI boost" that makes AEO a distinct discipline rather than pure SEO. Because of this added layer, AEO strategy has to span more surfaces than SEO did — Chris Long frames it as four separate ecosystems a brand needs a presence in: your own site, Reddit, third-party/affiliate sites, and YouTube/video.
 
**What business problems it solves.**
- *Discovery without clicks.* Buyers are increasingly using AI as a discovery layer and Google as a verification layer, meaning a large share of the buying journey now happens where you have no direct analytics visibility (source: Chris Long, citing a Winter/CMO survey report).
- *Brand perception risk.* An estimated 90% of B2B procurement now uses AI in some form (source: Chris Long, citing Forrester data) — meaning how AI characterizes your brand can stall or kill deals before a human on your team ever hears about them.
- *Traffic reality check.* Falling organic traffic is more often caused by Google's own AI Overviews eating clicks than by users switching to ChatGPT outright — actual migration away from Google search hasn't happened at scale (source: Ryan Law, citing Rand Fishkin's clickstream research, [YouTube interview](https://www.youtube.com/watch?v=mL1W1SMtTT4)).
**Success metrics.**
Traditional SEO metrics (rankings, sessions) undersell what's actually happening. What the sources actually recommend tracking:
- Branded web mentions — the single strongest correlate Ahrefs found with appearing in AI Overviews (~0.67 correlation) (source: Ryan Law, ).
- Citation count and citation *sentiment/accuracy* — not just whether you're mentioned, but whether the AI characterizes you correctly (source: Aleyda Solis, 22-12-2025).
- Conversion rate over raw traffic — several sources report AI-referred visitors convert better because they arrive further down the funnel (source: Chris Long; source: Mike King).

---
 
## 2. Prerequisites


**Required skills / mindset.** <br>
Some-experts call this discipline "relevance engineering": the intersection of information retrieval, content strategy, AI, digital PR, and UX is explicit that it draws on different skills than classic SEO execution (search operators, Search Console configuration). AEO can't be run as a siloed function the way SEO historically has been; it needs cross-functional access to social, video, and content teams, since visibility now spans channels no single SEO team owns.
 
**AI tools.** <br>
ChatGPT, Claude, and Gemini each get used for different jobs rather than one tool covering everything, experts report using Gemini for imagery and Docs-based work, Claude for cross-computer agentic tasks, and ChatGPT for quick mobile answers.
 
**AI-search-specific tracking tools.**
- **Ahrefs Brand Radar** <br> Ahrefs' AI brand-monitoring module, tracking mentions, citations, and share of voice across ChatGPT, Perplexity, Gemini, Copilot, and Google's AI Overviews/AI Mode. It's built into Ahrefs' existing Site Explorer rather than a separate product. Ryan Law's own reported correlation stat (branded mentions vs. AI Overview appearance) comes from this same data set (source: Ryan Law; general product description via web search, current as of this writing).
- **AthenaHQ** <br>A dedicated GEO platform (not affiliated with Ahrefs) that tracks brand visibility across a similar set of AI platforms and layers on content recommendations. Chris Long references it as a tool for competitor gap analysis (source: Chris Long; general product description via web search).
- **SparkToro, buzzabout.ai, Similarweb**<br> audience and topic-discovery tools for understanding where an audience already congregates before creating content aimed at them (source: Aleyda Solis).
relevant note: GA-style analytics tends to undercount AI-influenced conversions, due to cookie consent, GDPR, and JavaScript-rendering gaps in how AI referral traffic gets tracked (source: Ryan Law) 
---
