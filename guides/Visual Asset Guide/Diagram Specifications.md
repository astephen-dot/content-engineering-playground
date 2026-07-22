# **Diagram Specifications**

**Version:** V1.0  
**Purpose:** Design System Guide  
**Stage:** Visual Pattern Selection → Visual Asset Generation

---

# **Overview**

The Diagram Specifications guide defines the standards for constructing visual assets recommended by the Visual Pattern Library.

Its purpose is to ensure consistency, readability, accessibility, and scalability across all generated visuals.

This guide does not determine *which* visual to create. It defines *how* approved visual patterns should be constructed.

---

# **Design Philosophy**

Every diagram should prioritize:

* Clarity over decoration  
* Simplicity over complexity  
* Consistency over creativity  
* Readability over density  
* Communication over aesthetics

A reader should understand the core message within a few seconds of viewing the visual.

---

# **Universal Design Rules**

Every visual must satisfy the following principles:

### **1\. One Message Per Visual**

Each visual should communicate one primary concept.

Do not combine unrelated ideas into a single diagram.

---

### **2\. Progressive Disclosure**

Information should be revealed naturally.

Readers should not need to inspect every element to understand the main idea.

Prioritize:

1. Headline  
2. Structure  
3. Supporting Details

---

### **3\. Visual Hierarchy**

Every visual should establish a clear hierarchy using:

* Size  
* Weight  
* Position  
* Contrast  
* Spacing

The most important information should attract attention first.

---

### **4\. Cognitive Load**

Reduce unnecessary mental effort.

Avoid:

* Excessive labels  
* Decorative elements  
* Repeated information  
* Overly complex layouts

---

# **Layout Guidelines**

## **Process Diagram**

Preferred Layout

```
Start

↓

Step 1

↓

Step 2

↓

Step 3

↓

Outcome
```

Maximum recommended steps:

**7**

If more than seven steps are required, split into multiple diagrams.

---

## **Framework Diagram**

Preferred Layout

```
Central Idea

↓

Supporting Pillars

↓

Capabilities

↓

Examples
```

Maximum layers:

**4**

---

## **Timeline**

Preferred Layout

```
Past

────────────►

Present

────────────►

Future
```

Avoid timelines containing excessive milestones.

---

## **Comparison Matrix**

Recommended columns:

2–5

Recommended rows:

4–8

Highlight key differences rather than exhaustive specifications.

---

## **Decision Tree**

Maximum decision depth:

5 levels

Branches should remain balanced where possible.

---

## **Architecture Diagram**

Organize systems by logical grouping rather than technical ownership.

Suggested hierarchy:

```
User

↓

Application

↓

Platform

↓

Data

↓

Infrastructure
```

Connections should remain easy to trace.

---

# **Typography Guidelines**

Use concise labels.

Preferred label length:

**2–5 words**

Avoid paragraphs inside diagrams.

Headings should clearly describe the purpose of the visual.

Sentence case is preferred.

---

# **Icons**

Icons should:

* Reinforce meaning  
* Be visually consistent  
* Represent concepts rather than decoration

Avoid mixing icon styles within a single visual.

---

# **Connectors**

Directional flow should always be obvious.

Use:

* Arrows for movement  
* Lines for relationships  
* Dashed lines for optional connections

Avoid crossing connectors whenever possible.

---

# **Colour Usage**

Colour should communicate information, not decorate.

Recommended uses:

* Distinguish categories  
* Show progression  
* Highlight emphasis  
* Indicate status

Avoid assigning unique colours to every element without meaning.

---

# **White Space**

Maintain sufficient spacing between elements.

White space improves comprehension and reduces cognitive load.

Do not fill empty areas unnecessarily.

---

# **Accessibility Standards**

Every visual should:

* Maintain sufficient contrast  
* Avoid colour-only distinctions  
* Include meaningful labels  
* Support descriptive alt text  
* Be readable on desktop and mobile  
* Remain understandable when printed in grayscale where practical

---

# **Mobile Adaptation**

Visuals should scale effectively for smaller screens.

Recommendations:

* Minimize text  
* Increase spacing  
* Avoid overly wide layouts  
* Stack components vertically when appropriate

---

# **Complexity Guidelines**

### **Low Complexity**

Suitable for:

* Hero graphics  
* Checklists  
* Simple comparisons

Expected review:

None or minimal.

---

### **Medium Complexity**

Suitable for:

* Frameworks  
* Process diagrams  
* Journey maps

Expected review:

Content or design review recommended.

---

### **High Complexity**

Suitable for:

* Architecture diagrams  
* KPI dashboards  
* Infographics

Expected review:

Designer review required before publication.

---

# **Pattern-Specific Recommendations**

| Pattern | Maximum Elements | Ideal Reading Time |
| ----- | ----- | ----- |
| Process Diagram | 7 steps | 15–30 seconds |
| Framework Diagram | 5 pillars | 20–40 seconds |
| Timeline | 8 milestones | 20–30 seconds |
| Comparison Matrix | 5 × 8 grid | 30–45 seconds |
| Decision Tree | 5 levels | 30–60 seconds |
| Architecture Diagram | 15 components | 45–90 seconds |
| Journey Map | 8 stages | 30–45 seconds |
| Checklist | 10 items | 15–20 seconds |
| KPI Dashboard | 8 metrics | 30–45 seconds |

---

# **Diagram Quality Checklist**

Before approving any visual, verify:

* Does the visual communicate one clear idea?  
* Is the structure immediately understandable?  
* Is information logically grouped?  
* Are labels concise?  
* Is visual hierarchy clear?  
* Are connectors easy to follow?  
* Is unnecessary information removed?  
* Can the visual be understood without reading the full article?  
* Is it accessible and mobile-friendly?

---

# **Output Format**

```
Diagram Specification

Pattern:
Framework Diagram

Layout:
Layered

Reading Direction:
Top to Bottom

Maximum Elements:
5 Primary Sections

Typography:
Short labels (2–5 words)

Icons:
One consistent icon set

Colour Strategy:
Use colour only to distinguish conceptual groups

Complexity:
Medium

Accessibility:
Provide alt text, maintain contrast, avoid colour-only distinctions

Mobile Ready:
Yes

Designer Review:
Recommended
```

---

## **Why this guide matters**

The first three guides now form a clear decision pipeline:

```
Visual Decision Framework
        ↓
"Do I need a visual?"

Visual Pattern Library
        ↓
"What type of visual best communicates this?"

Diagram Specifications
        ↓
"How should that visual be structured and designed?"
```

At this point, you've separated **strategy**, **pattern selection**, and **design standards**. The final guide can then focus purely on translating these decisions into **tool-specific generation instructions** (for Firefly, Canva, or any future image-generation system), without mixing implementation concerns into the earlier guides.

