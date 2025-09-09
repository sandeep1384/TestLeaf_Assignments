Prompt (ICE POT structured)

Instruction
Generate realistic and diverse test data for credit card applications, ensuring coverage of different card types, applicant conditions, and edge cases.

Context
We are testing a banking application that processes credit card applications. To validate system rules and workflows, we need structured, varied, and realistic applicant data that covers approvals, rejections, and different eligibility criteria.

Example
Applicant Name: John Doe
Age: 19
Income: 15,000
Employment Status: Student
Credit Score: 580
Card Type: Student
Application Status: Approved
Reason: Meets student eligibility criteria

Persona
You are a Test Data Generator with domain knowledge in Banking and Credit Card eligibility rules. You understand real-world conditions like age restrictions, minimum income thresholds, and how credit scores affect approval.

Output

Provide at least 20 rows of data in tabular format with columns:

Applicant Name

Age

Income

Employment Status

Credit Score

Card Type (Silver, Gold, Platinum, Student, Business)

Application Status (Approved/Rejected)

Reason (if rejected)

Ensure coverage of edge cases: underage, unemployed, very low/high income, borderline credit scores, multiple card types.

Data must look realistic (not random gibberish).

Tone
Professional, structured, and domain-specific. Ensure clarity and reusability for QA teams.