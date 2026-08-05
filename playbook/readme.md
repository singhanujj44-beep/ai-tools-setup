# AI Search (AEO/GEO) Playbook(with SOP)
 
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
## 3. End-to-End Workflow
 
1. Topic & entity research
2. Off-page ecosystem mapping (competitor gap analysis)
3. Content brief creation
4. AI-assisted drafting
5. Human editing & fact-check
6. On-page technical optimization for AI crawlers
7. Off-page distribution (Reddit, YouTube, affiliates, digital PR)
8. Publishing
9. Performance & citation monitoring
10. Content refresh cycle
---
 
## 4. SOP for Each Stage
 
### 4.1 Topic & Entity Research SOP
1. Input business niche/vertical into a citation-mapping tool (e.g. Brand Radar) to see which domains and pages are most commonly cited by AI systems for that niche.
2. Run a competitor "entity gap" comparison — pull conversations where a competitor is mentioned and your brand is not. This reveals topics where the AI's "understanding" of your brand has a gap it doesn't have for competitors.
3. Segment findings by vertical rather than applying generic benchmarks — Reddit matters heavily for some verticals (regulated industries, consumer products) and much less for others; the highest-performing teams segment down instead of using catch-all data studies.
4. Cross-check discovered topics against your own subject-matter expertise — avoid chasing topics just because they're trending in citation data if they're not on-brand or backed by real in-house expertise.
5. Document rationale for each topic selected, including which ecosystem (own site / Reddit / affiliate / YouTube) it's meant to win in.
### 4.2 Competitor & Off-Page Ecosystem Analysis SOP
1. Identify the "off-page SEO era" reality: content about your brand on other domains can matter more for AI visibility than your own site content, even without a backlink.
2. Map the four ecosystems (own site, Reddit, third-party/affiliate, YouTube) and note where competitors have a presence you don't.
3. Identify high-authority niche third-party/affiliate sites relevant to your vertical — even ones a broad industry study wouldn't surface, since niche affiliate authority can dominate citations for specific product categories.
4. Document a prioritized "where to get mentioned" list with a rough allocation of effort/budget per channel.
### 4.3 Content Brief Creation SOP
1. State the brief's single clear topic — avoid briefs that span multiple ideas, since diluted-topic pages reduce machine-parsed relevance per passage.
2. Require BLUF (bottom-line-up-front) structure: open every section with the clearest, most direct statement of the point before elaborating.
3. Require declarative, confident sentence structure over hedged language.
4. Flag whether the piece needs SME (subject-matter-expert) input or can be produced by the content/AI system alone.
5. Note freshness commitment — pages that are updated more recently are more likely to be preferred by ChatGPT/Copilot/Gemini in RAG retrieval than older, higher-authority organic-ranking pages.
### 4.4 AI-Assisted Drafting SOP
1. Break the brief into components and draft prompts per component rather than a single "write me 1,000 words" prompt.
2. Where relevant, ground drafting in a custom index/data source (a lightweight RAG pipeline over your own real data) rather than the model's general knowledge.
3. Use AI to accelerate, not replace — content produced without real human expertise and brand voice behind it tends toward generic, sometimes wrong output.
4. For regulated industries, route through a compliance-review layer (human or AI-assisted compliance-check agent) before publishing.
### 4.5 Human Editing SOP
1. Review for brand alignment — ask "is this actually on-brand," not just "is this accurate."
2. Review for UX quality, not just correctness — high bounce/low time-on-site is a common failure mode of unedited AI content.
3. Track "AI as bottleneck vs. human as bottleneck" as a proxy quality metric for your content system — if humans are the bottleneck, the system is working.
### 4.6 On-Page Technical Optimization SOP
1. Check page speed specifically for real-time-fetching AI crawlers (ChatGPT, Perplexity) — these give up and skip slow pages, logged as `499` server responses, which most SEO tools won't flag by default.
2. Minimize reliance on JavaScript for critical content — most AI crawlers don't render JS as reliably as modern Google crawling does.
3. Structure content in short, single-topic paragraphs with clear headers (chunking-friendly formatting) to align with passage-level retrieval.
4. Increase entity richness — mention related brands, topics, and discrete concepts explicitly, since AI systems appear to weight entity-dense text more heavily in citation likelihood.
5. Add periodic "document context" reminders in long pages so meaning survives if a page is chunked for retrieval.
### 4.7 Internal Linking SOP
Link your content to:<br>
Related guides,
Supporting tutorials,
Category pages,
Product or service pages<br>
Use descriptive anchor text (e.g., "keyword clustering guide" instead of "click here")
 
### 4.8 Off-Page Distribution SOP
1. Prioritize by ecosystem weight for your specific vertical rather than a one-size-fits-all channel mix.
2. Pursue "secondhand search traffic": get mentioned on sites that already rank/get cited for your target topics, via partnerships, affiliate deals, or sponsorships, rather than relying only on your own domain authority.
3. Consider under-used training data surfaces: GitHub repos, Wikipedia pages, original research papers, and patents are all near guaranteed to be included in model training data.
### 4.9 Publishing SOP
Track performance using:
Google Search Console
Google Analytics
Ahrefs or SEMrush

