LearnMate – AI Coach for Personalized Course Pathways
“Your LearnMate buddy that maps your perfect learning path—personalized, adaptive, and effortless!”

🧠 Project Overview
 Students often struggle to identify the right learning path that aligns with their interests 
and long-term goals due to the overwhelming number of online courses and a lack of personalized 
guidance. LearnMate aims to solve this by acting as an Agentic AI coach that interacts with students, 
understands their interests (like Frontend Development, Cybersecurity, UI/UX Design, etc.), assesses their 
current skill level, and dynamically builds a personalized course roadmap that adapts over time based on 
progress and preferences. 
🚀 Features
🧑‍🏫 Personalized Learning Paths
Dynamically creates a week-by-week roadmap tailored to the user's interest, time availability, and learning goal (e.g., job-ready, certification, or project-based).

📊 Skill-Based Assessment
Gathers user input on current experience level and preferred learning style through friendly conversations.

🧩 Interactive Quizzes & Tasks
Generates short quizzes and coding tasks after each module, with hints, explanations, and auto-feedback.

💬 Conversational Agent Behavior
Built with a growth mindset tone. Supports, guides, and motivates users throughout their journey.

🔁 Real-Time Adaptation
Adjusts difficulty, content, and pacing based on learner feedback and progress.

🛠️ Tech Stack
AI Model: IBM Granite 8B Instruct (ibm/granite-3-3-8b-instruct)

Platform: IBM Watsonx / IBM Cloud Lite

Architecture: LangGraph + React

Language Support: Python, JavaScript, HTML/CSS, SQL (for code tasks)

🧩 Functional Capabilities
Capability	Description
✏️ Quiz Generation	Auto-generates topic-based MCQs and T/F quizzes with answer explanations
💻 Coding Exercises	Practice problems with starter code, edge case handling, and debug tips
🚨 Error Detection	Identifies syntax/runtime/logic errors and provides resolution guidance
🔄 Personalized Updates	Adjusts roadmap based on user feedback on difficulty or interest changes
🧠 Adaptive Tone	Encouraging, non-judgmental language tailored to user’s experience level

👥 Example Prompts for Users
“Can you help me choose the right course for Frontend Development?”

“I’m a beginner in UI/UX. Where should I start?”

“I only have 5 hours a week—what should I focus on?”

📦 Files in This Repository
File	Description
project.json	Metadata and configuration for LearnMate project
wx_agent.json	Agent settings and architecture details
wx_prompt.json	Prompt template structure for agent interactions
wx_agent.65aed5e9.json	Core behavior and detailed instructions for the LearnMate agent
# Technology 
Use of IBM Cloud Lite services / IBM Granite

# Run local development server 
👩‍💻 Developed By
Anjali Pathak
BCA Student | AI & Cloud Intern | IBM Watsonx Developer
📧 anjalipathak879@gmail.com

📄 License
This project is licensed under the MIT License.
