# Week 01 - The AI Landscape

## Q1-Distingish AI, ML, DL, GenAI and agents
### A-Answer 
1. Artificial Intelligence (AI)
Artificial Intelligence is a technology that makes computers or machines perform tasks that normally need human intelligence. It can help machines understand information, recognize things, solve problems, and make decisions.
2. Machine Learning (ML)
Machine Learning is a part of Artificial Intelligence. In Machine Learning, a computer learns from data and finds patterns in it. After learning from previous data, it can use those patterns to make predictions or decisions about new data.
3. Deep Learning (DL)
Deep Learning is a type of Machine Learning. It uses neural networks with many layers to learn complicated patterns from data. It is commonly used for images, speech, and other complex types of information.
4. Generative AI
Generative AI is a type of AI that can create new content based on the instructions given by a user. It can generate text, images, code, audio, and other types of content.
5. AI Agent
An AI Agent is a system that can understand a goal and perform multiple steps to achieve that goal. It can decide what needs to be done and can use available tools to perform actions.
Relationship Between Generative AI and AI Agents
Generative AI mainly focuses on creating new content from a user's instructions. For example, it can generate text, images, or code.
An AI Agent focuses on achieving a particular goal by performing a series of steps. It can use an AI model and available tools to complete the task.
The main difference is that Generative AI mainly creates content, while an AI Agent uses AI to plan and take actions toward a goal. An AI Agent can also use Generative AI as one part of its system.
concept map:

Q1 – AI Concept Map

                         ARTIFICIAL INTELLIGENCE (AI)
                                      |
              ┌───────────────────────┼───────────────────────┐
              |                       |                       |
              ↓                       ↓                       ↓
      MACHINE LEARNING         GENERATIVE AI             AI AGENT
              |                       |                       |
              ↓                       ↓                       ↓
       DEEP LEARNING            Creates new            Understands goal
                                content                      |
                           ┌─────┼─────┐                      ↓
                           |     |     |                  Plans steps
                           ↓     ↓     ↓                      |
                         Text  Image  Code                     ↓
                                                           Uses tools
                                                               |
                                                               ↓
                                                          Takes actions
                                                               |
                                                               ↓
                                                         Completes task


Examples:

AI                 → Voice assistant
Machine Learning   → Spam email detection
Deep Learning      → Image recognition
Generative AI      → AI writing an email
AI Agent           → AI planning a trip using different tools

Relationship
* **AI** is the broad field of making machines perform tasks that normally need human intelligence.
* **Machine Learning (ML)** is a part of AI where systems learn patterns from data.
* **Deep Learning (DL)** is a type of ML that uses multi-layer neural networks.
* **Generative AI** creates new content such as text, images and code.
* **AI Agents** can understand a goal, plan steps, use tools and take actions to complete a task.

# E-Evidence
I checked the basic information about AI, ML, DL, Generative AI and AI Agents from IBM and Google Cloud. The sources helped me understand that ML is a part of AI, DL is a type of ML, Generative AI is used to create new content, and AI Agents can perform tasks by planning and using tools.

# V-Verification
I used ChatGPT and Google Gemini to get a basic understanding of the topics. After that, I checked the information with IBM and Google Cloud. I compared the information from these sources and used it to make my final answers and concept map.

# R-Reflection
While doing this question, I got a better understanding of the differences between AI, ML, DL, Generative AI and AI Agents. Earlier, I thought these terms were almost the same, but now I understand how they are related. I learned that Generative AI creates content, while an AI Agent can take steps and use tools to complete a task. This assessment helped me understand the topic in a simple and practical way.

# Q2. Is Everything That Looks Intelligent Actually AI?
## A-Answer

|  Case    |   Scenario                               |   Classification     |       Reason                                |
| -------- | ---------------------------------------- | -------------------- | ------------------------------------------- |
| A        | Calculator gives 25 × 16 = 400           | Traditional Software | Uses a fixed calculation.                   |
| B        | If temperature > 80°C, show WARNING      | Traditional Software | Follows a fixed rule.                       |
| C        | Email detects spam using previous emails | Machine-Learning AI  | Learns patterns from old emails.            |
| D        | AI assistant summarizes a document       | Generative AI        | Creates new text as a summary.              |
| E        | Navigation predicts arrival time         | Machine-Learning AI  | Uses traffic and past data to predict time. |

