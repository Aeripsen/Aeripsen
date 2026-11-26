# Sepehr Jafari

I build detectors and agents that know when to say "I don't know", and I measure how often that is the right call.

Fourth year at the University of Toronto Mississauga, studying mathematics, applied statistics and computer science. Research assistant in network security at York University's Behaviour-Centric Cybersecurity Centre. Toronto.

## Paper

**Unveiling Hierarchical Machine Learning UDP-QUIC Intrusion Detection: Protocol-Aware Flow Analysis and a New Cloud-Generated DDoS Dataset.** First author, with M. Shafi and A. H. Lashkari. SECRYPT 2026, pages 49 to 68. [DOI 10.5220/0015033600004103](https://doi.org/10.5220/0015033600004103).
The labelled dataset behind it, BCCC-UDP-QUIC-IDS-2025 (1.22 million flows), is released by the lab: [bccc.laps.yorku.ca/BCCC-UDP-QUIC-IDS-2025](http://bccc.laps.yorku.ca/BCCC-UDP-QUIC-IDS-2025/).

## Start here

- [agent-gates](https://github.com/Aeripsen/agent-gates): four deterministic checks between a language model and what it is about to say or do (honesty, eligibility, grounding, injection). 152 tests, and the README prints the misses next to the catches: the grounding gate lets through 80 of 179 unsupported claims.
- [FlowSentry](https://github.com/Aeripsen/flowsentry) ([live demo](https://aeripsen.github.io/flowsentry/)): the paper's two-stage UDP/QUIC detector as a service, with a reject knob you can move over 6,570 held-out flows. It also publishes the benchmark where a plain forest beat my two-stage design.
- [LedgerSentry](https://github.com/Aeripsen/ledgersentry) ([live demo](https://aeripsen.github.io/ledgersentry/)): the same idea on card fraud. Raising the auto-flag bar from 0.5 to 0.95 cuts false alerts from 26.9 to 1.1 per 10,000 transactions, with the review queue priced and the confidence interval printed.

## More

- [FlowSentry Desk](https://github.com/Aeripsen/flowsentry-desk): an agent that works the queue of flows FlowSentry refuses to call. Six read-only tools, server-checked citations, a close that needs three independent yeses.
- [boson-bug-reports](https://github.com/Aeripsen/boson-bug-reports): five bugs in a realtime voice API found at a hackathon, each with a reproduction script and raw event logs (with Javad Maheronnaghsh).
- [quant-facts](https://github.com/Aeripsen/quant-facts): read-only market analysis with an honest backtest harness. Facts and indicators, never advice.
- [youtube-knowledge](https://github.com/Aeripsen/youtube-knowledge): a pipeline from video transcripts to clean JSONL, with a cited-extraction spec and an offline evaluation.
- Course study guides for [CSC373](https://github.com/Aeripsen/csc373-study-guide), [CSC343](https://github.com/Aeripsen/csc343-study-guide) and [MAT244](https://github.com/Aeripsen/mat244-study-guide).

Team BYTE BABIES placed 3rd in Canada at UofT CTF 2025 ([CTFtime](https://ctftime.org/team/280084/)). I also volunteer as lead developer of a bilingual charity website, [imammahdi.ca](https://imammahdi.ca).

Python, SQL, R, C#, TypeScript, FastAPI, Docker. Open to internships and research roles in security, fraud and risk, and machine learning, in Toronto or remote in Canada.

## Reach me

[sepehr1381ja@gmail.com](mailto:sepehr1381ja@gmail.com) | [Site](https://aeripsen.github.io) | [LinkedIn](https://www.linkedin.com/in/sepehr-jafari-fesharaki) | [ORCID](https://orcid.org/0009-0002-8610-112X)
