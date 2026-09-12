decodelabs-python-internship
Python Internship Projects — DecodeLabs Batch 2026
■ DecodeLabs Python Internship — Batch 2026
Projects built during my Python Developer internship at DecodeLabs.
■ Project 1 — To-Do List
• Concepts Used: Lists, append(), for loops, enumerate(), JSON persistence
• Features:
- Add tasks
- View all tasks with status
- Mark tasks as Done
- Delete tasks
- Data saved to disk (tasks.json)
• How to Run: python todo_list.py
■ Project 2 — Expense Tracker
• Concepts Used: Accumulators, while loop, try/except ValueError, float type casting, sentinel values, JSON persistence, category
breakdown
• Features:
- Add expenses with category & description
- Quick-add session (continuous entry mode)
- Real-time running total using accumulator pattern
- Category-wise breakdown with visual bar
- Defensive coding — rejects invalid input
- Data saved to disk (expenses.json)
• How to Run: python expense_tracker.py
■ Project 3 — Random Password Generator
• Concepts Used: import string, import secrets, ''.join(), entropy math E=L*log2(R), NIST guidelines, JSON persistence
• Features:
- Cryptographically secure via secrets module (NOT random)
- Guaranteed character types (uppercase, lowercase, digits, symbols)
- Entropy analysis in bits with crack-time estimate
- NIST compliant (8-64 character range)
- O(N) efficient ''.join() — not O(N^2) string concatenation
- Generation history saved to disk
• How to Run: python password_generator.py
Built with ■ by Khushal Parmar
