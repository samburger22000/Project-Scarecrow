Cecure Intelligence Limited Academy Final Project:

Our team of 29 finalists (starting from 600+) collaborated on building a machine learning-powered farm pest detection and management system. We divided into sub-teams focusing on various aspects, including technical design documentation, monitoring and compliance (my role), architecture diagram, infrastructure as code (IAC), and more.

Project Goal:

Develop an algorithm to detect farm pests using images and trigger automatic deterrent measures (lights or sounds) to scare them away.
Display results on a user-friendly web app accessible globally to farmers.
Integrate a personalized QuickSight dashboard for each farmer within the web app.
Project Implementation:

Machine Learning: We utilized Amazon SageMaker to train a highly accurate pest detection model using 400 images of 6 different pest types.
Data Processing and Action Trigger: An IoT topic triggered a Lambda function that made predictions and stored results in a DynamoDB table.
Web App Development and Deployment:
AWS Amplify hosted the web app.
Amazon Cognito ensured user authentication.
WAF provided security.
Cloudfront delivered low latency and global availability.
Route 53 managed DNS routing.
Data Storage and Security:
S3 buckets stored raw and trained images, along with logs from CloudWatch and CloudTrail.
Server-side encryption and Amazon Key Management Service (KMS) ensured data security at rest.
Project Link and Code:

Explore the project details on my GitHub: [link removed]
Visit our functional website: www.scarecrow.tspace.uk
Key Learnings:

Beyond technical skills (machine learning, serverless technologies, QuickSight integration), the project fostered valuable skills like leadership, teamwork, collaboration, and project management. Additionally, working and connecting with colleagues from diverse backgrounds across Africa was a highlight.

Gratitude:

Sincere thanks to:

Blessing Udoisang MIET: For recognizing my potential and providing continuous support and encouragement.
Blessing Ogechi Nwojiji: For making learning sessions fun and fostering friendships.
Victor Ademola: For providing necessary pressure to keep us focused.
OJ Adekoya: For offering this incredible learning opportunity.
Cecure Intelligence Limited: For their invaluable contribution.
Team Members: (listed individually) Thank you for your teamwork and collaboration. I cherish the experience and look forward to future endeavors together.
Bonus: Happy and successful March everyone! Let's keep striving for even greater achievements.
