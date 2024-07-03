# Interview_Question_Creator_GenAI
- In this project we have developed and deployed a generative ai application which creates questions and answers based on the pdf provided.

- The tool stack used for the project is as follows:

1. Python - programming language
2. OpenAI API - LLM
3. FAISS - vector database
3. FAST API - API creation
4. AWS EC2 - application deployment
5. HTML/CSS

### What is the need for this Interview Question Answer creator app?
- Let us say you are teacher who is teaching a particular topic. You want to quizz your students on the same. When you upload pdf of the topic that you are stuying, this application can generate questions and their appropriate answers.

- This will enable in saving time for the teacher, so that they can move on to creating more constructive things for students.

### How has this app been created?


### How does the application look like?

1. App UI - 1
   ![AppUI1](https://github.com/therealabhishek/Interview_Question_Creator_GenAI/blob/main/assets/aws_instance.PNG)

   - You can upload the pdf file by clicking on the 'Choose File' button and click 'GenerateQ&A' to generate the question answers.

2. App UI - 2
    ![AppUI1](https://github.com/therealabhishek/Interview_Question_Creator_GenAI/blob/main/assets/aws_instance_1.PNG)

    - After the question answer are generated, the pdf we uploaded to generate will be visible and the question answer pai can be downloaded by clicking on the yellow button with downward arrow. The downloaded file will be a '.csv' file.

    - We can open the file using notepad as well to have a look at the generated question answers.

3. EC2 deployment
    ![EC2](https://github.com/therealabhishek/Interview_Question_Creator_GenAI/blob/main/assets/ec2_apprun.PNG)

   - The image above shows the app running on EC2 instance.


