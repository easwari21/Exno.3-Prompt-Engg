# Ex. No. 3 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques  

**Date: 09.09.2025**  
**Register Number: 212223240033**  

---

## Aim  
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone.  

In this experiment, different prompting strategies are employed, ranging from **basic task-oriented prompts** to **complex persona-driven prompts**, to guide the chatbot’s responses.  

---

## Algorithm  

### 1. Direct Instruction Prompts  
- **Objective:** Provide concise responses to customer inquiries.  
- **Prompt Pattern:**  
  *“When a customer asks for the status of their order, reply with: ‘Your order is currently being processed and will be delivered by [date].’”*  

---

### 2. Contextual Prompting  
- **Objective:** Incorporate prior context to give detailed answers based on user’s previous interaction.  
- **Prompt Pattern:**  
  *“If the customer previously mentioned that they haven’t received their order, say: ‘I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.’”*  

---

### 3. Persona-Based Prompting  
- **Objective:** Design the chatbot to adopt a persona for engaging interactions.  
- **Prompt Pattern:**  
  *“Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as: ‘Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!’”*  

---

### 4. Few-Shot Prompting  
- **Objective:** Teach the chatbot to generalize from examples.  
- **Prompt Pattern:**  
  *“Here are some examples of how to handle technical questions:  
  - ‘My phone isn’t charging.’ → ‘Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.’  
  - ‘The screen is flickering.’ → ‘It sounds like a display issue. Have you tried restarting the device?’  
  Now, respond to: ‘My app keeps crashing.’”*  

---

### 5. Chain-of-Thought Prompting  
- **Objective:** Use step-by-step reasoning for complex troubleshooting.  
- **Prompt Pattern:**  
  *“When a customer reports their laptop overheating, guide them through these steps:  
  - Ask if they are using the laptop on a soft surface.  
  - Suggest moving the laptop to a flat, hard surface for better airflow.  
  - Ask if they’ve cleaned the vents recently.  
  - Recommend restarting the device to see if the issue persists.  
  Now, solve: ‘My laptop fan is making a loud noise.’”*  

---

### 6. Instruction with Constraints  
- **Objective:** Provide assistance under specific conditions (e.g., word count, tone).  
- **Prompt Pattern:**  
  *“Respond to order inquiries in no more than 50 words and avoid technical jargon. Example: ‘Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.’”*  

---

### 7. Reflective Prompting  
- **Objective:** Reduce misunderstandings by reflecting the user’s query back before answering.  
- **Prompt Pattern:**  
  *“When a customer asks for help, first reflect their question back to them. For example, if they ask: ‘How can I reset my password?’ respond with: ‘You’re asking how to reset your password, correct? Here’s how you can do it.’”*  

---

## Result  
The various types of prompts were executed successfully, and the chatbot responded appropriately according to each prompting strategy.  

---

## Conclusion  
Thus, the prompts were executed successfully. By applying **direct, contextual, persona-based, few-shot, chain-of-thought, constrained, and reflective prompting**, the chatbot demonstrated flexibility in handling diverse customer service scenarios with improved clarity, engagement, and efficiency.  
