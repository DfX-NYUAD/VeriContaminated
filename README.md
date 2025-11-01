# VeriContaminated: Assessing LLM-Driven Verilog Coding for Data Contamination

## Abstract
Large Language Models (LLMs) have revolutionized code generation, achieving exceptional results on various established benchmarking frameworks. However, concerns about data contamination - where benchmark data inadvertently leaks into pre-training or fine-tuning datasets - raise questions about the validity of these evaluations. While this issue is known, limiting the industrial adoption of LLM-driven software engineering, hardware coding has received little to no attention regarding these risks. For the first time, we analyze state-of-the-art (SOTA) evaluation frameworks for Verilog code generation (VerilogEval and RTLLM), using established methods for contamination detection (CCD and Min-K% Prob). We cover SOTA commercial and open-source LLMs (CodeGen2.5, Minitron 4b, Mistral 7b, phi-4 mini, LLaMA-{1,2,3.1}, GPT-{2,3.5,4o}, Deepseek-Coder, and CodeQwen 1.5), in baseline and fine-tuned models (RTLCoder and Verigen). Our study confirms that data contamination is a critical concern. We explore mitigations and the resulting trade-offs for code quality vs fairness (i.e., reducing contamination toward unbiased benchmarking).

Author: Zeng Wang*, Minghao Shao*, Jitendra Bhandari, Likhitha Mankali, Ramesh Karri, Ozgur Sinanoglu, Muhammad Shafique, Johann Knechtel

Paper Link: [VeriContaminated](https://arxiv.org/abs/2503.13572)

<img width="852" height="476" alt="image" src="https://github.com/user-attachments/assets/7960551f-cab8-4f0c-969d-c1faaf853819" />

## Updates
[update]: upload the Colab for Verilog-related CDD, Min-K% and TED evaluation by 10/04/2025.
[update]: Paper has been accepted by IEEE International Conference on LLM-Aided Design (ICLAD), 2025