A normal program follows fixed instructions given by the programmer. AI can learn from data and use patterns to make predictions or create new content. So, not every smart-looking or automated system is AI.
## E- Evidence
I checked the concepts using IBM and other reliable sources. They explain that traditional software follows fixed rules, while AI can learn from data or generate new content.

## V-Verification
I used ChatGPT and Google Gemini to understand the examples and then checked the information with reliable sources.

## R-Reflection
This question helped me understand that not every smart-looking system is AI. I learned the simple difference between fixed-rule programs and AI systems that learn or create.

# Q3. What Happens When You Ask an LLM a Question?
## A-Answer
When we give a prompt to an LLM, the model first breaks the text into small parts called tokens. It looks at the context of the prompt and processes the information. Then, it calculates the probability of different possible next tokens and selects one. It keeps predicting the next token step by step until it produces the generated response.
Flow Diagram

                                                  
                                                          Prompt
                                                             ↓
                                                           Tokens
                                                             ↓
                                                      Model Processing
                                                             ↓
                                                  Probability Distribution
                                                             ↓
                                                     Next Token Selection
                                                             ↓
                                                    Generated Response

Terms:
| Term                  | Simple Meaning                                                           |
| --------------------- | ------------------------------------------------------------------------ |
| Prompt                | The question or instruction given to the model.                          |
| Token                 | A small piece of text that the model processes.                          |
| Context               | The information available to the model from the prompt and conversation. |
| Probability           | How likely each possible next token is.                                  |
| Next-token prediction | Predicting what token should come next.                                  |
| Generated response    | The final text produced by the model.                                    |

Why Can an LLM Give False Information?
An LLM is mainly predicting likely sequences of words/tokens based on patterns it learned. So, it can produce fluent and convincing language even when the information is incorrect or unsupported.
# E-Evidence
I checked how an LLM works using reliable sources like IBM and Google. They explain that language models use tokens and predict the next token to generate a response.

# V-Verification
I compared the information from these sources with what I learned from ChatGPT and Google Gemini. The basic process matched, so I used it for my answer.

# R-Reflection
This question helped me understand what happens when I ask a question to an LLM. I learned that it predicts the next token step by step to create a response. I also understood why an LLM can sometimes give a fluent answer that is not true.

# Q4. Hallucination Experiment: Can AI Sound Confident and Still Be Wrong?
## A-Answer
Question that I Asked
“In Python, what does the list.sort() method return?”
ChatGPT Answer :
ChatGPT said that list.sort() returns None and sorts the original list.
Google Gemini Answer :
Gemini said that list.sort() returns the sorted list.
Explanation :
I selected this question because it has one clear answer that can be checked. Both AI tools gave different answers, so I checked them with the official Python documentation.
# E-Evidence
The Python documentation says that list.sort() sorts the original list in place and returns None.

# V-Verification
After checking the documentation, I found that the ChatGPT answer was correct and the Gemini answer was wrong.

# R-Reflection
This experiment helped me understand that AI can give a confident answer even when the answer is wrong. I learned that we should check important information with a reliable source instead of trusting AI blindly.
# Q5. AI Assistant vs Search vs Authoritative Reference
Technical Question
What is the default port number used by HTTP?

| Method                  | Answer / Finding                                 | Accuracy | Explanation                                                   |
| ----------------------- | -------------------------------------------------| -------- | ------------------------------------------------------------- |
| AI Assistant            | HTTP normally uses port 80.                      | Correct  | Gives a quick and simple explanation.                         |
| Web Search              | Search results also show that HTTP uses port 80. | Correct  | Gives multiple sources to compare.                            |
| Authoritative Reference | IANA lists 80 as the registered port for HTTP.   | Correct  | It is an official source and can be trusted for verification. |

Differences: 
AI Assistant: Easy and fast, but the answer should be checked for important decisions.
Web Search: Gives more information and different sources, but not every website is reliable.
Authoritative Reference: More reliable and easier to verify, especially for technical standards and important decisions.
# E-Evidence
I checked the HTTP port information using an AI assistant, web search, and the official IANA website. All three showed that HTTP uses port 80.