Monitor:
Impressions
Click-through rate (CTR)
Rankings
Organic traffic
User engagement
 
### 4.10 Performance Monitoring SOP
1. Monitor citation count and citation accuracy/sentiment per AI platform separately — citation behavior differs meaningfully between ChatGPT, Perplexity, and AI Mode.
2. Monitor for hallucinated URLs — pages your analytics shows visits to that return 404s, indicating an AI system fabricated a URL for your brand.
3. Treat AI-visibility-tracker numbers as directionally useful, not accurate — judge these tools on consistent methodology (precision) over time rather than as ground truth (accuracy), and sample multiple times per day and average, given the probabilistic nature of LLM outputs.
4. Filter your Google Search Console data for keywords that trigger AI Overviews to separate "AI Overview traffic loss" from genuine ranking loss.
### 4.11 Content Refresh Cycle SOP
1. Prioritize refreshing pages already known to be cited by AI (pull the list from your citation tracker) over blind refreshing of the whole site.
2. Weight refresh frequency toward freshness-sensitive topics — content in fast-moving categories benefits more from frequent updates than evergreen reference content.
---
 
## 5. Prompt Library

A standardized collection of reusable prompts to support AI-powered SEO workflows. Each prompt follows a consistent structure to ensure repeatability, quality, and collaboration across teams.

---

### 1. Keyword Research

**Objective**

Identify high-potential keywords and semantic opportunities for a target topic.

#### Input

- Industry
- Target Audience
- Seed Keyword

#### Prompt

```text
Act as an SEO strategist.

Generate a list of primary, secondary, and long-tail keywords for the topic:

Topic: [TOPIC]

For each keyword provide:
- Search Intent
- Difficulty (Low/Medium/High)
- Suggested Content Type
- User Pain Point
- Related Semantic Keywords

Return the output in a markdown table.
```

#### Expected Output

- Primary Keywords
- Secondary Keywords
- Long-tail Keywords
- Search Intent
- Topic Clusters

---

### 2. Search Intent Analysis

**Objective**

Understand user intent before content planning.

#### Input

- Target Keyword

#### Prompt

```text
Analyze the search intent for the keyword:

"[KEYWORD]"

Classify the intent as:
- Informational
- Commercial
- Transactional
- Navigational

Explain why users search for this keyword.

List the questions users are most likely trying to answer.
```

#### Expected Output

- Search Intent Classification
- User Objectives
- Frequently Asked Questions

---

### 3. Competitor Analysis

**Objective**

Identify content gaps and competitive opportunities.

#### Input

- Topic
- Primary Keyword

#### Prompt

```text
Act as an SEO consultant.

Analyze the top-ranking articles for:

[TOPIC]

Identify:

- Common headings
- Missing information
- Weak arguments
- Opportunities to create better content

Finish by recommending how our article can outperform competitors.
```

#### Expected Output

- Competitor Strengths
- Content Gaps
- Differentiation Opportunities

---

### 4. Content Brief Generation

**Objective**

Generate a standardized SEO content brief.

#### Input

- Topic
- Target Audience
- Primary Keyword

#### Prompt

```text
Create a professional SEO Content Brief.

Topic:
Audience:
Primary Keyword:

Include:

- Search Intent
- Article Goal
- Suggested Word Count
- H1
- H2
- H3
- FAQs
- Internal Linking Opportunities
- External References
```

#### Expected Output

- Complete SEO Content Brief

---

### 5. First Draft Generation

**Objective**

Generate a structured first draft aligned with SEO best practices.

#### Input

- Approved Content Brief

#### Prompt

```text
Write a detailed SEO article using the content brief.

Requirements:

- Human sounding
- EEAT compliant
- Practical examples
- Avoid keyword stuffing
- Include H2 and H3 hierarchy
- Add FAQs
- End with actionable recommendations
```

#### Expected Output

- SEO-Optimized First Draft

---
## 6. Quality Assurance Checklist
 
| Check | Sourced? |
|---|---|
| Brand/on-brand alignment | Yes |
| Human-expertise / SME review (not fully AI-authored) | Yes |
| UX quality / bounce-rate risk | Yes |
| Chunking / short single-topic paragraphs | Yes |
| Entity richness | Yes |
| Freshness / last-updated date | Yes |
| Page-speed / 499 error check | Yes |
| JavaScript-rendering dependency | Yes |
| EEAT review | Not sourced |
| Plagiarism check | Not sourced |
| Meta title / meta description | Not sourced |
| Schema markup | Not sourced |
| Readability | Partial — BLUF/declarative-sentence guidance only |
 
---
 
## 7. Metrics & KPIs
 
