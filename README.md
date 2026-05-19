# Lab 7

Names: Nicole Sutedja and Kaley Chung

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
- Within a Github action that runs whenever code is pushed 
- Manually run them locally before pushing code
- Run them all after all development is completed
> Within a Github action that runs whenever code is pushed so that we can catch errors early on since it also depends on local storage data, we can ensure that errors are caught in a away that guarantees the browser environment is clean when tests are run.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
> No, we should use unit tests.

3) What is the difference between navigation and snapshot mode? 
> The key difference between Navigation mode and Snapshot mode is when each mode analyzes the page and what each is best suited for. Navigation mode analyzes the page immediately after it loads and provides performance metrics across categories. However, it cannot analyze user interactions and content changes after the initial load. Snapshot mode analyzes the page in its current state, making it useful for identifying accessibility issues at a specific moment. However, it cannot analyze the JS performance or changes to the DOM tree. In other words, Navigation mode is best for evaluating page load performance, while Snapshot  mode is best for evaluating the page at a specific moment in time. 

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
- Reducing unused JavaScript to improve page load performance 
- Adding a lang attribute to the <html> element to improve accessibility 
- Adding a meta description to improve SEO 




