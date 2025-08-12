---
layout: essay
type: essay
title: "Reflecting on My Use of AI in ICS 314"
date: 2025-08-11
published: true
labels:
  - AI in Education
  - Software Engineering
  - Reflection
  - ICS314
---

## I. Introduction

Artificial Intelligence (AI) has become an increasingly common tool in education, particularly in **software engineering**, where it can assist with coding, debugging, design, and even learning new concepts. In ICS 314, I interacted with various AI tools to enhance my workflow and understanding. The main AI tool I used was just **ChatGPT**. This essay will reflect on how I used AI in different parts of the course, how it impacted my learning, and how I see its role in future software engineering education.

---

## II. Personal Experience with AI

Below are my reflections for each course element, including examples of prompts I used and an evaluation of AI’s usefulness in each case.

1. **Experience WODs (e.g., E44: Nextjs Hello World)**  
   *Example:*  
   Prompt: `"In the terminal output after running npx create-next-app, it says '129 packages are looking for funding — run npm fund for details.' What does 'funding' mean in this context?"`  
   Reflection: *I was curious about some of the extra messages in the terminal that weren’t directly part of the assignment steps, so I asked AI what they meant. AI explained that the npm fund message is just letting me know that some of the packages I installed are from open-source projects that accept financial support. Running npm fund would list the links where I could contribute to the maintainers. While it didn’t affect the WOD itself, it gave me a better understanding of the open-source ecosystem behind the tools we use.*  

2. **In-class Practice WODs**  
   Prompt: `"Give me a beginner-friendly explanation of how Next.js works, including its folder structure, routing system, and how it differs from a regular React app."`  
   Reflection: *For the Next.js in-class practice WODs, I noticed there wasn’t much extra material provided on where to learn more about the framework beyond the WOD instructions. I used AI to fill in the gaps — asking it to explain how Next.js works, what the /app directory does, and how the App Router changes routing compared to older Next.js versions. The AI also gave me a high-level overview of key features like server-side rendering and static site generation. This helped me understand why Next.js was structured the way it was, making it easier to follow the WOD instructions and feel more confident in building apps with it.*  

3. **In-class WODs**  
   Prompt:  `"How do I improve the following blocks of code? Provide explanations for why."`
   Reflection: *I use AI after the In-class WODs, the purpose of this was to see what I could improve on. As the In-class WODs were timed, it had more pressure, causing me to make careless mistakes. There are always improvements I can make when I program.*  

4. **Essays**  
   Prompt: `"How do I structure this essay in .md?"`
   Reflection: *I wasn't too familiar with how to format the essays in .md format at first, so the first few essays I used the prompt to figure out and familiarize myself with using structures like 'format', etc..*  

5. **Final project**  
   Prompt: `"Provide me a workflow for git push, make sure to avoid messing up the main build."`  
   Reflection: *As the Final Project was collaborative, I wanted to make sure that what I did in my local side didn't mess up the main build. As I still had much to learn with using git in bash, I wanted to make sure that each of my 'moves' were understood by myself.*  

6. **Learning a concept / tutorial**  
   Prompt: `"In Next.js, what does the 'pages' folder do and how does file-based routing work?"`  
   Reflection: *When I was learning the basics of Next.js, I used AI to clarify some of the simpler concepts like the role of the pages folder and how file-based routing works. AI explained that each file in the pages directory automatically becomes a route in the application — for example, pages/index.js becomes / and pages/about.js becomes /about. This helped me quickly connect the folder structure to the way URLs were generated, which made the tutorials much easier to follow.*  

7. **Answering a question in class or in Discord**  
   Prompt: `N/A`
   Reflection: *As I didn't ask much questions in the Discord, I didn't really see a use in AI for this case. For the questions I asked, they were relatively simple and was concerned with grading.*

8. **Asking or answering a smart-question**  
   Prompt: `N/A`
   Reflection: *I didn't see any use of AI in asking or answering a smart-question. As asking a smart question wasn't too difficult, I also didn't answer questions if I didn't know how to answer them.*  

9. **Coding example**  
   Prompt: `"Show me an example of a simple Next.js component that displays a list of items from an array, and explain the code."`  
   Reflection: *I used AI to get a small example of a functional component in Next.js that maps through an array and displays the items in a list. The AI provided a clean, minimal example, which helped me understand how JSX rendering works in a Next.js page. Even though I could have figured this out on my own, having the example saved me time and gave me a reference I could modify for the WOD.*  