| Metric | Sourced? |
|---|---|
| Branded web mentions (off-site) | Yes — ~0.67 correlation with AI Overview appearance |
| Citation count by platform | Yes |
| Citation sentiment/accuracy | Yes |
| Conversion rate (over raw traffic) | Yes |
| Hallucinated-URL rate | Yes |
| 499 error rate on key pages | Yes |
| Organic traffic, CTR, keyword rankings, time on page, bounce rate | Not sourced, aside from bounce rate as a UX-quality signal (see QA checklist) |
 
---
 
## 8. Where Experts Disagree
 
### Disagreement 1: Should AI write the first draft with minimal human involvement?
- **Mike King** has generated content at scale using AI since 2020, and argues that "non-commodity" human-only content is a moat that erodes over time — if you can convert your unique data/expertise into structured data, you can eventually generate content at scale that captures it.
- **Aleyda Solis** argues AI should accelerate content production but should not be the final output — content produced without real human expertise and brand voice behind it tends toward generic, sometimes wrong output.
- **My take:**
### Disagreement 2: How technical does chunking/content-structure need to be?
- **Mike King** treats chunking as a real technical concept worth engineering deliberately — mapping content structure to how passage-level retrieval actually works.
- **Ryan Law** is dismissive of the jargon, framing it as "just good writing" — clear structure, short sentences, BLUF — without needing to think in retrieval-system terms.
- **My take:**
### Disagreement 3: Is optimizing training-data sources (GitHub, Wikipedia, patents) worth the effort?
- **Ryan Law** downplays this — arguing there's not much you can actually do to influence training-data inclusion, and treats RAG-visibility tactics as the actionable lever instead.
- **Mike King and Chris Long** both point to concrete tactics here — sponsoring GitHub repos to get cited, and deliberately publishing to guaranteed-training-data surfaces like Wikipedia, patents, and research papers. Ryan Law later lists several of these as "worth considering," in tension with his own downplaying.
- **My take:**
### Disagreement 4: Is broad, top-of-funnel informational content still worth targeting?
- **Aleyda Solis** warns against generic, off-brand informational content — citing sites that lost significant traffic in Google core updates after publishing shallow, off-brand content.
- **Ryan Law's data** shows blogs/guides and informational content are among the most heavily cited page types by AI systems generally, without the same brand-alignment caveat.
- **My take:**
---
 
## 9. What I Rejected and Why
 
1. **Cloaking / serving different content to AI crawlers than to users.** Mike King mentions people are experimenting with this, but explicitly says his own team has not seen a significant impact from it. Ryan Law separately warns against black-hat tactics generally, calling them not worth it for legitimate brands long-term. Rejected: unproven upside, real reputational/technical downside if discovered.
2. **Fully unedited, mass-produced AI content at scale.** Ryan Law calls out long AI-generated pages with no images/links as short-sighted, arguing AI systems will get better at filtering this the way Google did, and that being cited for spammy content that converts nobody isn't actually valuable. Rejected: even where it "works" short-term, it doesn't serve the actual business goal.
---
 
## 10. My Original Ideas
 
**Idea: A weighted "ecosystem budget" model.** Several sources describe the existence of multiple ecosystems (own site, Reddit, affiliates, YouTube) and the need to segment by vertical, but none propose an actual method for allocating budget/effort across those ecosystems in a structured way. A workable approach: score each ecosystem for a given vertical on (a) citation frequency observed in your tracking tool, (b) cost/effort to influence, and (c) your current gap vs. competitors, then allocate a rolling percentage of content/PR budget accordingly, re-scored quarterly. This turns a qualitative "know your vertical" heuristic into a repeatable operational process — the missing piece between "Reddit matters more in some verticals" and an actual monthly budget line.
 
---
 
## 11. Weaknesses of This Playbook
 
- **Small, homogenous source base.** Four experts, all fairly bullish on AEO as a discipline — no skeptical outside voice questioning whether AEO investment pays off at all for smaller brands.
- **No cost/effort data.** None of the sources quantify how much budget or time these tactics require relative to expected payoff.
- **Correlational, not causal, evidence.** The strongest data point in this playbook (branded mentions correlating with AI Overview appearance) is a correlation, not a proven causal lever.
- **Fast-moving subject matter.** This space is still described by its own practitioners as a "wild west" — treat every tactic here as provisional.
- **Missing expert diversity per the assignment.**
---
 
## 12. Who I Would NOT Recommend Following, and Why
 
Candidate: 
**Kevin Indig** : Skeptical Linkedin, he has(seemingly) worked in every big-tech as SEO advisor(un-officially)

**Mike King**, on narrow, specific grounds — not his expertise overall, but two things worth flagging for a reader deciding who to trust blindly:
1. He repeatedly undercuts the reliability of AI-visibility tracking data (calling rank tracking "fundamentally flawed") while his own company sells/relies on this kind of analysis.
2. Some claims in the interview are stated with high confidence but thin support — e.g., a four-reason case for why Google "wins long-term" trails off with an admitted forgotten fourth reason, delivered with the same confident tone as his rigorously-researched claims. A reader who can't tell the two apart risks over-trusting the latter.
 
