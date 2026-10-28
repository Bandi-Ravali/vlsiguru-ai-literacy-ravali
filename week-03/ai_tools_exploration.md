# Week 03 AI Tools Exploration

## 1. Introduction

AI tools can help students understand technical concepts, practise programming, explore documentation, and organise their learning. However, AI responses may contain errors, so important technical information must be verified using reliable sources.

The objective of this exploration is to understand how AI tools can support engineering learning and how prompt quality affects the answers they provide.

## 2. AI Tools and Their Uses

| AI Tool | Possible Use | Limitation to Consider |
|---|---|---|
| ChatGPT | Explaining concepts, generating examples, and helping with programming practice. | Responses can contain incorrect or incomplete information. |
| Google Gemini | Exploring topics and comparing explanations. | Technical claims still require verification. |
| Claude | Understanding longer explanations and working with documents. | Responses should be checked for accuracy and relevance. |
| NotebookLM | Studying information from supplied sources and generating source-based summaries. | Results depend on the quality and coverage of the supplied sources. |
| Perplexity | Exploring topics and locating information with source links. | Sources must be checked to confirm that they support the claims. |
| GitHub Copilot | Assisting with code completion and programming tasks. | Generated code may contain errors or fail to meet the requirements. |

These are potential uses of the tools. My personal observations should be added after I have actually tested them.

## 3. Prompt Experiment 1: Learning Physical Design

### Initial Prompt

"Explain Physical Design in VLSI."

### Observation

This prompt is broad. The response may provide a general introduction without explaining each stage in enough detail for a beginner.

### Improved Prompt

"I am a beginner learning VLSI Physical Design. Explain floorplanning, placement, clock tree synthesis (CTS), timing optimization, and routing in simple language. For each stage, explain its purpose, typical inputs and outputs, and one common problem. Give a simple example and provide reliable documentation links."

### Why the Improved Prompt Is Better

- It identifies my learning level.
- It specifies the exact topics.
- It requests a structured explanation.
- It asks for examples and technical sources.
- It helps me focus on the information I need.

### My Observation

[After testing both prompts, describe how the responses differed in clarity, detail, examples, and accuracy.]

## 4. Prompt Experiment 2: Learning Python

### Initial Prompt

"Teach me Python."

### Improved Prompt

"I am a beginner learning Python. Explain Python lists using simple language. Show how to create a list, access elements, add elements, remove elements, and iterate through a list. Provide a small code example, explain each line, and include two practice questions."

### Why the Improved Prompt Is Better

The improved prompt specifies the topic, my skill level, the concepts to cover, and the type of examples I need. This makes the response more focused and easier to practise.

### My Observation

[Record what you noticed after trying the prompts.]

## 5. Comparing AI Tool Responses

To compare AI tools fairly, I can ask the same technical question in two tools and evaluate their answers using the same criteria.

| Criterion | What I Will Check |
|---|---|
| Clarity | Is the explanation easy to understand? |
| Accuracy | Does the information agree with reliable technical documentation? |
| Examples | Are the examples relevant and useful? |
| Sources | Are the sources genuine and relevant to the claim? |
| Limitations | Does the answer mention uncertainty or missing information? |

### Comparison Results

**Tool 1:** [Enter the tool tested.]

**Tool 2:** [Enter the tool tested.]

**Question asked:** [Enter the same question used in both tools.]

**My conclusion:** [Explain which response was more useful and why, based on your actual comparison.]

## 6. Reusable Prompt Framework

A useful prompt can include the following elements:

1. Role or context: Explain what I am learning.
2. Skill level: Beginner, intermediate, or advanced.
3. Topic: Specify the exact subject.
4. Task: Explain, compare, debug, summarise, or demonstrate.
5. Format: Request a table, steps, examples, or code.
6. Verification: Request reliable sources and identify uncertainty.

### Example

"I am a beginner studying Physical Design. Explain clock tree synthesis in simple language, describe why it is needed, list its typical inputs and outputs, and give an example of a clock-skew problem. Use reliable sources and clearly identify anything that needs further verification."

## 7. Technical Claim Verification

### Claim to Investigate

OpenROAD provides functionality for digital physical-design tasks, including placement, clock tree synthesis, and routing.

### Source

Official OpenROAD documentation:

https://openroad.readthedocs.io/en/latest/

OpenROAD Flow Scripts User Guide:

https://openroad-flow-scripts.readthedocs.io/en/latest/user/UserGuide.html

### Verification Process

1. Identify the technical claim made by the AI tool.
2. Open the official documentation.
3. Find the section that describes the relevant functionality.
4. Compare the documentation with the AI response.
5. Record what is supported and correct any unsupported statements.

### Verification Result

[After checking the documentation, explain what it confirms and whether the AI response was accurate.]

## 8. Responsible AI Use

- I will verify important technical information before using it.
- I will test generated code instead of assuming it works.
- I will not treat AI-generated answers as proof.
- I will not invent sources or claim that I performed experiments I did not perform.
- I will avoid uploading confidential RTL, netlists, timing constraints, or proprietary chip-design information to public AI services.
- I will follow the assignment's rules for acknowledging AI assistance.

## 9. Conclusion

AI tools can support engineering education by explaining concepts, providing examples, and helping students practise. Effective prompts make responses more focused, while reliable documentation helps verify technical accuracy. Responsible use requires independent thinking and checking the information before relying on it.

## References

- OpenROAD Documentation: https://openroad.readthedocs.io/en/latest/
- OpenROAD Flow Scripts User Guide: https://openroad-flow-scripts.readthedocs.io/en/latest/user/UserGuide.html
- OpenAI Academy: https://academy.openai.com/
- Google AI Education: https://ai.google/education/