10. **Explaining code**  
    Prompt: `"Explain what this Next.js page component does and how it works: <paste code snippet>."`  
    Reflection: *I asked AI to break down a piece of example code from a practice WOD so I could better understand each part. It went through the imports, the function definition, the return statement, and even explained why certain Next.js conventions were used. This helped me not just memorize the code but also understand the reasoning behind it, which made it easier to adapt the code for different scenarios.*  

11. **Writing code**  
    Prompt: `"Write a Next.js page that fetches JSON data from an API endpoint and displays it in a table."`
    Reflection: *For a practice exercise, I used AI to help me scaffold out a Next.js page that fetched data from an API. The AI gave me a working example using getStaticProps. I still had to tweak it to match the assignment requirements, but it gave me a solid starting point and saved me from blank-page syndrome.*  

12. **Documenting code**  
    Prompt: `N/A`
    Reflection: I already learned a fair amount of how to document code from my previous ICS classes (e.g. ICS211, 212), so using AI wasn't needed.

13. **Quality assurance (e.g., “What’s wrong with this code <code here>” or “Fix the ESLint errors in <code here>”)**  
    Prompt: `"For the following block of code, I recieved these errors, what went wrong?"`  
    Reflection: *As we were using many tools, it also came with a fair amount of errors that I wasn't familiar with, especially with errors relating with databases.*  

14. **Other uses in ICS 314 not listed**  
    Prompt: `N/A`  
    Reflection: *I mainly used AI to explain software used in the class.*  

---

## III. Impact on Learning and Understanding
*AI tools helped me a lot for topics that had a steep learning curve, such as learning the basics of Next.js or understanding unfamiliar terminal output. They often provided explanations that were simpler and more direct than official documentation, which made it easier to grasp new concepts quickly. However, AI can sometimes get mixed up or provide outdated or incorrect information, which led to errors and occasional misunderstandings. This taught me to treat AI responses as a starting point rather than the final answer, and to always verify the information through testing or official sources.*

---

## IV. Practical Applications
*Outside of ICS 314, I have been using AI to support a personal hobby project that applies computer vision in Python to analyze bouldering videos. The goal is to process footage to identify movements, track climber positions, and possibly suggest improvements based on body positioning. AI has been especially helpful for learning about relevant Python libraries like OpenCV and MediaPipe, as well as for troubleshooting when I ran into issues with frame extraction and object tracking. While the suggestions weren’t always perfect, AI often provided starting points or alternative approaches that I could refine. This sped up the learning process and made it easier to experiment with different techniques without getting stuck on small details.*

---

## V. Challenges and Opportunities
*One of the main challenges I faced when using AI was trusting its answers too quickly. Sometimes, AI provided incorrect or outdated code suggestions, especially with frameworks like Next.js that update frequently. This could lead to wasted time debugging problems that came from following the wrong approach. AI explanations could also be vague or oversimplified, which meant I still had to dig into official documentation to fully understand the concept.*

*On the other hand, AI presents significant opportunities for future courses. It can act as an on-demand tutor, providing quick explanations, alternative solutions, and code examples when students are stuck. If integrated carefully, AI could help bridge gaps in understanding without replacing the need for critical thinking and independent problem-solving. With the right balance, AI could make learning more interactive, personalized, and efficient.*

---

## VI. Comparative Analysis
*Using AI tools versus traditional approaches created a very different learning experience. With AI, I could get answers and examples almost instantly, which kept me engaged and allowed me to move past roadblocks quickly. Traditional approaches — such as reading documentation, searching Stack Overflow, or trial-and-error coding — took more time but often resulted in deeper retention because I had to work through the reasoning myself. I found the best results came from a mix of both: using AI for quick guidance or clarifications, then verifying and expanding my understanding through official sources and hands-on practice.*

---

## VII. Future Considerations
*I believe AI will play a larger role in software engineering education in the coming years. For ICS 314, it could be integrated as a supplementary learning resource — perhaps with guided AI prompts or an “AI companion” that’s tuned to the course content. This could help students get targeted help without falling into the trap of copying and pasting code without understanding it. The main challenge will be ensuring that AI use supports critical thinking rather than replacing it. Encouraging students to explain AI-generated answers in their own words could be one way to strike this balance.*

---

## VIII. Conclusion
*My experience using AI in ICS 314 showed me that it’s a powerful tool when used responsibly. It helped me tackle steep learning curves, like with Next.js, and provided quick explanations when I didn’t know where to start. However, I also learned that AI isn’t always correct, and relying on it too heavily can lead to misunderstandings. For future courses, I think AI should be encouraged as a research and brainstorming aid rather than a complete solution provider. This way, it can enhance learning while still requiring students to think critically, test solutions, and truly understand the code they write.*
