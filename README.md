# EXP–2: Prompt Engineering

## **Aim**
Comparative Analysis of different types of Prompting patterns and explanation with various test scenarios.

---

## **Experiment**
To test and compare how different prompting patterns affect the responses of a Large Language Model (LLM).  
We will analyze **broad/unstructured prompts** versus **clear/refined prompts** across multiple scenarios and evaluate quality, accuracy, and depth.

---

## **Algorithm (Step-by-Step Procedure)**
1. Select different prompting patterns:
   - Zero-shot prompting
   - Few-shot prompting
   - Chain-of-thought prompting
   - Role-based prompting
   - Instruction + Context prompting
2. Design **broad/unstructured prompts** (vague) and **clear/refined prompts** (precise).
3. Test prompts on chosen scenarios (general knowledge, reasoning, summarization, creative writing).
4. Collect responses from the LLM for each scenario.
5. Compare results based on:
   - **Relevance**
   - **Accuracy**
   - **Depth**
   - **Creativity**
6. Tabulate the observations.
7. Represent the concept using a mind map for clarity.
8. Conclude with analysis and result.

---

## **Output**

### **Test Scenarios & Responses**

| Prompt Type | Example Prompt | Test Scenario | Observed Response Quality |
|-------------|----------------|---------------|---------------------------|
| **Zero-shot (Broad)** | "Tell me about AI." | General Knowledge | Generic, surface-level, lacks depth. |
| **Zero-shot (Refined)** | "Explain Artificial Intelligence in simple terms for school students." | General Knowledge | Clear, structured, audience-focused. |
| **Few-shot** | "Summarize like: 1. Topic intro, 2. Key points, 3. Conclusion. Now summarize Cloud Computing." | Summarization | More structured, follows given format. |
| **Chain-of-thought** | "Step-by-step, explain why the Earth orbits the Sun." | Reasoning | Detailed reasoning, logical explanation. |
| **Role-based** | "You are a cybersecurity professor. Explain phishing attacks." | Teaching | Professional tone, practical examples. |
| **Instruction + Context** | "Given this news article [insert text], summarize in 3 bullet points focusing on economic impact." | Context Summarization | Highly relevant, focused on required aspect. |

---

### **Visual Representation (Mind Map)**

<img width="1112" height="503" alt="image" src="https://github.com/user-attachments/assets/876c3045-2ce2-4d49-b6f8-eff8f261e58c" />

## RESULT:
Broad/unstructured prompts → Often lead to vague, general, or incomplete responses.<br>
Clear/refined prompts → Produce more accurate, structured, and context-relevant outputs.<br>
Chain-of-thought and role-based prompting significantly improve depth and clarity.<br>
Instruction + context prompting yields the most precise and targeted results.<br>
Effective prompt engineering depends on choosing the right prompting pattern for the task.
