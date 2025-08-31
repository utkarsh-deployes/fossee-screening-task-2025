# FOSSEE Python Screening Task 2 – AI Debugging Assistant 

The designed prompt is available in (./PROMPT.md). 
---

## Reasoning Behind the Design 

### 1. Tone and Style
I deliberately chose a **supportive, tutoring-like tone**. Research in education shows that learners engage better when feedback is encouraging rather than judgmental. The assistant is asked to act as a "guide on the side" not a "sage on the stage" or a strict traditional tutor. This ensures that students feel motivated to explore solutions independently. 

### 2. Balancing Bugs vs Guidance
The AI should identify **possible problem areas** but stop short of giving away the fix. Instead of spoon-feeding solutions, it asks **guiding questions** (as “What value do you expect this variable to hold at this point?”). This shows how good human tutors scaffold learning, fostering **critical thinking and debugging habits**.  

### 3. Adaptation for Different Learners
The prompt explicitly includes **dual-layer adaptability**:
- **Beginners** → receive simple, step-by-step explanations, analogies, and encouragement.  
- **Advanced learners** → get deeper hints around efficiency, structure, and best practices.  
This flexibility ensures the same prompt can work across diverse learners. 

--- 

## Research Foundation 
This design is grounded in established **prompt engineering frameworks (2022–2025):**
- **Clarity & specificity** → Strong prompts clearly define role, task, and constraints (OpenAI, 2023)
- **Role prompting** → Assigning the AI the persona of a “Debugging Assistant” improves alignment and consistency (Anthropic, 2024).   
- **Step-by-step reasoning** → Inspired by *Chain-of-Thought prompting* the assistant guides learners through logic rather than answers.
- **Scaffolded hints** → Borrowed from educational scaffolding theories, the assistant provides **progressive hints** instead of full solutions.  
- **Framework inspiration** → Elements of the **o1 Anatomy (Brockman, 2025)** and **Microsoft GCES (2024)** frameworks shaped the structured format (role → task → constraints → guidance). 
 
For a detailed discussion of these frameworks, see (./ResearchBackup_FOSSEE.pdf), which I authored as supporting research for this task & every submission & prompt is based on that research snippet authored by me, by taking references from various internet sources. 

---  

## Conclusion 
This prompt is **student-centered**: it guides without revealing answers, adapts to skill levels, and builds problem-solving capacity.  
By blending educational principles with prompt-engineering best practices, it ensures the AI acts as a **true debugging mentor** not as a direct answer tool, cause we want kids to have develop that thinking ability, we don't want them to just mug up the answers or approach to particular questions. 
