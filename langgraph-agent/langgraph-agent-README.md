# LangGraph Agent – Emotion-Aware Conversational Assistant

This project uses **LangGraph** to build a branching chatbot that routes user queries to different responses based on emotional tone.

---

## 📌 Use Case

**Scenario:** A user interacts with a chatbot. Based on the message, the agent decides whether to:
- Respond with empathy (therapist style), or
- Respond with logic (analytical style)

---

## 🧠 Agent Flow Architecture

1. **Start Node:** Takes user input
2. **Classifier Node:** Determines if the query is emotional or logical
3. **Router Node:** Routes to Therapist Agent or Logic Agent
4. **Therapist Node:** Empathetic response (e.g., "I feel sad")
5. **Logic Node:** Factual answer (e.g., "Top 5 cars in 2024")
6. **End Node:** Conversation ends when user types "exit"

---

## 🔧 Technologies Used

- LangGraph
- LangChain
- OpenAI (GPT-3.5 via DC Connect)
- Python 3.10

---

## 📂 Files

- `main.py`: Full flow definition and execution
- `nodes.py`: All node logic (start, classify, route, respond)
- `chatbot_config.py`: Constants and helpers

---

## 🧪 Test Run

Example 1:
> **Input:** I feel sad.  
> **Output (Therapist):** I'm really sorry to hear that. Can you tell me more?

Example 2:
> **Input:** What are the top cars in 2024?  
> **Output (Logic):** Based on recent reviews, top cars include…

---

## 📸 Demo (screenshot)

<p align="center"><img src="assets/langGraph.PNG" width="1920"/></p>

