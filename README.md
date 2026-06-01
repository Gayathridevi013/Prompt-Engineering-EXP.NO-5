EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

Aim:
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. Analyze the quality, accuracy, and depth of the generated responses.

Explanation:

Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model. Based on that pattern type refined the prompt and submit that with AI tool. Get the ouput and write the report.

Prepare Multiple Test Scenarios: Select various scenarios such as: Generating a creative story. Answering a factual question. Summarizing an article or concept. Providing advice or recommendations. or Any other test scenario. For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure. Run Experiments with ChatGPT: Input the naïve prompt for each scenario and record the generated response. Then input the corresponding basic prompt and capture that response. Repeat this process for all selected scenarios to gather a full set of results. Evaluate Responses : Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well? Deliverables: A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios. Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs. Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

OUTPUT:
Scenario 1: Email writing
Naïve:  Write any email
Here's a simple professional email example:
I drafted a sample email below.
Dear Sir/Madam,
I hope you are doing well.
I am writing to request leave for one day on June 5, 2026, due to a personal commitment. I will ensure that all my pending work is completed before my absence and will be available for any urgent matters if required.
Kindly grant me leave for the mentioned date. I would appreciate your consideration.
Thank you for your understanding.
Sincerely,
[Your Name]
You can replace the date and name as needed.

Basic: Write a professional email to a professor requesting a deadline extension for a project submission due to illness. Keep the tone polite and formal.

Here's a professional and formal email template:
Dear Professor,
I hope you are doing well.
I am writing to respectfully request an extension for the submission of my project, which is currently due on [Due Date]. Unfortunately, I have been  the project by the scheduled deadline.
I have been making every effort to continue working on the assignment; however, due to my health condition, I require some additional time to ensure that I can submit work that meets the expected standards. I would be grateful if you could consider granting me an extension until [Proposed New Date].
I apologize for any inconvenience this may cause and appreciate your understanding and consideration. If necessary, I can provide medical documentation to support my request.
Thank you for your time and consideration. I look forward to your response.
Sincerely,
[Your Full Name]
[Student ID]
[Course Name and Section]

Scenario 2:  Coding Assistance
Naïve: Write a Python program.
Sure. Here's a simple Python program that prints "Hello, World!":
# Hello World Program

print("Hello, World!")
If you need a program for a specific task (e.g., factorial, palindrome, sorting, matrix operations, file handling, etc.), tell me the requirement and I'll write it.

Basic: Write a Python program to find the factorial of a number using recursion. Explain each step with comments

Here's a Python program to find the factorial of a number using recursion, with detailed comments explaining each step:
# Function to calculate factorial using recursion
def factorial(n):

    # Base case:
    # Factorial of 0 and 1 is always 1
    if n == 0 or n == 1:
        return 1

    # Recursive case:
    # n! = n × (n-1)!
    else:
        return n * factorial(n - 1)


# Take input from the user
num = int(input("Enter a number: "))

# Check if the number is negative
if num < 0:
    print("Factorial is not defined for negative numbers.")

# Calculate and display the factorial
else:
    result = factorial(num)
    print("Factorial of", num, "is", result)
How it works
Suppose the user enters 5.
1.	factorial(5) returns 5 * factorial(4)
2.	factorial(4) returns 4 * factorial(3)
3.	factorial(3) returns 3 * factorial(2)
4.	factorial(2) returns 2 * factorial(1)
5.	factorial(1) reaches the base case and returns 1
Now the recursive calls return:
•	factorial(2) = 2 × 1 = 2
•	factorial(3) = 3 × 2 = 6
•	factorial(4) = 4 × 6 = 24
•	factorial(5) = 5 × 24 = 120
Output:
Enter a number: 5
Factorial of 5 is 120
Key Concept: Recursion is a technique where a function calls itself until a stopping condition (base case) is reached.

Scenario 3: Interview Preparation
Naïve: Help me prepare for an interview.

