# The Emergent Learning Pipeline 🧠🎙️

**Live Site:**[https://emergentcomplex.github.io](https://emergentcomplex.github.io)

The Emergent Learning Pipeline is an open-source, high-agency learning tool. It bridges the gap between dense, technical source material and intuitive, personalized education by chaining together Socratic LLM tutoring and AI audio podcast generation (via Google NotebookLM).

## 📖 The Origin Story
This project was born out of a live audio room on Clubhouse. Technical, high-level information was being shared, but the format created friction for "silent listeners" who wanted to ask questions, test their intuition, or learn at their own pace without interrupting the speakers. 

This pipeline was built to solve that social and educational bottleneck. It allows anyone to take raw notes, feed them into an AI mentor for a personalized, metaphor-driven learning session, and ultimately generate an audio podcast to reinforce the concepts.

## 🚀 How It Works (Phase 1: Manual MVP)
Currently, the pipeline operates as a guided workflow:
1. **Upload/Prepare:** Get your source material in `.txt`, `.md`, or `.pdf` format.
2. **Generate Master Prompt:** Use our static site to generate a highly optimized prompt designed to force an LLM into a "Socratic Tutor" mode (using metaphors, high-entropy testing, and step-by-step validation).
3. **Execute:** Paste the prompt and your document into an LLM or Google NotebookLM.
4. **Synthesize:** Use NotebookLM to generate a two-host audio overview (podcast) of your personalized learning session.

## 🗺️ Roadmap
We are building this in public, moving from a manual workflow to a fully automated educational engine.

- [x] **Phase 1 (Current):** Static GitHub Pages site acting as a workflow guide and prompt generator. Zero cost, zero friction.
- [ ] **Phase 2:** Integration of a basic backend to automatically parse uploaded documents and format them for LLM ingestion.
- [ ] **Phase 3:** Full automation. Users upload a document, and the system automatically orchestrates the Socratic LLM interaction and utilizes Audio Generation APIs to output a finished podcast. (Will likely require a "Bring Your Own Key" model or grant funding for compute costs).

## 🤝 Contributing
This is a public good. If you are a developer, educator, or prompt engineer who wants to help automate Phase 2 and Phase 3, pull requests are welcome! 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
