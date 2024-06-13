Design Project 6: Project Showcase
====================================
## Final Interface

https://www.figma.com/design/O8fbdPu9gTO4BjODvYKyMP/Paymily-Design-DP5?node-id=0-1&t=S5L5vDueND6CCgB8-1

## Representative screenshots

![image](https://github.com/hogyulee/cs374/assets/66636839/c3168271-90c5-47e7-bcbe-aa477c397242)
![image](https://github.com/hogyulee/cs374/assets/66636839/b492c81c-3e58-49bb-ab30-43bd23e48918)
![image](https://github.com/hogyulee/cs374/assets/66636839/337f43a7-fd90-4b34-beaf-a0a181e7d61e)
![image](https://github.com/hogyulee/cs374/assets/66636839/883cd44d-d33a-4fc7-86ff-40da37f75a87)
![image](https://github.com/hogyulee/cs374/assets/66636839/2efbfec6-a939-42b7-a37f-0ced060f3608)

## Quality arguments

Our interface stands out as a high-quality user experience, defined by its dynamic logic, user-friendly design, and responsiveness. Below are key arguments that demonstrate why our interface is exceptional:

#### 1. Dynamic and Adaptive Logic: 
   
We created a sophisticated logic system, which dynamically responds to user inputs. This system doesn't just execute pre-determined pathways; it adapts based on the user's interactions. For each section, we meticulously set local variables and display orders, ensuring a smooth, logical progression that feels intuitive to the user. For instance, we have a local variable for approver and candidate of approvers, which dynamically changes its value based on the user's input. We also created a variable that stores the current status of a request, allowing for a natural change of the notification page and badge. This adaptive logic ensures that the interface remains responsive and relevant to each user's unique journey.

![image](https://github.com/jiwoong123/hciprojects/blob/main/img/image5.png?raw=true)

![image](https://github.com/jiwoong123/hciprojects/blob/main/img/image4.png?raw=true)

#### 2. Modular Component Design:

We utilized a wide range of UI components, each carefully chosen and implemented to ensure easy updates and modifications. This modularity means that our interface is not only tailored for current requirements but is also ready for future enhancements without extensive overhauls. We sorted our components and icons within designated frames so that they could be easily found and revised. Components are organized cleanly, making revisions straightforward and less error-prone for developers. This foresight in design supports sustainability and adaptability, key markers of a high-quality interface. The modular approach also facilitates collaboration among team members, as each component can be developed and tested independently before integration into the larger system.



![image](https://github.com/jiwoong123/hciprojects/blob/main/img/image3.png?raw=true)

#### 3. Simplicity and Intuitiveness:
Users often remarked on the simplicity and intuitiveness of our interface. The common feedback was, "Is that all?"—a testament to the interface's ease of use. Tasks that traditionally take multiple steps without our interface could be completed in just a few clicks with ours. As our task 1 shows, asking for approval with detailed information about the transaction took only four clicks to complete. This simplicity empowers users, reducing the cognitive load and making the technology accessible to a broader audience. By focusing on essential functions and streamlining the user journey, we ensured that even those with minimal technical skills could navigate our interface effortlessly.



![image](https://github.com/jiwoong123/hciprojects/blob/main/img/image2.png?raw=true)

### 4. Detailed and Responsive Feedback:

We have received significant positive feedback about the detailed and responsive nature of our interface. Every action a user takes is met with immediate and clear feedback. For example, numerical data and progress bars are not only accurately calculated but are displayed in a manner that is meaningful and easily digestible for users. This level of detail ensures that users are never in doubt about the impact of their actions, enhancing trust and satisfaction. By providing real-time feedback, we help users feel more in control and confident in their interactions with the system.


![image](https://github.com/jiwoong123/hciprojects/blob/main/img/image1.png?raw=true)

In summary, our interface excels because it is user-centric, adaptable, and detail-oriented, making it not just functional but a pleasure to use. Its design anticipates future needs, ensuring longevity and continued relevance in an evolving tech landscape. This combination of features makes our interface truly great, setting a benchmark for what effective UI design should look like. By focusing on dynamic logic, modularity, simplicity, and responsive feedback, we have created an interface that stands out in terms of quality and user satisfaction.


## Iteration

We mainly used the DP6 period for iteration to fix user problems discovered in DP5. The process can be divided into two stages.

- The stage of distinguishing between what we will accept and what we will not accept among the discovered user problems.
- The stage of fixing user problems that we accepted

We set a standard for deciding what to accept and what not to accept. The standard is that if we determine that our modification is likely to cause another user problem, we will not reflect that modification. The reason for this decision is that since there is no opportunity for another iteration, there is no opportunity to make corrections if there is a problem with the newly added product. Because we wanted to finish the prototype as complete as possible, we agreed to fix the existing functions and made modifications.

Below are the user problems we decided to accept and the fixes we made.

Problem 1: It is not intuitive to check whether you agree or disagree with the terms and conditions. When attempting to disagree, a message immediately pops up stating that consent is required, which confuses users.

- Instead of blocking the unchecking of the agreement, we made the payment button not clickable if the user does not agree.

Problem 2: The screen when a payment does not proceed due to budget exceedance is similar to the screen when the payment is successfully completed, making it difficult for the user to notice that the budget has been exceeded.

- We displayed the fact that the budget has been exceeded in large letters at the top of the screen, and made the positions where the used amount and remaining budget are displayed closer together so that users can intuitively know that the budget has been exceeded.


## Individual Reflection - Gyuho Lee
#### What part of the interface did you contribute to?

The category-specific consumption management interface, which is a core feature of our interface, was designed by me. Also, the idea of ​​adding a message to the interface and the idea of ​​enabling family invitations via SMS and invite code were all my ideas.

I contributed to the interface, but more than that, I contributed to the team by writing team report. With limited time, our team had to do a lot of work,  so interface improvement and team report writing were done simultaneously in one pipeline, and I was mainly responsible for writing the team report. I contributed greatly to writing the team project report. From DP1 to DP6, I feel like I wrote about 80% of the reports.

#### What worked well and not in your team?

Our team got almost everything done right. Among them, division of labor seems to have been achieved the best. Rather than everyone being stuck on the same task, which reduces efficiency, each person found what they needed to do and worked efficiently.

On the other hand, it was relatively difficult to unify opinions. Because each person expressed their opinions in abstract terms, it was not easy to understand what each person was saying and it was not easy to unify opinions.

#### How did you overcome any hurdle in teamwork?
We were able to overcome the hurdle by organizing and exchanging our thoughts in writing. After seeing each other's thoughts in concrete writing rather than abstract words, we were able to understand each other's thoughts and figure out exactly where there was a difference of opinion. Also, when we actually wrote down our different thoughts, there were many cases where there was not much difference in the content. This written method of communication helped us unify our opinions.

#### What lesson about teamwork did you learn that you might apply to your next team project?
I learned two lessons about team projects while working on a design project. The first is that written communication, as explained earlier, is very effective. I won't go into detail because I've already explained why it's effective.

As a second lesson, I learned that it is important to distinguish between what the team should do together and what it should do separately. When we all tried to do activities like brainstorming together, ideas didn't come out well due to the pressure of everyone being together. It was even more difficult because there was added pressure to make progress while we were together. I felt it was important for each person to consider in advance what they could do and do it in advance.

#### Through the team-based design project experience, what did you learn about the user-centered design process and UI prototyping?

I thought I would be left with some unexpected insight after the whole journey was over, but that wasn't the case. The words I learned throughout the class, “We are not users,” ultimately stayed in my mind. I kept hearing those words over and over again as problems that I didn't anticipate continued to arise.

## Individual Reflection - Sejun Jung
I played a key role in developing our prototype by contributing significantly to the logic, logo, and overall design structure. My responsibilities encompassed creating a user-friendly flow, designing an impactful logo, and deciding on the visual and structural layout of the interface. I organized the component structure and maintained the Figma environment to ensure easy access for team members, facilitating a smooth and efficient design process.
One of my primary focuses was on ensuring that our prototype was user-friendly. This involved designing intuitive navigation, clear and consistent visual elements, and ensuring that the overall flow of the application made sense from a user's perspective. I spent considerable time studying different settings and functions of Figma and applied these techniques to our project. By creating wireframes and interactive prototypes, I was able to iterate based on feedback from both the team and potential users.
Designing the logo and elemental figures was another crucial aspect of my role. I aimed to create a logo that was not only visually appealing but also conveyed the essence of our product. I used various plugins such as iconify, unsplash, material symbols to offer basic pictures and symbols that could be universally used in the project.
Deciding on the visual and structural layout of the interface required a holistic approach. I had to consider how each element would interact with others, ensuring consistency and coherence throughout the application. This involved creating a design system that included typography, color palettes, button styles, and other UI components. By maintaining a cohesive design system, we were able to ensure a consistent user experience across different parts of the application.
To facilitate collaboration and ensure that our design process was efficient, I organized the structure of the components in Figma. This involved setting up a clear hierarchy, naming conventions, and organizing layers and assets in a way that made it easy for team members to find and use them. By tidying up the Figma environment, I ensured that everyone could work more effectively and that our design files remained organized and manageable.
Communication was a strong suit for our team, helping us stay connected and informed throughout the project. However, we initially struggled with role definition, which led to decision-making inefficiencies. Without clear roles, it was challenging to make quick decisions, and this sometimes resulted in conflicts or duplicated efforts. Recognizing this issue, we took steps to define specific roles for each team member. By assigning clear responsibilities, we improved our efficiency and reduced conflict, ensuring a smoother workflow.
This experience taught me the importance of clearly defined roles in effective teamwork. When everyone knows their responsibilities and areas of expertise, it becomes easier to collaborate and make decisions. This not only improves efficiency but also fosters a more harmonious working environment.
Additionally, I learned the critical importance of accurately defining the problem before designing solutions. We spent time conducting user interviews to understand the needs and pain points of our target audience. These interviews provided valuable insights that directly influenced our design decisions. By adopting a user-centered approach, we were able to create a prototype that truly addressed the needs of our users.
User feedback was invaluable throughout the design process. It helped us identify areas for improvement and validate our design choices. We conducted usability tests and gathered feedback on various iterations of our prototype. This iterative process allowed us to refine our design and ensure that the final product was both functional and user-friendly.
In conclusion, my contributions to the logic, logo, and overall design structure of our prototype were crucial to the project's success. Through effective communication, role definition, and a user-centered approach, we were able to create a prototype that met the needs of our users and demonstrated the importance of teamwork and clear problem definition in design.


## Individual Reflection - Jiwoong Jang
I laid out the overall framework of the interface. Before creating a full-fledged prototype, I suggested the types of interfaces needed (payment window, permission window, payment completion window, main page, etc.). After that, I took charge of the design of the main page and completed it. In addition, I worked hard with team member Sejun to implement most of the functions. I created many components and variables and adjusted them so that they could be changed according to the situation. As a result, I was able to create alarm functions, changes in receipts, and changes in history.
I also created auto layouts and components for interfaces created by other team members. As team members divided up roles to create interfaces, there were often cases where there were multiple components with the same content or the formats did not match. I took the initiative to solve this, and unified the UI for history, back button, etc. In addition, during this process, I added them to places where auto layout was not processed, such as the family page and payment history.
In addition, I continuously accessed figma and made minor interface adjustments, such as the text interface in limit exceeding situations, adjusting the recognition size of each button, shading clickable buttons, and emphasizing or disemphasizing the text on each page.


Our team overall went smoothly. Each team member diligently performed their assigned roles and found and handled what they could do. In particular, the abilities required for team projects were distributed to each group member. The best part, I think, was the sharing of opinions within the team. All team members attended all meetings, shared opinions, and reached a single conclusion. However, the most difficult part of this process was scheduling meetings. Since we emphasized communication with all team members, we had to find a time when all four of us could work, which was difficult. I think this is because we tried too hard to gather the opinions of all team members. Therefore, in future team projects, we need to divide up roles a little more or reduce the number of meetings to manage time more efficiently.


I learned about the overall process of design. Each team member had an appropriate role and was able to experience creating one big result. Another thing I realized during the design process was the importance of listening to others, especially conducting user tests. I thought that great designers would be able to create great interfaces by thinking from the user’s perspective without having to conduct user tests. However, I found out that this is extremely difficult. I learned that users often deviate from designers’ assumptions. And sometimes, even among the designers have conflicts of opinion. Therefore, I learned that conducting many tests and listening to others’ voices can create better interfaces.

## Individual Reflection - Yeongseo Cho
I contributed and got charge of design and functions of family page. I also came up with design ideas with details, such as how to deliver time period of budgets or how to make buttons look unified. Plus, it was my job to make request details page. Here, I made several components to easily make the pages and make them look unified. After some user test and peer review, I found some critical problems of our interface and summarized how to fix them.

Since we couldn't find enough time for everyone to attend, we needed to proceed with the project as efficiently as possible. Through such efforts, I recognized the importance of dividing role. Due to lack of time, all of us could not focus on one job together. So we divided our roles and thus we could finish our project successfully. 
 However, one thing that is more important was not to lose focus on whole flow. Focusing only on the divided role would make the project irrelevant to each other. To prevent such situations, having time to talk each other’s progress and being interested in teammates’ work was helpful.

One thing that our team was exceptional was brainstorming. From the first brainstorm to decide our target user and POV, we had a lot of potential ideas.  Moreover, such abundant great thinkings also worked on making user-friendly interface. And I think that such good ideas could come from active communication and strong driving force of ours. Thanks to our teammates, we could find various reasonable approaches in limited time. 


In the sense of learning user-centered design, I realized that there is a big difference between the developer's perspective and the user's perspective. Since our target user was minor, I thought that I could think like users since I was once a minor. But user tests taught me the difference. Especially, I was impressed by the fact that a feature that was added without much thought turned out to be a huge advantage for one user during user test. Thanks to that user, we could deep into such advantage and improve our functionalities of prototype. 

Also, I could find the difference of our ideal target user and real user in target field. For example, I thought that since minor is our target, any minors could be our user. However, we could find a minor user without cellphone, which was not good environment to perform a prototype. Thus, I felt that having proper and good quality of user test is very important. 

Lastly, leaning systematic information and solution examples of usabilities was very helpful to find out solutions of user discomfort. Such content made me to think about type of usability first, which leads to more fast and effective solutions.


## Video link
https://youtu.be/GcGZyYSXSgY

Use YouTube subtitles for narration subtitles
