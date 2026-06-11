# 🎓 Agentic Mentoring Follow-up and Parent Communication Assistant

An AI-powered mentoring assistant built using Langflow that helps academic mentors identify students requiring immediate attention, generate professional parent communication messages, maintain interaction history, and schedule follow-up actions.

## 📌 Overview
Managing student mentoring activities manually can be time-consuming and prone to delays. This project leverages Agentic AI to automate the mentoring workflow by analyzing student data and assisting mentors in making informed decisions. The system evaluates academic indicators such as attendance, internal assessment scores, and backlogs to identify at-risk students and recommend appropriate interventions.

## ✨ Features
- 📊 Student performance analysis
- ⚠️ Risk level identification (High / Medium / Low)
- 👨‍👩‍👧 Parent communication generation
- 📝 Mentor recommendations
- 🔄 Follow-up planning
- 🧠 Conversation and interaction history
- 📂 Student record processing through file input
- 🤖 Agentic decision-making using Langflow agents

## 🛠️ Tech Stack
- Agent Workflow: Langflow
- Language Model: OpenRouter
- Memory: Message History
- Input: Chat Input, Read File
- Output: Chat Output
- Prompting: Prompt Templates
- AI Architecture: Agentic AI

## 🏗️ System Architecture
Chat Input → Prompt Template → OpenRouter → Agent → (Message History + Read File) → Chat Output

## ⚙️ Workflow
1. Mentor provides student details.
2. The agent analyzes attendance, IA marks, backlogs, and previous mentoring interactions.
3. The system determines the student's risk level.
4. Parent communication requirements are identified.
5. A professional parent message is generated.
6. Mentor recommendations are provided.
7. Follow-up actions are scheduled.

## 📥 Sample Input
Student Name: Rahul Sharma  
USN: 4MH23CA001  
Semester: 4  
Attendance: 62%  
IA1 Marks: 18  
IA2 Marks: 20  
Backlogs: 2  
Previous Parent Meeting: No  
Mentor Notes: The student has been absent frequently and academic performance has declined.  
Task: Analyze the student's academic status and generate a mentoring report.

## 📤 Sample Output
Risk Level: HIGH  
Reason: Low attendance and declining academic performance.  
Parent Contact Required: YES  

Parent Message:  
Dear Parent,  
Your ward requires additional academic support due to low attendance and IA performance. We request your cooperation in encouraging regular attendance and focused preparation.

Mentor Recommendation: Weekly mentoring sessions and progress monitoring.  

Follow-up Date: Within the next 7 days.

## 📂 Langflow Components Used
- Chat Input
- Prompt Template
- OpenRouter
- Agent
- Message History
- Read File
- Chat Output

## 📈 Future Enhancements
- Email integration for automatic parent communication
- SMS notifications
- Dashboard for mentors
- Integration with college ERP systems
- Predictive analytics for early intervention
- Mobile application support

## 🎯 Use Cases
- Academic mentoring programs
- College departments
- Universities
- Student welfare committees
- Educational institutions

## 📚 Project Objectives
- Automate mentoring workflows
- Reduce manual effort
- Improve parent communication
- Enable early identification of at-risk students
- Maintain mentoring records and follow-up plans

## 🤝 Contributors
- Ashwini Vishal

## 📄 License
This project is intended for academic and educational purposes. Feel free to modify and extend it for learning and research.

⭐ If you found this project useful, consider giving it a star!
