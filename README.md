# HR_LLM_biased

# introduction
(1)The adoption of LLMs is essential for HR operational efficiency
-Volume overload  : During peak recruitment seasons, a single HR manager should face thousands of applications.
-Cost efficiency & speed of LLM

(2)the lack of Objectivity
-The black box dilemma 
-The outlier crisis
-Absence of consensus


# dataset
-original dataset
https://github.com/Pramod9222/Employee-Performance-Analysis-
-generate personal profile and augment
<img width="476" height="128" alt="스크린샷 2025-12-11 오후 8 45 34" src="https://github.com/user-attachments/assets/c9b4c172-7671-4d9f-89bb-82716aa7c9bb" />

# experiment
(1)baselinemodel 
DeepSeek-llm-7b-chat
Gemini-2.0-flash
GPT-OSS-20B
Llama-3.1-8B-Instant
Qwen3-14B
Qwen3-Max

(2)evaluation metrics
Key Metrics
Promotion count, Average total score

Model-to-Model Comparison
Score distribution comparison

Outlier Case Study
When one model strongly disagrees → investigate reasoning differences

Cross-Model Evaluation per Individual
Compare multiple model outputs for the same employee
<img width="419" height="202" alt="스크린샷 2025-12-11 오후 8 49 51" src="https://github.com/user-attachments/assets/c445132e-7c58-4456-8aab-d1c5f950d1f1" />


# key findings
Focus on non-quantifiable soft skills → Deepseek, Llama
Strictly based on facts → Gemini, GPT

<img width="326" height="216" alt="스크린샷 2025-12-11 오후 8 51 41" src="https://github.com/user-attachments/assets/cad7e7d0-c76b-4e85-a938-c2736df1524e" />

