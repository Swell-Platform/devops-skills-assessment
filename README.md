# devops-skills-assessment
Hello, congrats on being identified as a potential employee of Swell. You were sent this skills assessment as a way to identify your current strengths and weaknesses as a potential hire for Swell as a DevOps and/or Site Reliability Engineer. Doing well on this assessment is absolutely critical to receiving a job offer.

## Required Skills
- Git version control system
- Some node.js skills
- Docker
- Terraform, Cloudformation or some other IaC language/framework

## Rules
1. It should only take about 1-2 hours to complete the assessment. If you need more time, that is allowed, however the amount of time from your first commit to last will be used to assess you as a candidate for the position. Only start the assessment when you are ready to give it your full attention.
2. You may use any code or text editor to complete the assessment you choose. We recommend [Visual Studio Code](https://code.visualstudio.com/) as a free choice.
3. You may use any programming language, library or framework to complete the assessment.
4. You may consult anybody and anything to help you with your assessment, including google, developer documentation, stackoverflow, etc. However, it will be apparent if you use copy-pasta code, and your unique code style will be part of your assessment.
5. If you use others' code (i.e. Stack overflow answers), make sure you credit the author/answer in comments inline with your work
6. It is not required to actually deploy your code to an AWS account for cost savings, however it should create a valid cloud infrastructure plan.

## Assessment Scenario
Congrats, it's your first day at Swell. You get your badge, find a desk, and are ready to get started. Your manager comes up, introduces themself, and assigns you your first task. He tells you that, recently he asked a developer to build a simple landing page for the company. The developer built the project in node.js

He wants you to do two things:
1. Containerize the application using docker.
2. Use an Infrastructure as Code technology (Terraform, Cloudformation, Pulumi, etc.) to deploy the application in the company's AWS cloud infrastructure. For the purpose of this task, create a new VPC, subnets, internet gateway, and all other networking necessary for connecting to the deployed instance.
3. Use your best decision-making for using cloud services like ECS or EKS for deploying the instance.

## Instructions
1. Fork this repository to your personal github page. You will need to create a github account if you don't have one by [visiting this link](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home).
2. Clone the repository to your machine.
3. If you do not have node.js installed on your computer, you will need to install it. You can use the [official binary](https://nodejs.org/en/) or a tool like [node version manager](https://github.com/nvm-sh/nvm).
4. Navigate to your projects directory on your machine and run the command `npm start`.
5. You should be able to visit the webserver built by the junior developer by typing into your browser `http://localhost:9876`.
6. Add your dockerfile and IaaC code to complete the task. 
8. Respond back to the hiring manager who contacted you and asked you to complete the assessment with the link to the repository.
