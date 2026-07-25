# Hi, I'm Sydney 👋

Computer science student in Toronto. I build things that turn messy real-world data into something a person can actually act on — usually because I needed the thing myself first.

Currently a co-op student on the **Innovation Excellence** team at **Humber River Health**, where I work on AI assistants for hospital IT and switchboard workflows.

---

### What I'm working on

**🫀 [svt-monitor](https://github.com/sydneygahunia-wq/svt-monitor)** — iOS app that detects and logs SVT episodes  
I have SVT, and I spent nearly a year not knowing what was happening to me. This app watches heart rate, flags possible episodes with a tested detection state machine, and opens a guided breathing screen when one starts. Symptom and trigger tagging turn scattered episodes into something you can hand to a cardiologist.

`Swift · SwiftUI · HealthKit · SwiftData · Swift Charts`

**📊 [apple-health-insights](https://github.com/sydneygahunia-wq/apple-health-insights)** — analyse Apple Health exports without running out of memory  
Real exports are gigabytes of XML with millions of records. This streams them in constant memory — a 33 MB file uses less peak RAM than a 3 MB one — then reports trends, sustained heart-rate episodes and coverage gaps.

`Python · streaming XML · matplotlib · 55 tests`

**🔍 [askdocs](https://github.com/sydneygahunia-wq/askdocs)** — ask questions of your own documents, with citations  
A RAG pipeline built from the parts up: chunking, hashed TF-IDF embeddings, BM25, reciprocal rank fusion, and a groundedness gate that refuses to answer when the documents don't support it. Runs offline, no API key.

`Python · numpy · information retrieval · 66 tests`

**🌍 [portfolio](https://github.com/sydneygahunia-wq/portfolio)** — scroll-driven 3D globe  

`JavaScript · GSAP · Lenis · Canvas`

---

### How I like to build

**Test the part that fails quietly.** A parser bug crashes and announces itself. A statistics bug returns a plausible wrong number that nobody questions. That's where the tests go.

**Say what the system doesn't know.** Both my data projects refuse rather than guess — askdocs won't answer a question its documents can't support, and the health analyzer reports what it skipped so a summary never quietly covers a third of the file.

**Write down the trade-off.** Brute-force vector search beats an ANN index below a million vectors, and my README says so — including where it stops being true.

---

### Currently learning

Agentic architectures, retrieval evaluation, and how far you can get with classical IR before reaching for a neural model.

📫 **sydneygahunia@gmail.com**
