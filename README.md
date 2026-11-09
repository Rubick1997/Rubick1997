## Hi, I'm Rustam 👋

Senior product engineer in Seattle. I build AI features end to end: the LLM pipeline, the checks that keep it honest, and the UI people actually use.

- 🔭 **Now:** Senior Software Engineer at [Qloo](https://www.qloo.com), owning the Insights dashboard, [TasteDive](https://tastedive.com) and [qloo.com](https://www.qloo.com)
- 🧪 **Also:** AI evaluation contributor at Mercor, writing coding tasks and rubrics that frontier labs use to train and grade coding agents
- ✍️ **Writing:** case studies on [Medium](https://medium.com/@vinch1910)
- 🌐 **Site:** [kolumstack.best](https://kolumstack.best)

### Recent work

**Precomputed LLM output, fact-checked** · qloo.com  
A personalization demo took 31 seconds per request. I generated all 4,095 possible answers ahead of time with the Claude batch API, had a small model fact-check every claim against the source data, and shipped each answer as a static file. Instant page, about $121 for the full run, and every phrase links back to the data behind it.

**Face-aware image framing** · TasteDive  
A CSS center crop was cutting off people's heads on hero banners. I built a detector chain in Node with TensorFlow.js on WebAssembly (faces → head → saliency) that finds a focal point once on the server, cached and time-boxed so pages never slow down. Faces now stay in frame across 2M+ People pages.

**Insights dashboard rebuild** · Qloo  
Rebuilt the frontend architecture (40% faster loads), built React + D3 visualizations for ML output, moved the codebase to TypeScript (30% fewer runtime bugs), and cut LLM costs for written insights by 50% with batch prompting.

**Secure computation UI** · Pyte  
Sole frontend engineer on a privacy-preserving ML platform (SMPC, AWS Nitro, Azure Confidential Containers) for Fortune 100 clients: ~30 screens built from scratch, plus a QR-code mobile demo shipped in a week for Advertising Week NYC.

### Stack

`TypeScript` `React` `Next.js` `Node.js` `PostgreSQL` `AWS` `Python` `D3.js` `TensorFlow.js` `Claude / OpenAI APIs` `LLM evaluation` `gRPC` `Docker`

### Contact

[LinkedIn](https://www.linkedin.com/in/rustam-kolumbayev) · [Medium](https://medium.com/@vinch1910) · rustam.kolumbayev@gmail.com