To prepare effectively, it's useful to cover HR questions, technical questions, communication skills, and interview strategy.
Common HR Interview Questions
1. Tell me about yourself.
Sample Structure:
•	Educational background
•	Relevant skills
•	Projects/internships
•	Career goals
Example:
I am a final-year Computer Science student with a strong interest in software development and artificial intelligence. I have worked on academic projects involving Python and machine learning and completed internships that improved my problem-solving and teamwork skills. I am eager to start my career in a role where I can contribute to real-world software solutions while continuing to learn and grow.
________________________________________
2. Why do you want to work for our company?
Tip: Research the company beforehand.
Sample Answer:
Your company is known for innovation and employee development. I am particularly interested in the opportunities to work on impactful projects and learn from experienced professionals.
________________________________________
3. What are your strengths?
Choose strengths relevant to the role.
Example:
•	Problem-solving
•	Adaptability
•	Teamwork
•	Time management
Sample Answer:
One of my key strengths is problem-solving. During my academic projects, I often took the lead in analyzing issues and finding efficient solutions.
________________________________________
4. What is your biggest weakness?
Mention a genuine weakness and how you're improving it.
Sample Answer:
Earlier, I was hesitant to speak during group discussions. To improve, I actively participate in presentations and team activities, which has increased my confidence significantly.
________________________________________
5. Where do you see yourself in five years?
Sample Answer:
In five years, I hope to have developed strong technical expertise, taken on greater responsibilities, and contributed meaningfully to the success of my organization.
________________________________________
Technical Interview Preparation
For Software/IT Roles
Review:
•	Programming fundamentals (C, C++, Java, Python)
•	Data Structures and Algorithms
•	Object-Oriented Programming
•	Database Management Systems (SQL)
•	Operating Systems
•	Computer Networks
Sample Technical Questions
1.	What is the difference between a list and a tuple in Python?
2.	Explain OOP concepts.
3.	What is normalization in DBMS?
4.	What is a deadlock in an operating system?
5.	Explain TCP and UDP.
________________________________________
Behavioral Questions
1. Describe a challenge you faced and how you overcame it.
Use the STAR Method:
•	Situation
•	Task
•	Action
•	Result
2. Tell me about a time you worked in a team.
Focus on:
•	Collaboration
•	Communication
•	Results achieved
________________________________________
Interview Day Tips
Before the Interview
•	Research the company.
•	Review your resume.
•	Prepare examples from projects and internships.
•	Practice common questions.
During the Interview
•	Maintain eye contact.
•	Listen carefully.
•	Answer clearly and concisely.
•	Be honest if you don't know an answer.
After the Interview
Ask thoughtful questions such as:
•	What does success look like in this role?
•	What are the team's current priorities?
•	What learning opportunities are available?
________________________________________
Quick Self-Introduction Template
Good morning/afternoon. My name is [Name]. I am currently pursuing a degree in [Branch] at [College]. I have developed skills in [Technical Skills] through coursework and projects. I am particularly interested in [Area of Interest]. I enjoy learning new technologies, solving problems, and working collaboratively. I am excited about opportunities where I can apply my skills while continuing to grow professionally.
If you tell me:
1.	Your branch (CSE, ECE, IT, Mechanical, etc.),
2.	Year of study,
3.	Target company or role,
I can generate a customized mock interview with questions and model answers.

