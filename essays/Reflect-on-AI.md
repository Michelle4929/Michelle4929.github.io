---
layout: essay
type: essay
title: Responsive Design made Simple!
# All dates must be YYYY-MM-DD format!
date: 2024-05-05
published: true
labels:
  - AI
  - ChatGPT
  - ICS 314
---

### I. Introduction

In this day and age, most people have heard about AI. Artificial Intelligence is technology that enables machines to perform tasks commonly associated with intelligent beings, such as humans. In education, most students in modern times know how to use AI, such as ChatGPT, copilot, and much more. The big question being how helpful is AI in terms of education and helping students without being detrimental to their learning. There are always two sides to a coin with some supporting the aid of AI and others disagreeing that AI encourages dishonesty in terms of learning. AI is generally a tool to assist people to work more efficiently and to proof check their work. In those terms, AI has both a positive and negative impact to one's education. As students should not rely on AI to do all their work but should be used to learn or help improve one's current work.

For software engineers, AI can be used in multiple different ways, such as enhancing code efficiency for improved productivity. In that aspect, AI automates common tasks and offers problem-solving approaches when one gets stuck. Although, AI can produce key information or answers to your solution, it should not be 100% relied on as its information is not always correct. I personally think it is important to understand the basics of the topic before asking AI. As an ICS student, I've used ChatGPT on many occasions to debug my code. Although AI has helped on multiple occasions, it also gave wrong solutions just as much. In that case, it was important that I understood how to program/code as ChatGPT could give me different solutions but I would have to know how to read and understand what exactly I would use and change to fit my problems.

### II. Personal Experience with AI:
I have used AI in class this semester in the following areas:

  1. Experience WODs e.g. E18: I did not use AI for experience homework WODs. As these were WODs to help us practice for our in-class WODs, I wanted to see if I was able to solve them on my own first. If I was unable to solve them initially, the class provided enough material for me to look for aide in where I was stuck before I had the chance to use AI to assist me.

  2. In-class Practice WODs: I did not use AI for in-class practice WODs as well. With the same mindset as experience homework WODS, I wanted to see if I could solve them on my own without help from AI but only from sources provided from the class.

  3. In-class WODs: I have used AI for several WODs. In the beginning, I didn't want to use AI, such as ChatGPT to help but as WODs became essentially harder to meet the time through each week. I found myself having to use ChatGPT on multiple occasion to debug my code or for styling issues. Especially when we started using bootstrap meteor, it was my first time using bootstrap functions so on multiple occasions, I found myself asking ChatGPT on how to use certain calls or why my website did not display what I wanted. For example, in the Morning Brew WOD, I asked ChatGPT: "In meteor bootstrap, how do I get my text to display over an image?", which it outputed:
```
.overlay-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white; /* Text color */
    font-size: 24px; /* Adjust font size as needed */
    text-align: center; /* Center text horizontally */
    /* Additional styles as needed */
}
```
In terms of styling, ChatGPT helped me immensely, as most of the time, I would finish a WOD but the format of the website would not match what the in-class WOD had wanted. After using ChatGPT's suggestion, it actually helped me use bootstrap meteor more effectively, as I would test trial different solutions and found out what different functions would actually do.

  4. Essays: I did not use AI initially for essays but towards the end of the semester, I found using AI for ideas really helped me start the initial train of flow for my essays. For example, in the design pattern essay, after reading up about different design patterns, I was still conceptually confused on the different patterns. At that point, I had asked ChatGPT to explain in more details: "Can you give me examples of the 3 different type of design patterns?". With actual coded examples, I was able to understand at what given moments I had used design patterns in my current and past codes.

  5. Final project: I did use AI on multiple occasions for the final project. In the beginning of the project, just setting up each page was relatively easy as it was similar to previous materials we have learned so I didn't use AI during those times. But when it came to incorperating new material we have not learned how to use, I would occasionally ask ChatGPT whenever I got stuck and couldn't dig myself out of the hole. For example, in our final group project we had to make a study application that helps connect students with joining study sessions for ICS/IT students in UHM. In our application, we had to develop a calendar, which we have not learned how to do in class yet. After finding a fullcalendar plug-in we could use for meteor, I found the instructions on how to use fullcalendar a bit vague in terms of what we wanted to use it for. Setting up the initial calendar was simple but having to add events with a working collections ended up being pretty difficult. With my groupmates, after going through trial and error for each solution we came up with, even with ChatGPT's help, we were finally able to incorporate some of ChatGPT's as well as our own solutions. ChatGPT helps in giving a base case/framework but we need to know how to mold it. In this case, I think it showcases how important it is to also understand the material as not all of ChatGPT's answers fit your problem even if it does help in others.

  6. Learning a concept / tutorial: I did use AI to help understand a concept on multiple occasions. Although, there are many articles available online that cover material I have yet to learn, a lot of times, I find it difficult to understand what exactly it is trying to tell me. Especially if I am learning it for the first time, when the word choices and examples are convoluted, I would need a simpler explantion. I found that if I copy the difficult example/phrase and use ChatGPT to explain what exactly it means, or to explain in simpler terms, most of the times I would actually understand it better. For example, when we first started learning how to use the underscore function in javascript, there were a lot of new functions to learn and I felt overwhelmed at first. Even each function only had one example, I used ChatGPT to understand in more detail what each function was used for: "Could you give me multiple examples on how to use the underscore function filter in javascript?".
