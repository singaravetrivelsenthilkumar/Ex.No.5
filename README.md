# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS
## NAME: SINGARAVETRIVEL S
## REGISTER NUMBER: 212222220048

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT




## 1.  Introduction

In Artificial Intelligence (AI) systems, especially **Large Language Models (LLMs)** like ChatGPT, the quality of responses depends heavily on the **prompts provided**. Prompts act as the “input instructions” that guide the AI’s reasoning and output generation.

Two broad prompt types are studied here:

* **Naïve Prompts (Broad/Unstructured):**

  * Short, vague, and open-ended instructions.
  * Do not provide context, structure, or constraints.
  * Example: *“Tell me a story.”*

* **Basic Prompts (Clear/Structured):**

  * Explicit, detailed, and context-rich instructions.
  * Specify length, focus, and constraints.
  * Example: *“Write a 150-word story about a lost dog who finds its way home with an emotional ending.”*

This study tests and compares how ChatGPT responds to these two prompt types in **multiple scenarios**, analyzing the **quality, accuracy, and depth** of outputs.

---

## 2.  Experiment Design

### Step 1: Define Prompt Types

* **Naïve Prompt:** General instruction, open-ended.
* **Basic Prompt:** Specific instruction with constraints.

### Step 2: Select Test Scenarios

We choose **four diverse scenarios** that cover creativity, factual knowledge, summarization, and advice:

1. Creative Story Generation
2. Factual Question Answering
3. Summarization of a Concept
4. Providing Advice/Recommendations

### Step 3: Run AI Experiments

* Input the **Naïve Prompt** for each scenario and record the output.
* Input the **Basic Prompt** for the same task and record the output.

### Step 4: Evaluate Responses

Compare results based on three metrics:

* **Quality** → Clarity, grammar, and presentation of the output.
* **Accuracy** → How factually correct the response is.
* **Depth** → How well the response explores details, nuances, and examples.

---

## 3.  Test Scenarios and Responses

---

### **Scenario 1: Creative Story Generation**

* **Naïve Prompt:** *“Write a story.”*
* **Basic Prompt:** *“Write a short story (150 words) about a lost dog who finds its way home, with an emotional ending.”*

**Naïve Response (Sample Extract):**
*A dog wandered into the forest. It walked around and saw many things. Eventually, it came home. The end.*

**Basic Response (Sample Extract):**
*Max, the little brown dog, lost his way on a rainy night. Frightened and tired, he followed the smell of bread from a bakery. Along the way, a kind stranger gave him food. Guided by familiar scents, Max finally reached his home. His owner burst into tears, hugging him tightly, and Max’s tail wagged with joy.*

 **Analysis:** The naïve story is flat and lacks emotional depth. The basic prompt guided ChatGPT to create a structured, emotionally rich narrative.

---

### **Scenario 2: Factual Question Answering**

* **Naïve Prompt:** *“What is electricity?”*
* **Basic Prompt:** *“Explain electricity in simple terms, including how it is generated and used in households, in less than 200 words.”*

**Naïve Response (Sample Extract):**
*Electricity is a form of energy. It powers many things like lights and fans. It flows through wires.*

**Basic Response (Sample Extract):**
*Electricity is the flow of charged particles, usually electrons, through a conductor like copper wire. It is generated in power plants using coal, hydro, wind, or solar energy. Once generated, it travels through transmission lines and reaches homes, where it powers appliances such as lights, refrigerators, and fans. Without electricity, modern life would be nearly impossible.*

 **Analysis:** Naïve answer is vague and incomplete. The structured prompt produced a correct, simple, and application-oriented explanation.

---

### **Scenario 3: Summarization**

* **Naïve Prompt:** *“Summarize climate change.”*
* **Basic Prompt:** *“Summarize climate change in under 100 words, highlighting its causes, effects, and possible solutions.”*

