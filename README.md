# WEBHOOK-PROBLEM-SOLVER
a Spring Boot application that automatically interacts with a remote API at application startup, without any manual HTTP trigger (i.e., no controller call).


Objective 
The application must: 
• Call the /generateWebhook endpoint on startup. 
• Solve the assigned problem and store the result in a json. 
• Send the result to the provided webhook with JWT authentication. 

>>> Mutual Followers 
Identify mutual follow pairs where both users follow each other. Output only direct 2-node cycles as [min, max] once.
