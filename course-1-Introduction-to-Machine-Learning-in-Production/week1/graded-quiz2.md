1.
Question 1
You’ve built a new system for making loan approval decisions. For now, its output is not used in any decision making process, and a human loan officer is solely responsible for deciding what loans to approve. But the system’s output is logged for analysis. What is this type of deployment called?

1 / 1 point

Canary deployment


Red green deployment


Blue green deployment


Shadow mode deployment

Correct
That's right! Shadow mode is a type of deployment where the ML algorithm runs in parallel with the user but it’s output isn’t used for any decision making.

2.
Question 2
On a new social media platform, you’re rolling out a new anti-spam system to flag and hide spammy posts. Your team decides to roll out the anti-spam filter via a canary deployment, and roll it out to 1% of users initially. Which of these would you advocate?

0 / 1 point

Monitor that 1% of users’ reaction, and if it goes well, flip the switch to send all traffic (100%) to the system. 


Use a plan to ramp up to more users at a fixed rate: 1% in the first week, 2% in second week, 4% in third, and so on, so that the rollout can be well planned and managed.


After a successful canary deployment, begin to implement a shadow mode deployment. 


Monitor that 1% of users’ reaction, and either gradually ramp up (if it’s going well) or rollback (if not) 

Incorrect
While it's a great idea to ramp-up your canary deployment if it a success, this ramp up need not be scheduled at such a fixed rate. As well, in the case of an issue, you may consider a rollback too. 

3.
Question 3
You’re building a healthcare screening system, where you input a patient’s symptoms, and for the easy cases (such as an obvious case of the common cold) the system will give a recommendation directly, and for the harder cases it will pass the case on to a team of in-house doctors who will form their own diagnosis independently. What degree of automation are you implementing in this example for patient care? 

1 / 1 point

Full Automation


Shadow mode 


Partial Automation


Human only  

Correct
That’s correct! This type of approach offers some automation, but still requires a human in the loop.

4.
Question 4
You have built and deployed an anti-spam system that inputs an email and outputs either 0 or 1 based on whether the email is spam. Which of these will result in either concept drift or data drift?

1 / 1 point

Spammers trying to change the wording used in emails to get around your spam filter.


Cloud computational costs going down, resulting in a lower cost to process each email received.


Updating a monitoring dashboard to keep track of new metrics.


None of these will result in either concept drift or data drift.

Correct
That's right! Changing the wording will result in a concept or data drift. 

5.
Question 5
Which of these statements is a more accurate description of deployment?

1 / 1 point

Because deployment is a high stakes event, it's critical to design the right system, so that immediately after launch it will immediately work reliably and scale effectively.


It is an iterative process, where you should expect to make multiple adjustments (such as metrics monitored using dashboards or percentage of traffic served) to work towards optimizing the system.

Correct
That's correct! Don't plan or expect to perfect the deployment on your first attempt, it's much more reasonable and efficient to iterate on the process and optimize its performance over time. 
