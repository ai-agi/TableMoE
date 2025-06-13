<div align="center">
  
<h1 style="display: flex; align-items: center; gap: 10px; margin: 0;">
  <img src="assets/wukong.png" alt="logo" height="44" />
  <span style="font-size: 2.6em; font-weight: 800;">TableMoE</span>
</h1>


<h3>Neuro-Symbolic Routing for Structured Expert Reasoning in Multimodal Table Understanding</h3>

<br> College of Computer Science and Technology  <br>
<br> Zhejiang University <br>

*If you have any question, feel free to contact [📧](mailto:junwen.agi@gmail.com).*

</div>

# TableMoE

**TableMoE** is a powerful multimodal large language model built upon a novel <strong>Mixture-of-Connector-Experts</strong> (MoCE) architecture. It is designed for robust table-centric understanding and visual reasoning across diverse formats, including text, tables, charts, and images. Trained on extensive tabular corpora, TableMoE supports advanced tasks such as table editing, highlighting, replotting, transformation, and symbolic CoT-driven or PoT-driven reasoning. Its <strong>neuro-symbolic routing</strong> and expert composition enable strong conversational capabilities grounded in structured data.

Visit the project: https://ai-agi.github.io/TableMoE/

Keywords: TableMoE, Neuro-Symbolic Routing, Table Reasoning, MoE, Multimodal, Table-Centric QA, Symbolic Graph Planning, Role Classification, Structural Alignment, LLMs, LMMs, LVLMs, Vision-Language Models, Structured Reasoning


## News
- **`2025/06/13`**: 📌 We release _WildStrcut_ Series **WMMTabDialog** benchmark, see https://github.com/ai-agi/WMMTabDialog or https://huggingface.co/datasets/darkme-ai/WMMTabDialog. **WMMTabDialog** is a high-quality multimodal benchmark for Chinese tax and finance, featuring multi-turn dialogues and multi-table images with _WildStruct_ traits, e.g., incomplete structures, complex nested cells, symbolic expressions, and visual noise. It targets structured reasoning in Multimodal Large Language Models (MLLMs). **WMMTabDialog** is a held-out zero-shot benchmark, excluded from all training to ensure contamination-free, unbiased evaluation.
- **`2025/06/02`**: 🌍 We release **WMMFinanceMath**, see [**here**](https://github.com/ai-agi/WMMFinanceMath), a visually grounded version of FinanceMath with markdown tables rendered into WildStruct-style images featuring real-world noise like blur, skew, and watermarks. 🎉
- **`2025/05/05`**: 🎉🎉🎉 TableMoE extends the LLaVA-NeXT framework (https://github.com/LLaVA-VL/LLaVA-NeXT) by implementing new functionalities that enable encoding multiple images within multi-round conversations in a single sample per batch—capabilities not supported in the original implementation!
- **`2025/05/01`**: 🚀 We release TableMoE!

## 🔥 Key Features
- 💡 Neuro-Symbolic Routing with Role and Structural Graph Alignment
- 📊 Support for WMMFinanceMath, ChartQA, WMMTATQA, WMMTabDialog, WMMFinQA datasets
- 🧠 Compatibility with Llama 3.1, Qwen2.5-VL Transformer-based LLM backbones
- 📎 Built-in evaluation and visualization scripts

## 🚀 Quick Start

```bash
git clone https://github.com/ai-agi/TableMoE.git
cd TableMoE
bash scripts/alignment_table2code.sh

