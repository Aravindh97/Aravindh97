### Aravindh Varadharaj

Full-stack engineer: Go services on PostgreSQL with React + TypeScript frontends. I build projects in my spare time to learn, and test each one against a real database, in real browsers and under load. All of these are personal projects, not affiliated with my employer.

**Live resume: [aravindh97.github.io/resume](https://aravindh97.github.io/resume/)**: ask questions about my code, kill the Raft leader, and flip `sync.Mutex` on a real data race, all in Go WebAssembly.

Full-stack apps (Go, PostgreSQL, React + TypeScript):

| Project | What it does | Measured | Try it |
|---|---|---|---|
| [kaasu](https://github.com/Aravindh97/kaasu) | Personal finance: a UPI-style wallet on a double-entry ledger, PIN and fraud rule, and a bank-statement analyser that runs in your browser as WebAssembly | 431 payments retried with the same key under load, 0 paid twice; ledger balanced after 10,306 requests | [live demo](https://kaasu.onrender.com/) |
| [arogya](https://github.com/Aravindh97/arogya) | Hospital platform: OPD tokens, patient records with an access log the patient can read, beds and a blood bank | 41,874 requests in 20 s, token p99 61 ms; no slot, bed or blood unit ever given twice | [live demo](https://arogya.onrender.com/) |
| [thari](https://github.com/Aravindh97/thari) | Garment order tracker for a factory and its buyers, with live updates and permissions in every query | about 3,700 requests/s at p99 under 26 ms; caught and fixed a lost-update bug (8 of 40 saved) | [live demo](https://thari.onrender.com/) |
| [kurippu](https://github.com/Aravindh97/kurippu) | Offline-first notes: one Go CRDT on the server and in the browser, IndexedDB and a service worker | 1,500 random offline sessions all converge; a keystroke takes 1.2 ms at 10,000 characters | [live demo](https://kurippu.onrender.com/) |
| [pallanguzhi](https://github.com/Aravindh97/pallanguzhi) | The Tamil board game, online multiplayer over WebSockets or against a Go search AI | 1,000 games over 4,000 connections, 0 failures | [play it](https://aravindh97.github.io/pallanguzhi/) |

Go systems, each with tests, CI, measured results and a demo that runs in your browser:

| Project | What it proves | Try it |
|---|---|---|
| [granth](https://github.com/Aravindh97/granth) | document ingestion and hybrid retrieval: hit@5 0.977 vs 0.955 BM25; survived an OpenSearch outage with no duplicates | [live demo](https://aravindh97.github.io/granth/) |
| [smriti](https://github.com/Aravindh97/smriti) | long-term memory for agents: 1.000 correct and 0 stale vs 0.676 / 0.176 for raw chat history | [live demo](https://aravindh97.github.io/smriti/) |
| [sutra](https://github.com/Aravindh97/sutra) | CDC connectors and entity resolution: held-out F1 up to 0.996; source = warehouse after kill -9 | [live demo](https://aravindh97.github.io/sutra/) |
| [fairdrop](https://github.com/Aravindh97/fairdrop) | 0 seats sold twice across 50,000 simulated buyers; a queue order anyone can verify | [live demo](https://aravindh97.github.io/fairdrop/) |
| [paisa](https://github.com/Aravindh97/paisa) | exactly-once ledger: balances unchanged after 20 kill -9s; 477/477 reconciliation breaks found | [live demo](https://aravindh97.github.io/paisa/) |
| [orbit](https://github.com/Aravindh97/orbit) | satellite conjunction screening: 190/190 vs brute force, 16,763 objects × 6 days in under 4 minutes | [live demo](https://aravindh97.github.io/orbit/) |
| [relief](https://github.com/Aravindh97/relief) | offline-first CRDT sync: 10,000 randomised partition runs all converge | [live demo](https://aravindh97.github.io/relief/) |
| [aqcal](https://github.com/Aravindh97/aqcal) | air sensor calibration as a stream: error down 52% on held-out days, 298/300 faults caught | [live demo](https://aravindh97.github.io/aqcal/) |
| [foodwatch](https://github.com/Aravindh97/foodwatch) | food-stress warning for Somalia: 20 of 26 IPC crisis onsets flagged ~22 weeks early | [live demo](https://aravindh97.github.io/foodwatch/) |
| [resume](https://github.com/Aravindh97/resume) | this resume as a Raft mesh, a Go WebAssembly race simulator and a git log | [live site](https://aravindh97.github.io/resume/) |

The full-stack demos run on a free server that sleeps when idle, so the first visit can take up to a minute.

Stack: Go · PostgreSQL · React · TypeScript · WebAssembly · WebSockets · Playwright · Docker · Temporal · OpenSearch

[LinkedIn](https://www.linkedin.com/in/aravindh-varadharaj-253231201) · aravindhvaradha@gmail.com