# V-Verification
I compared the answers from the three methods. The information matched, and the IANA reference confirmed that port 80 is registered for HTTP.

# R-Reflection
This activity helped me understand that different sources can be used for different purposes. AI is useful for quick explanations, web search helps to find more information, and an authoritative source is better when I need to confirm important technical information.

# Q6. What Is an AI Agent?
## A-Answer

Comparison Table:

| Idea                 | Simple Meaning                                                                                     |
| ---------------------| -------------------------------------------------------------------------------------------------- |
| LLM                  | A model that understands and generates text.                                                       |
| LLM Application      | An application that uses an LLM to perform a specific task.                                        |
| RAG System           | A system that gets information from a trusted source and gives it to the LLM to answer.            |
| Tool-Using Assistant | An assistant that can use tools like search, calculator, or APIs.                                  |
| AI Agent             | A system that can understand a goal, plan steps, use tools, and take actions to complete the task. |

Flow Diagram :
                                             User Request
                                                 ↓
                                                LLM
                                                 ↓
                                        Decide What to Do
                                                 ↓
                                              Tool Call
                                                 ↓
                                            Tool Result
                                                 ↓
                                        Decision / Next Step
                                                 ↓
                                           Final Response
Agent vs Simple Chatbot
A simple chatbot mainly responds to the user's message. An AI agent can plan, use tools, make decisions, and take actions to complete a goal.
Simple Example :
A travel-planning AI agent can take a user's travel request, search for flights and hotels, compare the information, create a plan, and give the final travel schedule.
# E-Evidence
I checked the explanation with Google Cloud's information about AI agents, which describes agents as systems that can use reasoning, planning, tools, and actions to complete goals.

# V-Verification
I checked my explanation with Google Cloud's information about AI agents. The main points matched, especially that an agent can plan, use tools, and take actions to complete a goal.

# R-Reflection
This question helped me understand the difference between an LLM and an AI agent. I learned that an LLM mainly generates responses, while an agent can use tools and take steps to complete a task.

# Q7. Where Should Humans Still Make the Decision?
## A-Answer

| Situation                   | Possible Failure                                    | Required Verification                           | Who/What Approves  |
| --------------------------- | --------------------------------------------------- | ----------------------------------------------- | ------------------ |
| **Medical information**     | AI may give incorrect advice.                       | Check with a doctor or trusted medical source.  | Doctor             |
| **Financial decision**      | AI may suggest a wrong or risky decision.           | Check official financial information and facts. | Qualified person   |
| **Legal information**       | AI may misunderstand a law or rule.                 | Check the current law or legal expert.          | Legal professional |
| **Important work report**   | AI may include wrong facts or missing information.  | Check the original data and sources.            | Human reviewer     |
| **Important email/message** | AI may give incorrect or inappropriate information. | Read and check the message before sending.      | Human user         |

Simple Rule:
Use AI to help with the work, but verify important information before making a decision or taking action.
# E-Evidence
I checked the idea of responsible AI use from reliable AI guidance. It supports keeping humans involved when AI outputs can affect important decisions.

# V-Verification
I reviewed each example and considered what could go wrong if the AI answer was accepted without checking. I added a trusted source, original data, or a qualified person as the verification step.

# R-Reflection
This question helped me understand that AI should be used as a helper, not as the final decision-maker. I learned that checking important AI outputs can help avoid mistakes.

# Q8. Find AI Around You
## A-Answer

| System / Feature              | AI/ML Involved? | Task Type          | Evidence / Source                                      |
|-------------------------------|-----------------|--------------------|--------------------------------------------------------|
| Google Maps                   | Yes             | Prediction         | Google says Maps uses AI/ML for traffic prediction.    |
| Gmail Spam Detection          | Yes             | Classification     | Google explains that Gmail uses ML to detect spam.     |
| YouTube Recommendations       | Yes             | Recommendation     | YouTube says its recommendations use ML models.        |
| YouTube Auto Captions         | Yes             | Recognition        | YouTube uses AI to create automatic captions.          |
| Google Photos Face Recognition| Yes             | Recognition        | Google explains that Photos uses ML for face grouping. |

