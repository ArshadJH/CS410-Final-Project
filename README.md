# Proposal
Solo Project by Arshad Hussain
e-mail: ahj4@illinois.edu
Illinois ID: ahj4

I have chosen to work with the LiveDataLab website for this project. More specifically I plan to create a more user-friendly interface for this website so that students can have an easier time submitting their projects and waste less time with the arduous GitHub linking process. I also plan to add more documentation making it easier for students to access learning materials on this site, such as links to corresponding lectures.

I plan to primarily use JavaScript classes and functions for the sake of making website enhancements, most likely in React for the sake of this assignment. I will adhere to a component-based design as that will make the website easier to navigate for students because they can draw their attention to exclusively sections they need, and to make the development process easier on my end. I will also adhere to a principal of looking at past UX research on similar designs in order to make educated decisions on how to improve the user-interface.

In my final deliverable, I plan to use a metric-driven approach to prove that my design is an improvement over the current LiveDataLab implementation. Specifically, I will demonstrate how my mockup reduces clutter as compared to the current design and how this leads to faster response time from the user. Some metrics I plan to investigate included time to destination for a student and number of readable text items at any given point in time.

I plan to code my own mock website completely from scratch, with no link to the current LiveDataLab source code. This is due to the fact that editing a pre-existing publicly-facing website will incur several permissions and hosting issues.

I plan to use the JavaScript programming language for both the front-end and any back-end logic. Depending on available time and scope of tasks, I might use Python along with a Flask server to handle back-end operations, but I predict that this will be unlikely due to the time it takes to manage codebases in two different languages combined with the other academic/professional responsibilities I have.

The first step is a throrough analysis of the shortcomings of the current LiveDataLab website, I estimate this will take roughly 1 hour.
The second step is reading up on current UI/UX trends in the education space and mocking up a design as to what I want my final product to roughly look like, I estimate this will take roughly 3 hours.
The third step is coding a front-end for my website using a component/page-based design paradigm, I estimate this will take roughly 7 hours, largely due to the fact that I need to brush up on my JavaScript skills.
The fourth step is coding a back-end for my website to facilitate navigation on the front-end, I estimate this will also take roughly 7 hours.
The fifth and final step is a thorough comparison of my website and the current LiveDataLab website, which I will record various metrics for and display likely in PowerPoint format, I estimate this will take roughly 2 hours.

# Documentation
Website can be accessed at this link: https://1660200.playcode.io/

My website can be used by computer science students to easily submit code they have written for class projects. The intention of this website is to evade the complicated version control upload process that is currently in place, and allow students to simply copy/paste code which they may have written for grading, thus saving student time and worry. Personally, I have been in the position of finishing my projects for this class, but speding considerable time managing the version control steps for each project only for my submission to fail until after multiple retries, whereas any technologically literate student can use my website to submit their code in a matter of seconds and just a few clicks of a mouse. This website is designed to accomodate just one computer science course, and unlimited projects and code blocks for each project.

This software is implemented exclusively in the JavaScript programming language, specifically using the React Library. I used a component-based approach for easy organization, with each component representing one project, and that way the main class contains a list of projects in it's state representation and it can easily render all of these components similarly design-wise. My codebase is designed so that each 
