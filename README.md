# Hi, I'm Ma1oneZhang 👋

- 🎓 MPhil student at [DBGroup@SUSTech](https://github.com/DBGroup-SUSTech), working on efficient LLM inference — sparse offloading & large-scale parallelism
- 💼 Infra intern at [Novita AI](https://github.com/novitalabs), previously developer at datalayers
- 🚀 Contributor to two LLM inference engines:
  - [vLLM](https://github.com/vllm-project/vllm) — FlashTopK backend for sparse-attention (DSA) top-k prefill: 1.36–1.38× faster top-k at ≥128K keys, −4.4 s TTFT at 1M tokens ([#67149](https://github.com/vllm-project/vllm/pull/67149))
  - [pegainfer](https://github.com/pegainfer-project/pegainfer) — Qwen3.5 tensor parallelism: per-rank GDR state sharding, batched eager & CUDA-graph decode under TP ([#1003](https://github.com/pegainfer-project/pegainfer/pull/1003)–[#1006](https://github.com/pegainfer-project/pegainfer/pull/1006))
- 🏆 National Scholarship recipient during undergrad
- 🥇 Champion (performance award), Vector Retrieval Track — 2024 OceanBase Database Competition

### 🔨 Featured

- [gravity-trace](https://github.com/novitalabs/nsight-perf-sdk-for-ai/pull/1) — NVIDIA Nsight Perf SDK as a production GPU trace source (Rust): Prometheus metrics, Parquet / Perfetto capture, Flight SQL streaming, per-process attribution
- [nsys2perfetto-datafusion](https://github.com/Ma1oneZhang/nsys2perfetto-datafusion) — Nsight Systems Parquet → Perfetto JSON with Rust + DataFusion
- [nsys-parquet-perfetto-skill](https://github.com/Ma1oneZhang/nsys-parquet-perfetto-skill) — Codex skill packaging the same converter workflow