```
const _ = require('underscore');

const users = [
  { name: 'John', age: 30 },
  { name: 'Alice', age: 25 },
  { name: 'Bob', age: 35 }
];

const adults = _.filter(users, user => user.age >= 18);

console.log(adults); // Output: [{ name: 'John', age: 30 }, { name: 'Alice', age: 25 }, { name: 'Bob', age: 35 }]
``` 
This really helped me understand how to use filter on different problems and for different variables to the point, I found myself using it to solve a lot of problems in WODs compared to other functions I could've used.

  7. Answering a question in class or in Discord: I did not use AI to answer any questions in class or on discord. In terms of answering questions in class, usually it would be in a group settings, when we are doing practice in-class WODs and have questions for one another. I found that in these times, trying to solve the problems on your own was more efficient so that I don't rely on AI for all thought processes and it was more beneficial as a group to go through each problem together and seeing when the lightbulb goes on when we worked through the problem.

  8. Asking or answering a smart-question: I did not use AI to ask or answer a smart-question. To be fair, I did not ask or answer any smart questions on Discord but I have asked a fair share of questions to the TA and professor in class. I don't really like using AI to help ask for questions as it would either change my question into something I'm not really asking for and would lose the personal touch of what my problem actually is. Plus as a student learning how to ask a smart question, I found it more productive to think about how to format the question myself.

  9. Coding example e.g. “give an example of using Underscore .pluck”: Similar to learning a concept, I ended up actually using coding examples the most for underscore in javascript. As the beginning of class was more programming heavy in terms of a typical coding language. As a first time underscore function user, I used ChatGPT to ask for a lot of coding examples of each function. I'm usually a multiple-example learner as I usually try to see the related pattern between each example and try to understand why it works that way.

  10. Explaining code: I definitely used AI to explain codes that I did not understand or why my code was not outputting exactly what I needed it to. A lot of times when using IntelliJ, my code would pass the ESLint check and I would think everything works but when I check my browser, my website/application would not display what I wanted it to. Confused on what exactly went wrong, I would end up copying my code into ChatGPT to ask why my code is not outputting what I want it to. For example, "Why is my code not displaying the font I added?". Then it gave me a thorough explanation on what could possibly be the problem and how to change it so that it may work.

  11. Writing code: I used AI to write code, usually to help fix a current code I had already made or to start a code I wasn't sure of. I usually had a harder time with AI when it came to fixing a current code already made as the solutions would usually also not work but after learning to use AI more proficiently in this class. I found that even though some solutions AI gives doesn't work, a lot of times if you can edit and change certain aspects to fit your problem then it'll usually end up working. In terms of efficiency, this really helped me speed up my code as I don't have to sit there for multiple hours wondering what went wrong but instead use that time with the help of AI to come up and try multiple different solutions.

  12. Documenting code: I did not use AI to document my codes. I think it is important to know what exactly your code does even if it is a code from AI so when documenting the code, we should write what the code block does ourselves.

  13. Quality assurance: I did use AI for quality assurance, especially when it came to essays. I tend to have a lot of spelling and grammatical mistakes. I ended up using Grammarly on almost all my essays after I finished just for that last cherry on the top.

  14. Other uses in ICS 314 not listed above: I think the ones listed above were all the times I have and have not used AI in ICS 314.



### III. Impact on Learning and Understanding:


### IV. Practical Applications:


### V. Challenges and Opportunities:


### VI. Comparative Analysis:


### VII. Future Considerations:


### VIII. Conclusion:
