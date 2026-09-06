# seo-geo-news

Public log of SEO/GEO/AEO news, algorithm updates, and best practices —
industry-wide, not client-specific. This repo is intentionally public: it
only contains publicly-reported news plus generic strategic commentary, no
client data or credentials. It's public specifically so cloud-scheduled
automation can read and write it without needing private-repo access.

Private context (Ody's own instructions, and any future client/business-
specific notes) lives separately in the private `seo-geo-advisor` repo,
which references this one for general industry context.

## Working in this repo

- `knowledge-base.md` is a dated log, most recent entry first. Treat it as
  a starting point, not a substitute for a live check — this space moves
  fast, so confirm anything time-sensitive with a fresh web search before
  acting on it.
- When adding an entry, follow the existing entry format: date heading,
  what happened/is anticipated, source link(s), and a short "what this
  means" strategic note.
- Default sources to check: Search Engine Land, Search Engine Roundtable,
  Google Search Central Blog, Moz, Ahrefs blog, SparkToro. Not exhaustive —
  use judgment on anything else credible.
- Always flag as significant: Google core/spam algorithm updates,
  structured-data/schema/JSON-LD changes, and shifts in how AI Overviews,
  ChatGPT, Perplexity, etc. surface or cite sites (GEO/AEO territory).
  Credible previews/rumors of upcoming changes count too, not just shipped
  ones — label those clearly as "anticipated" in the entry.

## Certainty labels

Every entry heading carries a certainty tag, so a skim tells you how much
weight to put on it. This is separate from `MAJOR`, which marks significance
— an item can be `CHATTER` and `MAJOR` at the same time.

- **`[CONFIRMED]`** — officially announced or verifiably shipped: Google
  Search Central, an OpenAI/Anthropic/Perplexity changelog, an on-record
  statement from a company spokesperson, or a change anyone can reproduce.
- **`[ANTICIPATED]`** — credibly previewed but not yet live: a pre-announced
  rollout, a documented deprecation date, a feature spotted in testing, an
  official "coming soon".
- **`[CHATTER]`** — unconfirmed community signal: forum and Reddit threads,
  ranking-volatility tracker spikes, practitioners reporting the same thing
  independently, with no official confirmation. Worth logging early, because
  chatter is usually how a core update gets noticed before Google confirms
  it — but never present it to a client as fact.

Heading format: `### [CHATTER] Widespread ranking volatility reported — MAJOR`

When an item graduates — chatter that Google later confirms — do NOT rewrite
the old entry. Add a new dated entry marked `[CONFIRMED]` and note that it
confirms the earlier chatter. The log is a timeline, not a live status page;
the history of what was suspected when is itself useful.

## Chatter sources

Beyond the default publications, check community and volatility sources for
looming/unconfirmed changes: the Search Engine Roundtable forum roundups,
WebmasterWorld, r/SEO, r/bigseo, r/TechSEO, the Google Search Central help
community, and practitioners who track this closely (Barry Schwartz, Glenn
Gabe, Lily Ray). For volatility specifically: Semrush Sensor, Mozcast,
Algoroo, Advanced Web Ranking. Corroboration matters — one person posting
that their traffic dropped is not a signal; the same report from several
unrelated sites on the same days is.
