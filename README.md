# Video Diffusion Compression Atlas

An interactive guide to 16 papers on compressing and accelerating the LTX-2.3 text-to-audio+video diffusion transformer on Intel hardware with OpenVINO and NNCF.

Open `index.html` in a browser and begin with **Start here**, a visual primer on diffusion, transformers, quantization, hardware, the OpenVINO toolchain, quality metrics and a map of the papers. Each paper tab opens with a narrated "Before reading" intro, then covers the paper with every figure redrawn as a diagram, every equation, the results tables and a note on relevance to the thesis.

- **Guides:** every block has a collapsed "Guide" note. Link to one directly with `index.html#g-<guide-id>`, for example `#g-vidit-q-fig-07`.
- **Intros and guided tours:** each paper has a short narrated intro and a narrated tour (about 4 to 5 minutes) that scrolls through the key blocks. The narration is in `audio/` and the scripts in `tours/`, generated with Google Cloud Text-to-Speech (voice en-US-Chirp3-HD-Charon).
- **`atlas-guides.json`:** all guide texts, with paper, block type and label.

Reading order: LTX-Video, LTX-2 → GPTQ, SmoothQuant, AWQ → Q-Diffusion, PTQ4DiT, ViDiT-Q, SVDQuant, DVD-Quant, QVGen, SVDQuant-GPTQ for Wan2.2 → FlashAttention-2, DeepCache, TeaCache → VBench.

The diagrams are redrawn illustrations for teaching. Where a plot was redrawn from its shape rather than from printed numbers, the caption says so. Refer to the original papers for exact figures.
