Hiring Challenge: Rich Text Editor with Lexical – By Pratyush Kumar Sinha

For this assignment, I, Pratyush Kumar Sinha, developed a fully functional rich text editor using Lexical. This project demonstrates my approach to frontend architecture, state management, and building clean, maintainable code.

Overview

I created a React-based editor that goes beyond plain text, designed to be scalable and maintainable for real-world applications.

Key Features:

Lexical Editor Integration:
I implemented the editor using Lexical with React, following best practices to ensure stability and performance. I avoided direct DOM manipulation, keeping the editor fast and reliable.

Table Support:
Users can insert and edit tables directly from the toolbar. The logic for table management is decoupled from the UI, making it easy to extend or modify in the future.

Math Expression Support:
The editor supports inserting and editing mathematical formulas using KaTeX. Formulas render cleanly and remain fully editable after insertion.

State Management with Zustand:
I used Zustand to manage the editor’s state. The content is managed independently from the toolbar and other UI elements, ensuring that updates are efficient and only affect what’s necessary.

Saving and Loading Content:
The editor saves content as JSON in localStorage. Reloading the page restores the content seamlessly. The implementation is modular, making it easy to connect to a backend server in the future.

Notes:
I prioritized modularity, clarity, and maintainability throughout the project. This editor reflects my approach to building professional, production-ready frontend applications that are easy to extend and maintain.