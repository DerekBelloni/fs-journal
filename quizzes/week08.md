# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The packege.json file holds all the relevant metadata for a project and handles the projects dependancies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json exists in the root directory of a node.js project. This is because it contains dependancies for the entire project.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Environment variables.
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
The two ways to view logs from your heroku app are the heroku cli and the dashboard.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
After pushing changes to github, login to your heroku, set your project to remote and push it to heroku as the main branch.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is important to version control because it allows for the testing of parallel code in handling either the same parts of the program, perhaps to see which branches methodology is better.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen after automated checks and testing but before merging to the main branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
The term used for combining two branches is merging.
```