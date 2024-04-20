
# 🧠 Chain-of-Thought Reasoning in LLMs (CSE 574 Assignment)

## 📘 Overview

This project explores how **reasoning and planning techniques**, specifically the **Chain-of-Thought (CoT)** prompting method, can enhance the problem-solving capabilities of **Large Language Models (LLMs)**. The project applies and compares four prompting strategies on three distinct test cases using the open-source **Llama2-13B** model, deployed on Google Colab.

---

## 🚀 Prompting Methods Implemented

1. **Few-shot CoT**  
   → Explicit CoT demonstrations included as part of the prompt.

2. **Zero-shot CoT**  
   → Prompts use “Let’s think step by step” to invoke step-by-step reasoning without examples.

3. **Standard Few-shot**  
   → Direct Q&A examples without intermediate reasoning steps.

4. **Standard Zero-shot**  
   → No examples provided; LLM responds directly.

---

## 🧪 Test Cases Used

| Test Case                        | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| **1. Math Word Problem**         | Evaluates numerical reasoning based on word problem interpretation.         |
| **2. Date Understanding Problem**| Tests temporal reasoning involving delays and back-dating calculations.     |
| **3. Coinflip Problem**          | Assesses logical reasoning about state changes across sequential actions.   |

Each test case was run **five times per prompting method**, and the **average accuracy** was calculated for fair comparison.

---

## ⚙️ Technical Setup

- **Model**: Llama2-13B
- **Platform**: Google Colab (T4 GPU)
- **Language**: Python (Jupyter Notebook)
- **Libraries**: Transformers, accelerate, matplotlib, etc.

---

## 📊 Evaluation and Results

Results were analyzed based on average accuracy and visualized using **bar charts** for each test case. These insights help identify which prompting strategies most effectively enable logical reasoning in LLMs.

All testing and visualization steps are clearly documented in the provided `.ipynb` notebook.

---

## 📌 Conclusion

This project demonstrates the effectiveness of **CoT prompting** in improving the reasoning capabilities of LLMs. By comparing standard prompting methods against CoT-enhanced techniques, we gain insights into how structured reasoning can significantly enhance LLM performance even in small-scale deployments.

---

## 📚 References

- Wei et al., 2022: *Chain-of-thought prompting elicits reasoning in large language models*
- Kojima et al., 2022: *Large language models are zero-shot reasoners*
