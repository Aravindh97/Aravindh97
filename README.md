### Aravindh Varadharaj

I build Go backend projects in my spare time to learn: concurrency, payments, distributed systems, data pipelines and search. Each one has a Go backend and a React + TypeScript frontend, with a live demo in the browser. All of these are personal projects, not affiliated with my employer.

**Live resume: [aravindh97.github.io/resume](https://aravindh97.github.io/resume/)**: ask questions about my code, kill the Raft leader, and flip `sync.Mutex` on a real data race, all in Go WebAssembly.

| Project | What it does | Measured | Try it |
|---|---|---|---|
| [granth](https://github.com/Aravindh97/granth) | Document ingestion on Temporal, hybrid BM25 + k-NN retrieval in OpenSearch, citations, MCP tools | hit@5 0.977, MRR 0.925 vs 0.955 / 0.891 BM25; survived an OpenSearch outage with no duplicates | [live demo](https://aravindh97.github.io/granth/) |
| [smriti](https://github.com/Aravindh97/smriti) | Long-term memory for agents: user, team and org scopes, supersede instead of append, bitemporal history | 1.000 correct and 0 stale vs 0.676 / 0.176 for raw chat history | [live demo](https://aravindh97.github.io/smriti/) |
| [sutra](https://github.com/Aravindh97/sutra) | Postgres CDC and CRM connectors, ontology, GSTIN/PAN-aware entity resolution with lineage | held-out F1 0.96–0.996 vs 0.72–0.77 GSTIN-only; source = warehouse after kill -9 | [live demo](https://aravindh97.github.io/sutra/) |
| [resume](https://github.com/Aravindh97/resume) | This resume as a Raft mesh, a Go WebAssembly race simulator and a git log | `go run github.com/Aravindh97/resume/cmd/career@latest log` | [live site](https://aravindh97.github.io/resume/) |

More Go systems, each with tests, CI, measured results and a demo that runs in your browser:

| Project | What it proves | Try it |
|---|---|---|
| [fairdrop](https://github.com/Aravindh97/fairdrop) | 0 seats sold twice across 50,000 simulated buyers; a queue order anyone can verify | [live demo](https://aravindh97.github.io/fairdrop/) |
| [paisa](https://github.com/Aravindh97/paisa) | exactly-once ledger: balances unchanged after 20 kill -9s; 477/477 reconciliation breaks found | [live demo](https://aravindh97.github.io/paisa/) |
| [orbit](https://github.com/Aravindh97/orbit) | satellite conjunction screening: 190/190 vs brute force, 16,763 objects × 6 days in under 4 minutes | [live demo](https://aravindh97.github.io/orbit/) |
| [relief](https://github.com/Aravindh97/relief) | offline-first CRDT sync: 10,000 randomised partition runs all converge | [live demo](https://aravindh97.github.io/relief/) |
| [aqcal](https://github.com/Aravindh97/aqcal) | air sensor calibration as a stream: error down 52% on held-out days, 298/300 faults caught | [live demo](https://aravindh97.github.io/aqcal/) |
| [foodwatch](https://github.com/Aravindh97/foodwatch) | food-stress warning for Somalia: 20 of 26 IPC crisis onsets flagged ~22 weeks early | [live demo](https://aravindh97.github.io/foodwatch/) |
| [pallanguzhi](https://github.com/Aravindh97/pallanguzhi) | the Tamil board game against a Go search AI; 2,800-game benchmark: the AI wins 100% as second player vs random | [play it](https://aravindh97.github.io/pallanguzhi/) |

Earlier: six full-stack platforms in Python and Go in [aravindh-impact-portfolio](https://github.com/Aravindh97/aravindh-impact-portfolio).

Stack: Go · PostgreSQL · Temporal · OpenSearch · pgvector · MCP · React · TypeScript · Python

[LinkedIn](https://www.linkedin.com/in/aravindh-varadharaj-253231201) · aravindhvaradha@gmail.com
