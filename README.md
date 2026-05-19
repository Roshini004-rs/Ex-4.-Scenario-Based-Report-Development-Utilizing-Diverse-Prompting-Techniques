# Ex-4: Scenario-Based Report Development Using Diverse Prompting Techniques  

## Objective  
The objective of this experiment is to design and develop an AI-powered chatbot for a retail environment that can handle customer queries, provide efficient support, and improve overall customer experience. Various prompting techniques are used to guide chatbot behavior, data collection, response evaluation, and report generation.

---

## Aim  
To design, implement, and evaluate a retail chatbot using different prompting strategies in order to analyze how effectively it handles customer inquiries, improves support efficiency, and enhances user satisfaction.

---

## Algorithm  

1. **Identify Use Case**  
   Select key retail customer support scenarios such as product inquiries, return/refund requests, order tracking, and troubleshooting.

2. **Define Prompting Techniques**  
   Identify prompting approaches including zero-shot, one-shot, few-shot, role-based, instruction-based, contextual, persona-driven, and chain-of-thought prompting.

3. **Design Prompts**  
   Create uniform customer queries and apply different prompting techniques to each scenario.

4. **Execute Prompts**  
   Run prompts across multiple AI platforms such as ChatGPT, Claude, Gemini, etc.

5. **Collect Outputs**  
   Record chatbot responses for each scenario and prompting method.

6. **Analyze Responses**  
   Evaluate responses based on clarity, accuracy, empathy, personalization, and usefulness.

7. **Document Results**  
   Present results in a structured format with comparisons.

8. **Conclusion**  
   Identify which prompting techniques provide the best customer interaction.

---

## Prompt Design  

### Scenario 1: Product Inquiry  

1. **Zero-shot Prompting**  
   Do you have wireless headphones available?

2. **One-shot Prompting**  
   How can I cancel an order?

3. **Few-shot Prompting**  
   Do you offer warranty on electronics? How long does delivery usually take?

4. **Role-based Prompting**  
   You are a professional retail customer support agent. A customer asks about wireless headphones—respond politely and clearly.

5. **Instruction-based Prompting**  
   Provide a short and clear answer about the availability of wireless headphones.

---

### Scenario 2: Return and Refund  

1. **Zero-shot Prompting**  
   What is your return policy?

2. **One-shot Prompting**  
   How can I cancel an order?

3. **Few-shot Prompting**  
   Do you offer warranty on electronics? How long does delivery usually take?

4. **Role-based Prompting**  
   You are a retail support agent. Explain the return policy clearly and politely.

5. **Instruction-based Prompting**  
   Explain the return policy in 2–3 simple sentences.

---

### Scenario 3: Order Tracking  

1. **Zero-shot Prompting**  
   Where is my order #12345?

2. **One-shot Prompting**  
   How can I cancel an order?

3. **Few-shot Prompting**  
   Do you offer warranty on electronics? How long does delivery usually take?

4. **Role-based Prompting**  
   You are a retail support agent. A customer asks about their order status—respond clearly.

5. **Instruction-based Prompting**  
   Provide the order status in 2–3 short sentences.

---

### Scenario 4: Troubleshooting  

1. **Zero-shot Prompting**  
   My blender is not working. What should I do?

2. **One-shot Prompting**  
   How can I cancel an order?

3. **Few-shot Prompting**  
   Do you offer warranty on electronics? How long does delivery usually take?

4. **Role-based Prompting**  
   You are a retail support agent. Help a customer troubleshoot a faulty blender.

5. **Instruction-based Prompting**  
   Give 2–3 simple steps to fix the issue.

---

## Output (Sample Responses)  

### Scenario 1: Product Inquiry  

- **Zero-shot:**  
  Yes, wireless headphones are available in different models and price ranges. I can help you choose one.

- **One-shot:**  
  You can cancel an order within 24 hours through the “My Orders” section.

- **Few-shot:**  
  Electronics have a 1-year warranty and delivery takes 3–5 days. Wireless headphones are available.

- **Role-based:**  
  We currently have several wireless headphone options available. I can help you select the best one.

- **Instruction-based:**  
  Yes, wireless headphones are available in multiple models.

---

### Scenario 2: Return and Refund  

- **Zero-shot:**  
  Items can be returned within 30 days if unused.

- **One-shot:**  
  Orders can be canceled within 24 hours.

- **Few-shot:**  
  Returns are accepted within 30 days. Products include warranty.

- **Role-based:**  
  You can return items within 30 days if unused and in original condition.

- **Instruction-based:**  
  Returns are accepted within 30 days with original packaging.

---

### Scenario 3: Order Tracking  

- **Zero-shot:**  
  Your order is in transit.

- **One-shot:**  
  Orders can be canceled within 24 hours.

- **Few-shot:**  
  Shipping takes 3–5 days. You can track your order online.

- **Role-based:**  
  Your order has been shipped and is on the way. Track it online.

- **Instruction-based:**  
  Your order is on the way. Track it using your order ID.

---

### Scenario 4: Troubleshooting  

- **Zero-shot:**  
  Check if the blender is plugged in.

- **One-shot:**  
  Orders can be canceled within 24 hours.

- **Few-shot:**  
  Try resetting the blender or check warranty.

- **Role-based:**  
  Please check the power connection and ensure parts are assembled correctly.

- **Instruction-based:**  
  Check power, fix parts, contact support if needed.

---

## Comparative Analysis  
<img width="1660" height="677" alt="image" src="https://github.com/user-attachments/assets/7dd33377-e559-4273-80ba-c761184823e6" />


| Scenario | Technique | Inquiry Handling | Efficiency | Customer Experience |
|----------|----------|----------------|-----------|------------------|
| Product Inquiry | Zero-shot | Basic | Fast | Low |
| | One-shot | Clear | Efficient | Moderate |
| | Few-shot | Detailed | Moderate | High |
| | Role-based | Professional | High | Excellent |
| | Instruction-based | Simple | Very High | Good |
| Return/Refund | Zero-shot | Basic | Fast | Average |
| | One-shot | Clear | Efficient | Good |
| | Few-shot | Detailed | Moderate | High |
| | Role-based | Structured | High | Excellent |
| | Instruction-based | Simple | Very High | Good |
| Order Tracking | Zero-shot | Basic | Fast | Average |
| | One-shot | Clear | Efficient | Good |
| | Few-shot | Detailed | Moderate | Good |
| | Role-based | Structured | High | Excellent |
| | Instruction-based | Simple | Very High | Good |
| Troubleshooting | Zero-shot | Basic | Fast | Average |
| | One-shot | Structured | Efficient | Good |
| | Few-shot | Context-rich | Moderate | High |
| | Role-based | Empathetic | High | Excellent |
| | Instruction-based | Simple | Very High | Good |

---

## Result  

Role-based prompting provides the best customer experience due to professionalism and empathy.  
Instruction-based prompting is the most efficient for quick responses.  
Few-shot prompting gives detailed outputs but is less efficient.  
Zero-shot and one-shot prompting are faster but less personalized.

---
