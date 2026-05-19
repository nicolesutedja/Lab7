# Lab 7
### Names: 
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
- Within a Github action that runs whenever code is pushed 
- Manually run them locally before pushing code
- Run them all after all development is completed
> Within a Github action that runs whenever code is pushed so that we can catch errors early on since it also depends on local storage data, we can ensure that errors are caught in a away that guarantees the browser environment is clean when tests are run.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
> No, we should use unit tests.

3) What is the difference between navigation and snapshot mode? 

The key difference between the navigation and snapshot mode is when each mode analyzes the page. Navigation mode analyzes the page right after it loads, providing an overall performance metric across categories like Performance, Accessibility, Best Practice, and SEO. However, it can analyze user interactions and content changes after the page loads. Snapshot mode analyzes the page in its current state. This makes it best for finding accessibility issues, but it cannot analyze the JS performance or changes to the DOM tree. Navigation mode is a better mode for measuring load performance, while snapshot mode is better for accessibility auditing at a specific moment. 




