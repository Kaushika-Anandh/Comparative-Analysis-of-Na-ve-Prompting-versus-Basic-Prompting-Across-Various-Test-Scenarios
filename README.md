# Comparative-Analysis-of-Naive-Prompting-versus-Basic-Prompting-Across-Various-Test-Scenarios
Done by : Kaushika A<br>
Reg no : 212221230048


## **Aim**  
To test how ChatGPT responds to naïve prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios, analyzing the quality, accuracy, and depth of the generated responses.

---

## **Procedure**

### **Defining the Prompt Types**  

#### **Naïve Prompt**  
A naive prompt is a simple and straightforward instruction to an AI system that does not consider optimization or clarity.  
- It often lacks specificity, context, or structure, which can result in vague, incomplete, or suboptimal responses.

#### **Basic Prompt**  
A basic prompt is slightly more structured and clear than a naive prompt but still simple.  
- It provides enough detail to guide the AI toward a more relevant response but may not fully leverage advanced prompt engineering techniques.  

##### **Types of Basic Prompting**  
1. **Persona Prompt**  
   A prompt that assigns a specific role or identity to the AI to guide its behavior and tone.  
   
2. **Zero-Shot Prompt**  
   A prompt where the AI is asked to perform a task without any prior examples or context, relying entirely on its pre-trained knowledge.  

3. **Few-Shot Prompt**  
   A prompt that provides a few examples to guide the AI in performing a task, improving its understanding and response accuracy.

---

## **Test Case Scenarios**

### **Scenario 1: Explaining a Topic**

#### **Naïve Prompt:**  
`Explain climate change`

**Result:**  
> **What is Climate Change?**  
> Climate change refers to long-term alterations in temperature, precipitation, wind patterns, and other elements of Earth's climate system. These changes can be natural, caused by factors like volcanic eruptions or variations in solar radiation, but in recent decades, human activities have become the dominant cause, primarily due to the burning of fossil fuels like coal, oil, and gas.  
> **[Additional details provided in response include...]**
> - Greenhouse gas emissions trapping heat in the atmosphere.
> - Rising global temperatures leading to extreme weather events like hurricanes, droughts, and heatwaves.
> - Melting polar ice caps causing sea levels to rise.
> - Significant impact on ecosystems, biodiversity, and human communities.

---

#### **Basic Prompt (Zero-Shot):**  
`Explain climate change in simple terms, including its causes and effects.`  

**Result:**  
> **What is Climate Change?**  
> Climate change means the Earth's weather is changing over a long time. It's getting hotter, and this causes problems for nature and people. While the Earth's climate has always changed, it's now happening faster because of human activities.  
> - **Causes:** Burning fuels like coal and gas releases gases into the air that trap heat. Cutting down trees also makes it worse.  
> - **Effects:** Hotter weather, stronger storms, more droughts, and rising seas. Animals lose their homes, and farming gets harder.  
> - **What can we do?** Use clean energy like wind and solar power, plant more trees, and waste less energy.  

---

### **Scenario 2: Providing Recommendations**

#### **Naïve Prompt:**  
`What is the best way to get fit?`  

**Result:**  
> The best way to get fit depends on your current fitness level, goals, and lifestyle.  
> - Start with regular physical activities like walking, running, or cycling.  
> - Incorporate strength training exercises such as lifting weights or bodyweight exercises like push-ups.  
> - Eat a balanced diet rich in fruits, vegetables, proteins, and healthy fats.  
> - Stay consistent with your routine and give your body time to rest and recover.  

---

#### **Basic Prompt (Persona Prompt):**  
`As a fitness expert, suggest me what is the best way to get fit for a woman student in tech.`  

**Result:**  
> **As a woman in tech, you likely have a busy and often sedentary lifestyle due to long hours of sitting, coding, and studying.**  
> - **Routine:** Dedicate 20–30 minutes daily to light workouts such as yoga or pilates to improve flexibility and reduce stiffness.  
> - **Strength Training:** Incorporate exercises like squats, lunges, and planks to build core strength and improve posture.  
> - **Cardio:** Go for brisk walks or cycling 3–4 times a week to boost cardiovascular health.  
> - **Stretching:** Regular stretching to avoid repetitive strain injuries from typing or sitting for extended periods.  
> - **Diet Tips:** Focus on whole grains, lean proteins, and plenty of vegetables while staying hydrated.  
> - **Mindset:** Use apps or reminders to stay consistent, even on hectic days.

---

### **Scenario 3: Summarizing an Article/Text**

#### **Naïve Prompt:**  
`Summarize the following article: https://www.ijraset.com/research-paper/women-safety-device-with-gps-tracking-and-alerts`

**Result:**  
> The article discusses a women’s safety device designed to provide enhanced security by integrating GPS tracking, alerts, and self-defense mechanisms.  
> - It outlines the system's architecture, including sensors and communication modules.  
> - Describes real-time alert functionality and its impact on improving women’s safety.  
> - **[Further improvements suggested...]**

---

#### **Basic Prompt (Few-Shot):**  
`Provide the literature summary for the following article: https://www.ijraset.com/research-paper/women-safety-device-with-gps-tracking-and-alerts`

**Result:**  
> **Paper Title:** Women Safety Device with GPS Tracking and Alerts  
> **Problem Statement:** Women face increased risks of physical assault and other safety issues. In critical situations, they often struggle to contact emergency services quickly and discreetly.  
> **Approach:**  
> - The proposed device uses GPS for real-time tracking and sends alerts to predefined contacts.  
> - Includes a panic button to activate the alert mechanism immediately.  
> - Self-defense tools, like electric shock modules, are integrated into the device.  
> **Advantages:** Enhances women’s safety through a compact, wearable, and easy-to-use solution.  
> **Drawbacks:** Limited battery life and potential connectivity issues.  
> **Future Scope:** Development of AI-based predictive algorithms to detect and prevent threats in advance.  

---

## **Evaluation of Responses**

### **Quality:**  
- **Basic prompts** have better quality answers compared to naive prompt responses due to their structured and tailored prompt style, allowing the model to gather the information it needs before providing the response.

### **Accuracy:**  
- **Basic prompts** tend to have better accuracy in providing the right information compared to naive prompting, as they include more context to fine-tune the response.

### **Depth:**  
- **Naïve Prompt:** Descriptive but on a general scale.  
  - The model tries to infer all possible questions the prompter may want to know but did not mention.  
- **Basic Prompt:** More in-depth and tailored responses.  
  - Focused delivery of answers, meeting specific requirements.

---

## **Conclusion**  
Using basic prompts, including persona, zero-shot, and few-shot methods, significantly improves the quality, accuracy, and depth of ChatGPT responses compared to naïve prompts. These techniques leverage structured queries to guide the AI effectively, providing precise and context-aware outputs.
