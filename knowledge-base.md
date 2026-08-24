# SEO / GEO / AEO Knowledge Base

Dated log, most recent entry first. Each entry: what happened (or is
anticipated), source(s), and a short strategic takeaway. See CLAUDE.md for
format and source guidance.

---

## 2026-08-24

### ChatGPT Search: Reddit's citation share collapsed ~86–95% in one week — MAJOR (GEO/AEO)
Reddit held roughly 2–3.8% of ChatGPT Search citations through early August 2026,
then cratered to under 1% (some trackers report as low as 0.07%) between Aug
8–14. Multiple trackers agree on the magnitude but disagree on the cause: one
analysis ties it to Reddit blanket-blocking crawlers via robots.txt around Aug
20 (cutting off the data-licensing pipeline OpenAI had used for training/search
access); another ties it to a retrieval-behavior change inside ChatGPT itself
around Aug 8 (shifting from broad web queries toward targeted `site:`-style
lookups of official/institutional domains, which rarely surface forum
threads). Neither cause is officially confirmed by OpenAI or Reddit, and
source quality here is smaller AI-search-tracking blogs rather than the usual
SEL/SER tier — treat the exact mechanism as unconfirmed, the magnitude of the
drop as well-corroborated. Separately, a citation-tracking report (5W/
Profound) found publishers with an OpenAI licensing deal earn ~48% more
ChatGPT citations than those without one (112% more if the deal is
exclusive).
**What this means:** Citation share on any single generative engine can swing
hard and fast for reasons outside a site's own content quality — crawler
access, licensing deals, and undocumented retrieval changes all matter as
much as on-page optimization. Don't treat one platform's current citation
share as stable, and don't assume a drop means a client did something wrong.
Track citation mix across ChatGPT, AI Overviews, AI Mode, and Perplexity
separately, since overlap between them is already known to be low.
Sources: [explainx.ai](https://explainx.ai/blog/reddit-citations-chatgpt-search-drop-august-2026), [Qwairy](https://www.qwairy.co/blog/chatgpt-reddit-citations-collapse-august-2026), [Promptwatch](https://promptwatch.com/blog/chatgpt-stop-citing-reddit), [Elmo — OpenAI licensing deals](https://www.elmohq.com/blog/openai-licensing-deals-chatgpt-citations)

### Google August 2026 Spam Update — MAJOR
Rolled out Aug 18–21, 2026 (2 days 16 hrs), global, all languages. Third
spam update of 2026. No new spam policies or companion blog post announced
— this refines detection of existing spam tactics, not a policy change.
Followed weeks of SERP volatility with users reporting reduced clicks
across Search and Discover ahead of the rollout.
**What this means:** If a site sees a sudden traffic drop right around
Aug 18–21, check for spam-policy violations (scaled/low-value content,
manipulative link schemes) before assuming it's a core-relevance issue —
different update, different fix.
Sources: [Search Engine Journal](https://www.searchenginejournal.com/google-begins-rolling-out-the-august-2026-spam-update/586301/), [PPC Land](https://ppc.land/googles-third-spam-update-of-2026-hits-every-language-and-region/)

### AI Mode / AI Overviews — structural shift toward embedded citations — MAJOR (GEO/AEO)
Google shipped five new AI Mode/AI Overviews features simultaneously, all
pointing at one strategy: embedding web sources directly inside the AI
response rather than listing them below it. AI Overviews appeared on 48%
of queries as of March 2026 (up from 34.5% in Dec 2025). Being cited
inside an AI Overview now drives ~35% more organic clicks than a standard
#1 organic ranking — but the #1 spot's own clicks drop ~18% when an
Overview appears above it. In AI Mode specifically there's no fallback
list of blue links: a page is either cited or invisible, and only ~14% of
AI Mode citations overlap with AI Overview citations for the same query.
**What this means:** "Ranking #1" is no longer the win condition on its
own — earning the AI Overview/AI Mode citation is now worth more than the
top organic slot, and optimizing for one doesn't guarantee the other since
citation overlap between the two surfaces is low.
Sources: [Stradiji](https://www.stradiji.com/5-big-updates-to-google-ai-overviews-ai-mode/), [Launchcodex](https://launchcodex.com/blog/seo-geo-ai/google-io-ai-search-seo-update/)

### Structured data: schema.org v30, FAQ rich results permanently retired — MAJOR
schema.org v30.0 released March 25, 2026. Google permanently retired FAQ
rich results on May 7, 2026 (they'd been phased down before that), and
HowTo rich results are now gone from desktop too, following their 2023
removal from mobile. JSON-LD remains Google's explicitly recommended
format over microdata. The five schema types still moving the needle:
Organization, Article/BlogPosting, FAQPage (despite no rich-result payoff
— still feeds AI Overview/LLM understanding), Product, LocalBusiness.
**What this means:** Don't sell FAQPage/HowTo schema on the promise of a
visible rich-result snippet anymore — that payoff is gone. The remaining
case for structured data is feeding AI Overviews/LLM citation eligibility
and entity clarity, not classic SERP rich results.
Sources: [Digital Applied](https://www.digitalapplied.com/blog/structured-data-after-io-2026-schema-updates), [AI Schema Gen](https://www.aischemagen.com/blog/google-structured-data-changes-2026)

### GEO/AEO framing context
GEO is now understood as the broader discipline (share of model, sentiment
management, narrative control across the generative AI ecosystem) with AEO
— originally a voice-search concept — largely subsumed into it, since most
voice queries now route through the same generative response mechanisms.
Google's own 2026 documentation frames preparing for generative AI search
as part of SEO, not a separate discipline. ~31.3% of the US population is
projected to use generative AI search in 2026 (EMARKETER).
**What this means:** Treat GEO/AEO as an extension of the SEO scope of
work, not an upsell into a separate category — matches how Google itself
is framing it.
Sources: [eMarketer](https://www.emarketer.com/content/faq-on-geo-aeo--where-ai-search-seo-overlap-2026), [Jasper](https://www.jasper.ai/blog/geo-aeo)

---
