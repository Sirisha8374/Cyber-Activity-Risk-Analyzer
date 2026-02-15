#Cyber Activity Risk Analyzer

Project Description
-------------------
This Python program analyzes student activity scores and categorizes them into different risk levels.
It removes invalid (negative) values, groups valid scores into risk categories, and then applies a personalized filtering rule.
The personalization is based on the length of the user's name.
After filtering, a final summary report is displayed.

Risk Categories
---------------
Score < 0 → Ignored
0 – 30 → Low Risk
31 – 60 → Medium Risk
61 – 100 → High Risk
Above 100 → Critical Risk

Personalization Logic
---------------------
The program asks the user to enter their name.
If the length of the name is even, all Low Risk scores are removed.
If the length of the name is odd, all Critical Risk scores are removed.
This ensures personalized behavior for different users.

Program Output
--------------
The program displays:
Original data
Categorized lists before filtering
Categorized lists after filtering
Total valid entries
Ignored entries
Removed entries due to personalization

Files in this Repository
------------------------
Cyber-Activity-Risk-Analyzer/
│
├── challenge4.py
├── README.md
└── test_cases.txt

Language Used
-------------
Python
