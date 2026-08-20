Assignment 1: Understanding Concepts
Objective: Check basic understanding of branching.

Tasks:

What is a branch in Git? Explain in your own words.
Why should we not work directly on the main branch?
Explain the road analogy of branching (main road vs side road).
What is the difference between git branch and git switch?
Answer=<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/f5861532-cbfe-4e1b-a86e-a6a2647e3b5e" />

Assignment 2: Commands Identification
Objective: Identify the correct commands.

Tasks:

Write the command for the following actions:
Action	Command
List all branches	
Create a new branch named feature-home	
Switch to feature-home	
Create + Switch in one command	
Merge feature-home into main	
Delete feature-home after merge	
Write both the modern and older command for:
Switching to a branch
Creating + switching to a new branch
Answer=<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/9ae9d968-9f5e-470c-a310-9fe5b439ecb8" />

Assignment 3: Practical Branching Workflow
Objective: Perform the complete branching cycle.

Tasks:

Make sure you are on the main branch.
Create a new branch named feature-contact.
Create a file contact.txt and write your name + any message.
Stage and commit the file with a meaningful message.
Switch back to main.
Merge feature-contact into main.
Delete the feature-contact branch.
Verify using:
git branch
git log --oneline
Answer=<img width="1498" height="832" alt="Screenshot 2026-08-20 171253" src="https://github.com/user-attachments/assets/339233ec-ec99-4eb6-bffd-8ff5a7a68ad0" />
<img width="1085" height="183" alt="Screenshot 2026-08-20 171159" src="https://github.com/user-attachments/assets/6383c5ab-08ba-4c56-968e-b01e9b00227f" />

Assignment 4: Conceptual + Error Handling
Objective: Understand rules and common mistakes.

Tasks:

What will happen if you try to delete a branch that is not yet merged?
Write the error and how to fix it.
Why should you always commit before switching branches?
Fill in the correct flow:
______ → Work → ______ → ______ → Switch to main → ______ → Delete branch
Explain the difference between:
git branch -d branch-name
git branch -D branch-name
Answer=<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/7333472d-19e9-47dd-af68-fc99e26e944f" />

Assignment 5: Complete Real Scenario
Objective: Apply branching in a realistic situation.

Scenario:
You are working on a website project. Currently you are on the main branch. You need to add two new pages: About and Services.

Tasks:

Create a branch feature-about, add a file about.txt, commit it, merge it into main, and delete the branch.
Create another branch feature-services, add a file services.txt, commit it, merge it into main, and delete the branch.
After completing both, show:
Final list of branches (git branch)
Final commit history (git log --oneline)
Answer:
Why did we create two separate branches instead of doing both features on one branch?
What is the advantage of merging only after the feature is complete?
Answer=<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/9c2bc344-6e2e-4fd8-b738-4bd5d4076ad2" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/e892efe6-a2ee-4661-b867-2f695d9519ca" />