**Naïve Response (Sample Extract):**
*Climate change is happening due to human activities. It affects the weather and environment. People need to stop pollution.*

**Basic Response (Sample Extract):**
*Climate change refers to long-term shifts in global temperatures and weather patterns, primarily caused by burning fossil fuels, deforestation, and industrial emissions. Its effects include rising sea levels, extreme weather, and biodiversity loss. Solutions involve renewable energy, reforestation, reduced emissions, and sustainable practices.*

 **Analysis:** The naïve summary is oversimplified. The structured prompt forces ChatGPT to include **causes, effects, and solutions** in a concise, complete format.

---

### **Scenario 4: Advice/Recommendation**

* **Naïve Prompt:** *“How to study?”*
* **Basic Prompt:** *“Give 5 practical tips for engineering students to study effectively, focusing on time management and note-taking strategies.”*

**Naïve Response (Sample Extract):**
*Study regularly. Don’t waste time. Read books and take rest.*

**Basic Response (Sample Extract):**

1. **Plan Your Schedule:** Divide your day into focused study blocks.
2. **Use Active Note-Taking:** Write key points in your own words for better retention.
3. **Practice Problem-Solving:** For engineering, solve numerical problems daily.
4. **Review Regularly:** Revise notes weekly instead of last-minute cramming.
5. **Stay Balanced:** Take short breaks and maintain healthy sleep to avoid burnout.

 **Analysis:** Naïve tips are generic and obvious. Basic prompt yields **specific, actionable strategies** tailored to engineering students.

---

## 4.  Comparison Table

| **Scenario**          | **Naïve Prompt Output** | **Basic Prompt Output**  | **Quality** | **Accuracy** | **Depth** |
| --------------------- | ----------------------- | ------------------------ | ----------- | ------------ | --------- |
| Creative Story        | Short, generic          | Structured, emotional    | ⭐⭐          | ⭐⭐           | ⭐⭐⭐⭐      |
| Factual Question      | Vague, incomplete       | Clear, application-based | ⭐⭐          | ⭐⭐⭐⭐         | ⭐⭐⭐       |
| Summarization         | Oversimplified          | Concise, complete        | ⭐⭐          | ⭐⭐⭐⭐         | ⭐⭐⭐       |
| Advice/Recommendation | General, obvious tips   | Specific, tailored tips  | ⭐⭐          | ⭐⭐⭐          | ⭐⭐⭐⭐      |

---

## 5.  Visuals

### **Bar Chart: Naïve vs. Basic Prompt Performance**

(Already generated earlier ).

 [Click to open chart](sandbox:/mnt/data/prompt_comparison_chart.png)

### **Flow Diagram: Prompt Clarity → Better Output**

```
Naïve Prompt (Vague, Broad) → Generic Output (Low Depth)
          ↓
Basic Prompt (Clear, Structured) → Focused Output (High Quality, High Accuracy)
```

This can be shown as a **funnel diagram** or **process flow chart** in your report slides.

---

## 6.  Findings & Insights

1. **Prompt clarity directly improves AI performance** → Clear prompts consistently give more accurate and detailed outputs.
2. **Naïve prompts only work well in creativity** → Broad prompts sometimes allow “open imagination,” but lack control.
3. **Basic prompts are best for structured tasks** like factual Q\&A, summarization, and recommendations.
4. **For optimal results, always include:**

   * Context (what exactly you need).
   * Structure (word count, format, key points).
   * Constraints (focus area, audience type).

---

## 7.  Conclusion

This experiment proves that **prompt engineering** is a critical skill when working with AI tools like ChatGPT. By refining vague instructions into **basic, structured prompts**, users can achieve **higher quality, accuracy, and depth** in the generated responses.



---
<img width="1600" height="1000" alt="prompt_comparison_chart" src="https://github.com/user-attachments/assets/33495cf3-02e6-42d1-9436-e57154ef241f" />





# RESULT: The prompt for the above said problem executed successfully