Simple Rule-Based Example
For spam detection, a simple rule could be: “If an email contains certain words, mark it as spam.” This can work for simple cases, but ML can learn patterns from many previous emails.
# E-Evidence
I checked information from Google about these features. Google confirms that AI/ML is used in Maps, Gmail, YouTube, and Google Photos for tasks like prediction, spam detection, recommendations, and recognition.

# V-Verification
I compared the features with information from their official sources. This helped me confirm that these systems use AI/ML and are not just simple rule-based programs.

# R-Reflection
This activity helped me notice how AI is used in everyday applications. I also learned that I should check reliable evidence before assuming that a feature uses AI.

# Q9. Prediction, Classification, and Generation
## A-Answer

| Case  | Example                                     | Type               | Reason                                                 |
| ----- | ------------------------------------------- | ------------------ | ------------------------------------------------------ |
| **A** | Predicting house prices                     | **Prediction**     | It predicts a future price using available data.       |
| **B** | Detecting whether an image has a cat        | **Classification** | It puts the image into a category: cat or not cat.     |
| **C** | Writing an email from an instruction        | **Generation**     | It creates new text based on the instruction.          |
| **D** | Predicting whether a customer will cancel   | **Prediction**     | It predicts what the customer may do in the future.    |
| **E** | Summarizing a research paper                | **Generation**     | It generates a shorter version of the original text.   |
| **F** | Identifying a fraudulent transaction        | **Classification** | It classifies the transaction as fraudulent or normal. |
| **G** | Generating an image from a text description | **Generation**     | It creates a new image from the given description.     |
| **H** | Predicting the next word/token              | **Prediction**     | It predicts which token is likely to come next.        |

Why is next-token prediction important?
Modern language models generate text one token at a time by predicting what should come next. By repeating this process, the model can produce emails, summaries, code, and answers to questions. So, many different language tasks are built on the same basic idea of next-token prediction.
# E-Evidence
I checked the concepts using reliable educational sources about machine learning and language models. They explain prediction, classification, and generation as different types of AI tasks, and that language models generate text by predicting tokens.

# V-Verification
I compared my classifications with these sources. The examples matched the main ideas of prediction, classification, and generation.

# R-Reflection
This question helped me understand the difference between these three task types. I also learned that next-token prediction is the basic process behind many language-model tasks like writing, summarizing, and answering questions.

# Q10. Design Your Personal AI Verification Protocol
## A-Answer
7-Step Procedure:
1. Define the problem
First, I clearly understand what I need from the AI.
Why: Avoids solving the wrong problem.
2. Check the AI output
I read the answer carefully and understand what it is saying.
Why: Helps me notice unclear or missing information.
3. Inspect the assumptions
I check what assumptions the AI has made.
Why: Wrong assumptions can lead to a wrong answer.
4. Check the evidence and sources
I check important facts using reliable sources.
Why: Helps catch unsupported or false information.
5. Test the result
I test the answer with examples, calculations, or other available methods.
Why: Helps find mistakes in the output.
6. Compare and review
I compare the result with the original problem and check whether it makes sense.
Why: Helps find errors that may not be obvious.
7. Accept, reject, or revise
Finally, I decide whether to accept the answer, reject it, or ask AI to revise it.
Why: Makes sure I do not use an incorrect result.
Simple Example
Suppose I ask AI to calculate the total cost of five products.
I clearly give the product prices and quantities.
I check the calculation given by AI.
I check whether AI made any assumptions about quantity or price.
I verify the prices from the original information.
I calculate the total separately using a calculator.
I compare both results.
If they match, I accept the result; if not, I revise or check the answer again.
Simple rule: Use AI to help me, but verify the result before I depend on it.
# E-Evidence
I checked my verification steps with general responsible AI guidance. It supports checking the problem, assumptions, evidence, and results before using AI-generated information.

# V-Verification
I reviewed my 7 steps and made sure they include defining the problem, checking assumptions, verifying sources, testing the result, and making a final decision.

# R-Reflection
This question helped me create a simple process for using AI safely in engineering work. I learned that I should not directly accept an AI answer without checking it. I can use AI as a helper while keeping the final decision with myself.
