# Exno.7-Prompt-Engineering
# Date:
# Register no: 212222040130
# Aim: 
To Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.



# Algorithm: 
Develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.
# Output :
```

Name: S.Ramya				Reg.No:212222040130
Dept: B.E.CSE
Content-Aware Prompt Writing for Intelligent Productivity Applications.

Ex No.7 – Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

Aim:
To develop a prompt-based application using ChatGPT – To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced content-aware prompt designs and their corresponding outputs.

AI Tools Required:
ChatGPT

Explanation:
Prompt:
"Design a content-aware personal productivity assistant that helps manage daily tasks, schedule events, provide wellness suggestions, and adapt its behavior based on the type and urgency of the user’s inputs. The assistant must respond in natural language and intelligently detect contextual priorities within the prompts."
Content-aware prompt writing refers to the design of prompts that take into account the context, urgency, type of task, and user preferences embedded in natural language. By using this technique with large language models like ChatGPT, users can interact with the assistant in a more intuitive, human-like manner. For example, the model can differentiate between a health-related task and a work-related one or detect whether something is urgent or flexible.

Procedure:
Define the core requirements of a content-aware productivity assistant.
Should handle varied types of inputs (tasks, events, reminders, wellness tips).
Must detect content types like deadlines, activities, self-care routines.
Should prioritize based on time sensitivity and category.
Design prompts to demonstrate context-aware interactions.
Prompt 1: "Remind me to call my professor before 2 PM."
Prompt 2: "Suggest something healthy to eat if I’m feeling tired."
Prompt 3: "Set a casual chat with team around lunchtime."
Implement prompt-to-output mapping using LLM.
Analyze the user prompt.
Classify content (work, health, general query).
Respond appropriately with action or suggestion.
Simulate natural user interaction using a command-line interface.
User inputs prompt in casual tone.
Assistant interprets and executes based on detected context.
Adapt responses based on simulated user preferences and content priorities.
Add memory of timing preference (e.g., "I prefer work reminders in the morning").
Modify tips and reminders based on mood or repeated choices.

Expected Output:
Personal Productivity Assistant Features:
Daily Task Manager
Accepts tasks like: “Remind me to pay the bill before 3 PM”
Detects urgency and sets early reminders if high priority.
Groups tasks by category (e.g., finance, communication, wellness).
Smart Scheduler
Schedules events with vague terms: “Plan lunch with Kiran tomorrow”
Checks for conflicts and offers suggestions.
Detects social vs. professional meetings.
Wellness Tips Generator
Suggests health tips based on mood: “I feel drained” → “Take a short walk and drink water.”
Avoids repetition by tracking past tips.

Adaptive Preference Memory
Learns habits: prefers exercise reminders at 6 AM, avoids late-night notifications.
Categorizes tasks and wellness activities separately for better balance.

Design: Content-Aware Personal Productivity Assistant (LLM-Powered)

1. Core Requirements
Natural Language Understanding: Ability to understand casual speech with embedded context.
Context Detection: Identifies category (work, health, general) and urgency.
Task Management: Accept, update, delete, and categorize tasks.
Reminder Scheduling: Detects and responds to time-related cues.
Wellness Guidance: Provides adaptive tips based on emotional/mood input.
Preference Learning: Remembers and adapts based on interaction history.

2. Prompts for Each Feature
Feature	Example User Prompt	LLM Action Prompt
Task Manager	"Remind me to submit the report by 4 PM."	Extract task, deadline, and categorize as “work”; set a timely reminder.
Task Summary	"Do I have anything urgent today?"	Prioritize today’s tasks and display those marked “high urgency.”
Smart Scheduler	"Plan a call with Akash post-lunch tomorrow."	Schedule call, infer “post-lunch” as ~2 PM; check calendar for conflicts.
Wellness Suggestion	"I feel mentally tired."	Suggest rest tip (e.g., meditation, short nap, hydration).
Recurring Reminder	"Remind me to stretch every hour while working."	Set recurring reminders with “wellness” tag; adjust if time range specified.
Adaptive Memory	"I prefer no notifications after 9 PM."	Store preference and restrict future reminders post 9 PM.

3. Simulated Interface (Command-Line Interaction)
User: Remind me to review the budget file by 10 AM.
Assistant: Sure. I’ve added a reminder to review the budget file at 10 AM. It’s categorized under “Finance – High Priority”.
User: What do I have today?
Assistant: Today’s tasks include:
Review budget file at 10 AM
Lunch with Akash at 2 PM
Would you like to reschedule or add anything?
User: I feel anxious.
Assistant: Consider doing a short breathing exercise or going for a 5-minute walk. Would you like a reminder?
User: Don’t notify me after 9 PM.
Assistant: Got it. No alerts or reminders will be sent after 9 PM.

4. Feedback & Adaptation Example
User: Can you stop suggesting walking every time I say I'm tired?
Assistant: Noted. I’ll avoid repeating walking as a tip and suggest alternative wellness activities in future.

5. Simulated Memory (Preference Storage)
Preference Saved: “Avoid repeated wellness tips”
Preference Saved: “No reminders after 9 PM”

Example:
User: Remind me to take a break.
Assistant: Scheduled your break at 11:30 AM. I’ve set it as a quiet notification to avoid disturbance.
User: I’m tired.
Assistant: Instead of walking, how about trying a 5-minute mindfulness audio session?

Expected Output (LLM Response Simulation)
Content-Aware Personal Assistant Features:

Daily Task Manager
Understands varied user inputs with embedded deadlines.
Tags tasks by urgency and topic (e.g., work, finance, personal).
Sorts tasks by priority and delivers brief summaries.

Smart Scheduler
Uses natural cues like “after dinner,” “post-lunch” to assign times.
Detects conflicts and reschedules or suggests alternatives.
Wellness Tips Generator
Offers mood-based wellness suggestions.
Avoids repetitive tips using feedback and logs.

Adaptive Preference Learning
Learns preferred reminder timings, task types, and wellness routines.
Customizes interaction style and timing per user history.

Result:
The lab exercise resulted in the creation of a content-aware prototype assistant powered by ChatGPT. Students were able to:
Understand how content-aware prompts enhance LLM outputs.
Apply prompt writing techniques based on context, intent, and urgency.
Simulate intelligent interaction using natural language prompts.
Explore adaptive memory and feedback-driven interaction design.
Gain insight into real-world applications of LLMs for productivity and well-being.


```

# Result: 

The Prompt is executed successfully.


