I would rewrite it from scratch to make it **tool-agnostic**. This guide should never mention Firefly, Claude, Canva, Figma, or any other software. Its sole purpose is to determine **what visual assets are required** and **why**.

---

# **Visual Decision Framework**

**Version:** V2.0  
**Purpose:** Knowledge Guide  
**Stage:** Post Draft Generation → Pre Visual Asset Planning

---

# **Overview**

The Visual Decision Framework helps AI determine the visual requirements for a content asset by evaluating the communication needs of the content.

The framework identifies whether visual assets are required, defines their communication objectives, and recommends the most appropriate visual strategy to improve reader understanding and engagement.

This guide focuses exclusively on **visual planning**. It does not define visual execution, software, or generation methods.

---

# **Core Principles**

Visuals are communication tools, not decorative assets.

Every recommended visual should serve a clear purpose that improves the reader's experience.

Visual assets should:

* Improve comprehension  
* Reduce cognitive load  
* Explain complex concepts  
* Reinforce important information  
* Support decision making  
* Improve scanability  
* Strengthen editorial storytelling

Visuals should never be recommended solely to fill space or increase visual appeal.

---

# **Visual Asset Categories**

Content may contain two independent visual asset types.

## **Hero Image**

The Hero Image introduces the article and establishes its visual identity.

Its objectives include:

* Introducing the topic  
* Establishing tone  
* Creating visual interest  
* Supporting editorial storytelling  
* Reinforcing brand consistency

A Hero Image should not attempt to explain detailed concepts, workflows, or data.

---

## **Supporting Visuals**

Supporting visuals improve comprehension throughout the article.

Their objectives include:

* Explaining processes  
* Showing relationships  
* Comparing alternatives  
* Presenting research  
* Summarizing information  
* Supporting complex explanations

Supporting visuals should always communicate information that would otherwise require significant reading effort.

---

# **AI Evaluation Process**

The AI should evaluate every article using the following sequence.

---

# **Step 1 — Determine Hero Image Requirement**

Evaluate whether the article requires a Hero Image.

### **Recommended for**

* Blog articles  
* Thought leadership  
* Research articles  
* Editorial content  
* Long-form guides  
* Feature articles

  ### **Optional for**

* Release notes  
* Product updates  
* Technical documentation  
* Knowledge base articles  
* Internal documentation  
  ---

  ### **Output**

```
Hero Image Required: Yes
```

or

```
Hero Image Required: No

Reason:
The content does not require an editorial introduction.
```

---

# **Step 2 — Determine Supporting Visual Requirements**

Evaluate whether supporting visuals improve understanding.

Answer the following questions.

| Question | Yes | No |
| ----- | ----- | ----- |
| Does the article explain a process? | □ | □ |
| Does it describe relationships between concepts? | □ | □ |
| Does it compare alternatives? | □ | □ |
| Does it present research or quantitative information? | □ | □ |
| Does it introduce a framework or methodology? | □ | □ |
| Does it explain technical systems? | □ | □ |
| Would readers understand significantly faster with a visual? | □ | □ |

---

### **Decision**

If all responses are **No**

```
Supporting Visual Required: No

Reason:
The article is primarily narrative and additional visuals would not improve comprehension.
```

Otherwise continue.

---

# **Step 3 — Define the Communication Objective**

Each recommended supporting visual should communicate one primary objective.

Select the most appropriate objective.

| Objective | Description |
| ----- | ----- |
| Explain | Clarify concepts or processes |
| Compare | Highlight differences or alternatives |
| Summarize | Condense large amounts of information |
| Guide | Walk readers through a sequence |
| Validate | Present supporting evidence |
| Visualize | Show relationships or systems |
| Persuade | Reinforce recommendations |

Only one primary objective should be selected for each supporting visual.

---

# **Step 4 — Assess Information Complexity**

Evaluate the overall complexity of the information.

## **Low Complexity**

Characteristics

* Single idea  
* Limited relationships  
* Primarily narrative

Recommendation

Supporting visuals are optional.

---

## **Medium Complexity**

Characteristics

* Multiple related concepts  
* Sequential explanations  
* Moderate decision-making

Recommendation

One explanatory visual is recommended.

---

## **High Complexity**

Characteristics

* Technical systems  
* Research-heavy content  
* Multiple stakeholders  
* Interconnected concepts

Recommendation

Multiple supporting visuals may be recommended.

---

# **Step 5 — Determine Information Structure**

Identify how the information is organized.

| Structure | Description |
| ----- | ----- |
| Sequential | Step-by-step progression |
| Hierarchical | Parent-child relationships |
| Comparative | Side-by-side evaluation |
| Cyclical | Continuous process |
| Chronological | Events over time |
| Network | Connected systems |
| Matrix | Multi-dimensional comparison |
| Layered | Nested concepts |

The information structure determines the most appropriate visual pattern.

---

# **Step 6 — Determine Visual Placement**

Identify where each visual should appear.

## **Hero Image**

Default placement:

* Beginning of the article  
* Supporting the article title  
  ---

  ## **Supporting Visuals**

Possible placements

| Placement | Purpose |
| ----- | ----- |
| After Introduction | Introduce key concepts early |
| Mid-Article | Support detailed explanations |
| Before Conclusion | Summarize important ideas |
| Sidebar | Provide supporting context |
| Callout | Highlight key insights |

Visuals should appear as close as possible to the content they support.

---

# **Step 7 — Assess Visual Complexity**

Determine the complexity of the recommended visual.

| Complexity | Characteristics |
| ----- | ----- |
| Simple | Single concept with minimal relationships |
| Medium | Multiple connected ideas or sequential flow |
| Complex | Technical systems, extensive research, or multiple interacting concepts |

Complexity should be proportional to the information being communicated.

---

# **Step 8 — Accessibility Review**

Before finalizing recommendations, verify that the proposed visual can:

* Be understood independently of surrounding paragraphs  
* Support logical reading order  
* Maintain readability across devices  
* Minimize unnecessary visual clutter  
* Use meaningful labels  
* Support descriptive alternative text  
* Follow accessibility best practices  
  ---

  # **Final Output Format**

Every evaluation should produce a standardized **Visual Asset Requirement**.

```
Hero Image

Required: Yes

Purpose:
Introduce the topic and establish editorial context.

Supporting Visuals

Required: Yes

Primary Objective:
Explain

Information Structure:
Sequential

Recommended Pattern:
Process Diagram

Complexity:
Medium

Placement:
After Introduction

Reason:
The article explains a multi-step workflow that is easier to understand when represented visually.

Accessibility Notes:
Maintain clear labels, logical flow, descriptive alternative text, and mobile readability.
```

---

# **Decision Principles**

The AI should follow these principles in order of priority.

1. Prioritize reader comprehension over visual complexity.  
2. Treat Hero Images and Supporting Visuals as independent asset types.  
3. Recommend visuals only when they improve communication.  
4. Prefer one effective visual over multiple redundant visuals.  
5. Choose the simplest visual capable of communicating the intended message.  
6. Avoid visuals that duplicate surrounding text without adding value.  
7. When uncertain, recommend fewer visuals rather than unnecessary ones.  
   

