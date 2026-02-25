Duolingo Database Architecture & ERD

Product architecture and relational database design for a Duolingo-style learning platform
This project presents a complete relational schema and product architecture design for a language learning platform inspired by Duolingo.
It models how a real learning platform manages:

Users
Learning content
Progress tracking
Gamification systems
Social connections
The project demonstrates real-world scalable database design principles.

Project Goal

The goal of this project was to design a scalable relational database architecture for a modern language learning platform.
The schema supports structured learning, engagement tracking, and user interaction systems.
This project shows how large learning platforms organize data efficiently. 

Product Architecture
The database design models the core components of a modern language learning platform.
Core Learning System

Structured learning hierarchy:
Course → Unit → Lesson → Exercise
This modular structure allows courses to expand without affecting user progress. 


User Learning Data
Tracks learner behavior and progress.

Includes:

• Lesson completion
• Exercise attempts
• Scores
• Learning history

This enables analytics and personalized learning. 

Gamification System
Models user engagement features:

• XP tracking
• Streak tracking
• Hearts system
• Gems currency

Gamification data is separated from core user data for scalability. 


Social System
Models user-to-user interactions.

Includes:

• Friend connections
• Social relationships

Stored separately to maintain normalized data structure. 


Leaderboard System
Supports competitive learning features.

Includes:

• Weekly leaderboards
• User rankings
• XP comparisons

Designed for time-based competition tracking. 


Database Entities
Major entities include:

• Users
• Courses
• Units
• Lessons
• Exercises
• UserLessonProgress
• UserExerciseAttempt
• UserXP
• UserStreak
• UserHearts
• UserGems
• Leaderboard
• LeaderboardEntry
• Friends

These entities model both learning behavior and engagement systems. 


Entity Relationship Diagram:
The ER diagram shows relationships between users, learning content, engagement systems, and social features.
It illustrates how data flows across the platform and supports platform functionality. 

See the PDF for the complete diagram.

Key Design Decisions

Separation of Learning and Engagement Data

Learning data and gamification data are stored separately.

This improves scalability and performance. 



Modular Content Structure
Course → Unit → Lesson → Exercise hierarchy allows flexible content updates. 

Scalable Progress Tracking
User progress is stored independently.

This enables:

Performance analytics
Adaptive learning
Personalized practice 

Files
Check Duoling_ERD_Prankur_Thakur_V3.pdf for
Full architecture documentation and ER diagram.

Skills Demonstrated

• Relational database design
• Entity Relationship Modeling
• Product architecture thinking
• Schema planning
• Data normalization
• System design

What This Project Shows

This project demonstrates the ability to:

• Analyze a real product
• Translate product features into data models
• Design scalable schemas
• Structure complex systems

Author
Prankur Thakur
AI and data learner focused on building structured and human-centered systems.
