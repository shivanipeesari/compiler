# Smart Supportive Compiler  
MERN Stack Based Project

Description
A supportive version of a traditional compiler that tracks user mistakes and helps debug code intelligently. It features two types of tracking:
- User-Specific Tracking: Records syntax, compilation, and logical errors made by individual users.
- Global Tracking:Monitors and analyzes frequent mistakes across all users to improve overall system feedback.

The system compares the expected output (defined by users) with the actual output generated after running their code. If discrepancies are found,
the system identifies the mistakes and provides actionable suggestions. AI integration further enhances the system by offering dynamic logical error
detection and correction hints.

Features
- Code submission with a user-defined problem statement and expected output.
- Syntax error detection and personalized mistake tracking.
- Logical error detection by comparing outputs.
- AI-driven suggestions for logical improvements.
- Secure code execution through sandboxing or external judge services.
- User dashboard to view past mistakes and learning progress.

Tech Stack
- Frontend:React.js
- Backend: Node.js, Express.js
- Database:MongoDB
- Optional Integrations:
  - Judge0 API for safe code execution.
  - OpenAI API (ChatGPT) for AI-powered suggestions.

Future Enhancements
- Support for multiple programming languages (C++, Python, Java, etc.).
- Advanced AI-based logic correction.
- Personalized learning modules based on mistake patterns.
- Gamification features to encourage coding practice.
