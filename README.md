Lab 7 

Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
- "Within a Github action that runs whenever code is pushed"
  - Putting automated tests into a Github action creates an infinite, constant line of tests that automatically run on every push without relying on someone to manually do it. For the Recipe project, if someone pushes a change that breaks one of the features, the Github actions will catch it before it's pushed to the real world. 

Expose - Checking for Understanding
-  Would you use an end to end test to check if a function is returning the correct output?
   -  NO!

Explore - Checking for Understanding
- What is the difference between navigation and snapshot mode?
  - Navigation mode analyzes a page right after it loads, providing an overall performance metric, but can't analyze interactions or changes in content. Snapshot mode analyzes a page in its current state, best used for finding accessibility issues (not performance). 
- Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
  - Add meta description
  - Use efficient cache lifetimes
  - Render blocking requests



