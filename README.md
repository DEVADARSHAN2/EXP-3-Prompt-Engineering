
# **EXP-3: PROMPT ENGINEERING**

## **Aim**

To evaluate and compare the performance of advanced 2024 prompting tools across five leading AI platforms—**ChatGPT (OpenAI), Claude (Anthropic), Bard/Gemini (Google), Cohere Command, and Meta AI**—within the use cases of **text summarization** and **technical question answering**.

---

## **Algorithm **

### **1. Define Scope & Dataset**

* **Use Cases:**
  a) Summarization
  b) Technical Question Answering

* **Prompt Design:**
  Prompts created for both **simple** and **complex** input cases.

### **2. Define Evaluation Rubric**

* **Metrics:**

  * **Accuracy**
  * **Relevance**
  * **Clarity**
  * **Completeness / Depth**
  * **Conciseness**
  * **Safety** (No hallucinations)

* **Scale:**
  1–5 score per metric.

### **3. Generate Outputs**

* Same prompts issued to all five AI platforms.
* Outputs collected with metadata (time, version, model type).

### **4. Evaluation**

* **Blind Review:** Human raters scored outputs with no platform labels.
* **Quantitative + Qualitative** scoring used.

### **5. Aggregate Scores**

* Mean score per metric across each platform.
* **Composite scores** calculated for overall performance.

### **6. Analysis**

* Statistical comparison and pattern recognition:

  * Verbosity
  * Depth
  * Simplification level
  * Tone (technical, conversational)

### **7. Reporting**

* **Prompt → Output → Result** structure.
* Comparative ranking tables with key insights.

---

## **Experiment & Results**

---

### ** Case 1: Summarizing General Text**

**Prompt:**
*“Summarize the following text into three sentences:
Artificial intelligence is rapidly evolving and is transforming industries such as healthcare, education, and finance. However, ethical challenges related to privacy, fairness, and accountability remain critical. Governments, researchers, and companies are working together to ensure responsible deployment of AI.”*

#### **ChatGPT Output:**

> Artificial intelligence is revolutionizing industries like healthcare, education, and finance. Ethical issues such as privacy, fairness, and accountability remain central challenges. Governments, researchers, and companies are collaborating for responsible AI deployment.
> **Result:**  Balanced | Clear | Concise | **Score: 5/5**

#### **Claude Output:**

> AI is transforming sectors like healthcare, finance, and education at a rapid pace. This expansion raises ethical issues around privacy, fairness, and accountability. Governments and industries are cooperating to ensure responsible AI.
> **Result:**  Professional | Slightly formal | **Score: 4.5/5**

#### **Bard/Gemini Output:**

> AI is changing industries but creates challenges like fairness and privacy. Governments and companies are finding solutions. The aim is to ensure responsible AI for society.
> **Result:**  Simplified | Lacks depth | **Score: 3.5/5**

#### **Cohere Command Output:**

> AI is spreading across finance, education, and healthcare. Ethical concerns—privacy, fairness, and accountability—affect adoption. Governments and companies are acting to build trust in AI.
> **Result:**  Technical tone | Accurate | **Score: 4/5**

#### **Meta AI Output:**

> AI affects finance, healthcare, and education. Challenges include privacy and accountability. Governments and researchers work for safe AI.
> **Result:**  Fragmented | Shallow | **Score: 3/5**

---



### ** Case 2: Technical Question Answering**

**Prompt:**
*“What is the role of power electronics in Vehicle-to-Grid (V2G) systems?”*

#### **ChatGPT Output:**

> Power electronics enable bidirectional energy flow between EV batteries and the grid. They manage charging and discharging while ensuring voltage regulation, safety, and grid stability.
> **Result:**  Highly Accurate | Technical + Clear | **Score: 5/5**

#### **Claude Output:**

> In V2G, power electronics control energy exchange between the grid and EV batteries. They enable charging/discharging and maintain safety and efficiency.
> **Result:**  Concise | Informative | **Score: 4.5/5**

#### **Bard/Gemini Output:**

> Power electronics let vehicles charge and discharge power safely. This balances the grid.
> **Result:**  Too simple | Basic | **Score: 3/5**

#### **Cohere Command Output:**

