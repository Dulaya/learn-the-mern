### Homework: Write an article for this site.

This guide is mainly for members that are not familiar with the Git & GitHub workflow. 

0. If you don't have access to the [repo](https://github.com/Dulaya/learn-the-mern-client), message me your GitHub repo on Discord so I can invite you as collaborator.
1. Make sure you have [Git](https://git-scm.com/) and [Node.js](https://nodejs.org/en/) install on your computer. 
2. Clone the repo by running the command line: `git clone https://github.com/Dulaya/learn-the-mern-client.git`
3. After it finishes cloning, CD into the project directiory: `cd learn-the-mern-client`
4. Open the project folder with a code editor. If you use VSCode, you can use the command: `code .`
5. Install all the dependencies: `npm install` or `npm i`
6. Create a new branch by running the command: `git checkout -b [your-branch]` . 

Example: `git checkout -b arrow-function`

7. Open your assigned lesson (.md) under src > components > lessons and work on it. It's a markdown file, and you can use whatever tools available in the markdown that fit your needs. After you finish writing, save it. Don't worry too much about styling for now. Concentrate on writing a great content and use your own style.
8. Make sure your local clone is up to date with the most recent commits by runnning the command: `git pull`
9. (Optional) Check the status of your commit by running the command: `git status`
10. Add all the files by running the command: `git add .`
11. Make the commit by running the command: `git commit -m "your comment"` 

Example: `git commit -m "update arrow function lesson"`

12. Push your branch to the GitHub repo by running the command: `git push -u origin [your-branch]` (same name from step 6)

Example: `git push -u origin arrow-function`

13. Wait a few minutes (usually less than 3 minutes) for Netlify to automatically rebuild. Go to [https://learnthemern.com/lesson](https://learnthemern.com/lesson) to see your work live.