Basic:  Provide 10 commonly asked HR interview questions for fresh engineering graduates along with sample answers and preparation tips.
10 Common HR Interview Questions for Fresh Engineering Graduates
1. Tell me about yourself.
Sample Answer
Good morning. My name is [Your Name], and I am a final-year engineering student specializing in [Branch] from [College Name]. During my academic journey, I have developed strong technical skills in [relevant technologies/subjects] and worked on projects that enhanced my problem-solving and teamwork abilities. I am eager to begin my professional career, apply my knowledge in real-world situations, and continue learning from experienced professionals.
Preparation Tips
•	Keep your answer between 1–2 minutes.
•	Focus on education, skills, projects, and career goals.
•	Avoid discussing personal details unrelated to the job.
________________________________________
2. Why do you want to work for our company?
Sample Answer
I am interested in your company because of its strong reputation for innovation and employee development. I admire the projects your organization has undertaken and believe that the learning opportunities here align well with my career goals. I would be excited to contribute my skills while growing professionally.
Preparation Tips
•	Research the company beforehand.
•	Mention specific achievements, values, or projects.
•	Show enthusiasm and genuine interest.
________________________________________
3. What are your strengths?
Sample Answer
My key strengths are problem-solving, adaptability, and teamwork. During my final-year project, I collaborated with team members to overcome technical challenges and successfully completed the project within the deadline.
Preparation Tips
•	Mention 2–3 strengths relevant to the role.
•	Support each strength with an example.
•	Avoid generic answers without evidence.
________________________________________
4. What is your biggest weakness?
Sample Answer
Earlier, I found it difficult to speak confidently in large groups. To improve, I started participating in presentations and group discussions. Over time, this has significantly improved my communication skills.
Preparation Tips
•	Choose a real but manageable weakness.
•	Explain how you are actively improving it.
•	Avoid mentioning weaknesses critical to the job.
________________________________________
5. Why should we hire you?
Sample Answer
Although I am a fresher, I bring strong technical knowledge, a willingness to learn, and a positive attitude. My academic projects have helped me develop practical problem-solving skills, and I am confident that I can quickly adapt and contribute to your team.
Preparation Tips
•	Connect your skills with the job requirements.
•	Highlight enthusiasm and learning ability.
•	Be confident but not arrogant.
________________________________________
6. Where do you see yourself in five years?
Sample Answer
In five years, I hope to have developed strong technical expertise in my field, taken on greater responsibilities, and contributed significantly to organizational goals. I also aim to continuously learn and grow as a professional.
Preparation Tips
•	Show ambition and commitment.
•	Align your goals with career growth.
•	Avoid unrealistic expectations.
________________________________________
7. Tell me about a challenge you faced and how you overcame it.
Sample Answer
During a team project, we faced difficulties integrating different modules developed by team members. I coordinated discussions, identified compatibility issues, and helped create a testing plan. As a result, we completed the project successfully before the deadline.
Preparation Tips
•	Use the STAR method:
o	Situation
o	Task
o	Action
o	Result
•	Focus on problem-solving and teamwork.
________________________________________
8. Are you comfortable working in a team?
Sample Answer
Yes, I enjoy working in teams because it allows me to learn from others and contribute my own ideas. Throughout my engineering projects and laboratory work, I have collaborated effectively with teammates to achieve common goals.
Preparation Tips
•	Provide examples from projects or college activities.
•	Highlight communication and collaboration skills.
•	Show respect for diverse perspectives.
________________________________________
9. How do you handle pressure and deadlines?
Sample Answer
I handle pressure by prioritizing tasks, creating schedules, and focusing on one task at a time. During semester exams and project submissions, I used effective time management to complete all responsibilities successfully.
Preparation Tips
•	Give real examples.
•	Emphasize planning and organization.
•	Show a calm and positive approach.
________________________________________
10. Do you have any questions for us?
Sample Answer
Yes, thank you. Could you tell me more about the training programs available for fresh graduates and the opportunities for professional growth within the company?
Preparation Tips
•	Always ask at least one thoughtful question.
•	Focus on learning, growth, or the role.
•	Avoid asking about salary in the first interview unless the interviewer raises the topic.
________________________________________
Quick Interview Preparation Checklist
✅ Research the company and job role
✅ Review your resume thoroughly
✅ Prepare project and internship explanations
✅ Practice answering questions aloud
✅ Dress professionally
✅ Arrive early or join online interviews on time
✅ Maintain eye contact and confident body language
✅ Be honest when answering questions
✅ Prepare 2–3 questions to ask the interviewer
✅ Follow up with a thank-you email if appropriate
Final Tip
For fresh engineering graduates, interviewers often value attitude, communication skills, problem-solving ability, teamwork, and willingness to learn as much as technical knowledge. Demonstrating these qualities through examples from your academic projects and experiences can significantly improve your performance.

Comparison Table
Scenario 	Prompt Type   	Quality	Accuracy	Depth 
Email writing 	Naïve	Medium	Medium	Low
Email writing	Basic	Good	Good	Medium 
Coding Assistance	Naïve	Medium	Good	Low
Coding Assistance	Basic	Good	Good	Good
Interview Preparation	Naïve	Good	Good	Good
Interview Preparation	Basic	Medium	Good	Low

RESULT: 
Hence the experiment have bee completed successfully.