> Power electronics are the backbone of V2G, providing DC–AC conversion, switching, and protection. They ensure EVs act as reliable grid resources.
> **Result:**  Technical depth | Slight jargon | **Score: 4/5**

#### **Meta AI Output:**

> V2G uses power electronics for charging, discharging, and conversion between vehicles and the grid.
> **Result:**  Minimal explanation | Functional | **Score: 3/5**

---



### ** Case 3: Summarizing Renewable Energy Text**

**Prompt:**
*“Summarize the following passage into a short paragraph:
Renewable energy sources, such as solar, wind, and hydropower, are increasingly adopted to reduce dependence on fossil fuels. These energy systems are environmentally friendly, sustainable, and help in reducing carbon emissions. However, challenges remain in terms of energy storage, grid integration, and cost competitiveness.”*

#### **ChatGPT Output:**

> Renewable sources like solar, wind, and hydropower reduce reliance on fossil fuels and cut carbon emissions. They are eco-friendly and sustainable but face challenges of storage, grid integration, and costs.
> **Result:**  Clear | Balanced | **Score: 5/5**

#### **Claude Output:**

> Solar, wind, and hydropower are growing as sustainable energy options that lower fossil fuel use and emissions. Despite their benefits, challenges with storage, integration, and affordability remain.
> **Result:**  Smooth tone | Professional | **Score: 4.5/5**

#### **Bard/Gemini Output:**

> Renewables like solar, wind, and hydropower cut emissions and replace fossil fuels. They are sustainable but struggle with storage, integration, and costs.
> **Result:**  Easy to understand | Simple | **Score: 4/5**

#### **Cohere Command Output:**

> Renewable energy, including solar, wind, and hydropower, offers sustainable, low-carbon alternatives to fossil fuels. But growth is limited by storage, integration, and cost barriers.
> **Result:**  Structured | Technically strong | **Score: 4.5/5**

#### **Meta AI Output:**

> Solar, wind, and hydropower help reduce fossil fuel use but face storage, grid, and cost issues.
> **Result:**  Brief | Lacks context | **Score: 3/5**

---



## **📊 Comparative Evaluation**
| **Platform**    | **Case 1: Summarization (General AI Text)** | **Case 2: Technical Q\&A (V2G)** | **Case 3: Summarization (Renewables)** | **Average Score** |
| --------------- | ------------------------------------------- | -------------------------------- | -------------------------------------- | ----------------- |
| **ChatGPT**     |  5/5 – Balanced, Clear, Concise            |  5/5 – Accurate, Technical      |  5/5 – Clear, Balanced                | **5.0**           |
| **Claude**      |  4.5/5 – Professional, Slightly formal     |  4.5/5 – Concise, Informative   |  4.5/5 – Smooth, Professional         | **4.5**           |
| **Bard/Gemini** |  3.5/5 – Simplified, lacks depth          |  3/5 – Too simple, basic       |  4/5 – Easy, simple                   | **3.5**           |
| **Cohere**      |  4/5 – Technical tone, accurate            |  4/5 – Jargon, technical        |  4.5/5 – Strong, structured           | **4.2**           |
| **Meta AI**     |  3/5 – Fragmented, shallow                |  3/5 – Minimal explanation     |  3/5 – Brief, lacks context          | **3.0**           |


---

## ** Observations & Insights**

* **ChatGPT (OpenAI):**
  Outstanding in combining clarity, depth, and natural tone. Excellent for both academic and real-world applications.

* **Claude (Anthropic):**
  Highly articulate and ethically cautious. Slightly less detailed in technical contexts.

* **Cohere Command:**
  Very strong in technical domains. Feels formal and structured—ideal for enterprise and industry tasks.

* **Bard/Gemini (Google):**
  Prioritizes accessibility and brevity. Good for casual users or educational settings, but lacks technical rigor.

* **Meta AI:**
  Consistently brief. Good factual recall but fails to provide elaboration or critical reasoning.

---

## ** Conclusion**

The experiment revealed **ChatGPT** as the top-performing prompting tool in 2024 across use cases. It consistently delivered high-quality outputs with clarity, relevance, and depth. **Claude** followed closely, excelling in clarity and phrasing. **Cohere Command** proved technically robust but less conversational. **Bard/Gemini** offered simplicity at the cost of depth, while **Meta AI** functioned as a baseline model.

---


