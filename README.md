# CSCI355FINALPROJECT
The final project for Nikola baci winter 355 class

Aditya Dwivedi
I worked further on the results page making it so that the history of previous test scores is saved and displayed on the final result page after giving multiple quizes. I made a JSON file with an empty array in it and mapped the quizical.ejs file to it to store all the quiz results in the json file. This helped store past quiz results and helped me display the quiz results on the result page. This involved writing reading and writing statement to map to the json file and also working closely with Tim as his and my code were connected by a lot.

Arun Dahal:
Quiz Zone is a fun and easy-to-use quiz platform where users can test their knowledge in categories like Science, Education, Technology, and Computer Science. I worked on the homepage, making it simple and clear so users can log in, sign up, or reset their passwords easily. The homepage also shows the quiz categories with cool icons and hover effects to make it look nice. The signup and reset pages are straightforward and work well on any device.
The backend uses Node.js with Express.js, and we stored user data in a JSON file for now. 

I had an amazing time working on this project with my teammates, Timothy Ng and Aditya Dwivedi. They were great to work with, and we all worked hard to make everything fit together smoothly. This project was a great experience, and I’m proud of what we built as a team.


Timothy Ng
I handled the back end of the project. I updated the project to send fetch requests to the OpentriviaDB, sent the responses all to the JSON files, I shuffled it before giving to users, I made it so that the project wasnt reliant on each fetch request since opentrivia gives bad request sometimes. When given a bad request, the response is skipped and the current JSON file of trivia questions gets re shuffled to send questions to the page. I also handled the MongoDB database, and had all the scores sent to my personal schema. And I handled connecting everyones code into this one project.


Here is the youtube link to the video walkthrough:
https://youtu.be/3Msi8rU2odA


Run by typing npm start in terminal
and then go to local host 2000
