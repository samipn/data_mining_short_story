# DeepJSONEval – Data Mining Short Story

_A compact walkthrough of **DeepJSONEval: Benchmarking Complex Nested JSON Data Mining for Large Language Models**._

[![Paper](https://img.shields.io/badge/Paper-arXiv%3A2509.25922-B31B1B)](https://arxiv.org/abs/2509.25922)
[![Medium Article](https://img.shields.io/badge/Medium-DeepJSONEval-black)](https://medium.com/@samipn/deepjsoneval-finding-out-how-efficiently-llms-can-mine-data-using-multi-tiered-jsons-2f6cc6dce9db)
[![Slides](https://img.shields.io/badge/Slides-Slideshare-blue)](https://www.slideshare.net/slideshow/deepjsoneval-benchmarking-complex-nested-json-data-mining-for-llms-3a38/284330236)
[![Video](https://img.shields.io/badge/Video-Walkthrough-red)](https://drive.google.com/file/d/1lw1awbZ8g_tXf7HoLjI0dO2jWtHVR2qv/view?usp=sharing)

---

## 📁 Repository Contents

This repo currently contains:

- `DeepJSONEval Research Paper.pdf`  
  A copy of the research paper that the short story / writeup is based on.

- ✍️ **Medium article (short story / explainer)**  
  [DeepJSONEval: Finding out how efficiently LLMs can mine data using multi-tiered JSONs](https://medium.com/@samipn/deepjsoneval-finding-out-how-efficiently-llms-can-mine-data-using-multi-tiered-jsons-2f6cc6dce9db)

- 📊 **Slide deck (presentation)**  
  [DeepJSONEval – Benchmarking Complex Nested JSON Data Mining for LLMs](https://www.slideshare.net/slideshow/deepjsoneval-benchmarking-complex-nested-json-data-mining-for-llms-3a38/284330236)

- 🎥 **Video walkthrough**  
  [DeepJSONEval video walkthrough](https://drive.google.com/file/d/1lw1awbZ8g_tXf7HoLjI0dO2jWtHVR2qv/view?usp=sharing)

---

## 🔍 Key Ideas to Take Away

- **Information overload → nested JSONs**  
  The modern web is full of noisy, redundant text. Deep nested JSON schemas provide a way to **compress and structure** this information while keeping context.

- **From text to structure, not just formatting**  
  Many benchmarks only check if models follow a schema format. DeepJSONEval instead focuses on whether models can **extract and organize the right information** into complex schemas.

- **Challenging depth & diversity**  
  DeepJSONEval includes **thousands of instances** across diverse domains and nesting depths, making it a more realistic test of LLMs’ structured-output capabilities.

---

## 📚 References

- Zhicheng Zhou, Jing Li, Suming Qiu, Junjie Huang, Linyuan Qiu, Zhijie Sun.  
  **DeepJSONEval: Benchmarking Complex Nested JSON Data Mining for Large Language Models.**  
  arXiv:2509.25922, 2025.  
  Preprint: <https://arxiv.org/abs/2509.25922>

- Official DeepJSONEval repository:  
  <https://github.com/GTS-AI-Infra-Lab-SotaS/DeepJSONEval>

---

## 🙌 Acknowledgements

This short-story style writeup and resource hub is built on top of the DeepJSONEval benchmark and paper by the original authors. All credit for the benchmark, methodology, and results goes to them.
