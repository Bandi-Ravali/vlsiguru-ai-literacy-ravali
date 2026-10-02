# Week 01 AI Assistant Comparison

## Common question

**In Python, what does the `list.sort()` method return?**

## Tool 1
**Name:** ChatGPT

**Answer summary:**  
It returns `None` and sorts the original list in place.

**Strengths:**  
- Gave the correct answer.
- Clearly explained that the original list is modified.

**Weaknesses:**  
- The answer still needed to be checked with an official source.

## Tool 2
**Name:** Google Gemini

**Answer summary:**  
It said that `list.sort()` returns the sorted list.

**Strengths:**  
- Gave a direct and simple answer.

**Weaknesses:**  
- The answer was incorrect.
- It did not correctly explain the return value of `list.sort()`.

## Verification source

**Reference:** Official Python documentation

The documentation confirms that `list.sort()` sorts the list in place and returns `None`.

## Final comparison

- **Accuracy:** ChatGPT was correct; Google Gemini was incorrect.
- **Traceability:** The result could be checked using the official Python documentation.
- **Explanation quality:** ChatGPT provided the more accurate explanation.
- **Ease of verification:** Easy to verify using the Python documentation.
- **Which claims required correction or qualification?**  
  The Gemini claim that `list.sort()` returns the sorted list required correction. The correct return value is `None`.

## Lesson

I learned that different AI assistants can give different answers to the same question. I should check technical information with an official or reliable source before accepting an AI answer as correct.
