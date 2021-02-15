Backend Javascript Developer Exercise
=====================================

This exercise is designed to assess your skills and to see how you solve problems. Please don't spend more than 3 hours working on it, and if you have trouble completing it in that time, don't stress about it - just push up whatever you have.  There is no right answer here, and work-in-progress code is fine, as long as you can explain what you were working on during the interview.

We're expecting that many of you will not have worked with Cypress before - that's fine. You will probably want to start with [the docs](https://docs.cypress.io/guides/core-concepts/introduction-to-cypress.html), or see [the examples](./cypress/integration/examples).

Thanks, and good luck!

Instructions
------------

1. Read "The Exercise" below.
2. Clone this repository down locally, and perform the exercise.
3. Push your work up to a new, private repository in your own Github account.
4. At some point before your interview, give the Github user [`lastcall-automation`](https://github.com/lastcall-automation) read access to your repository.

The Exercise
------------

Last Call Media's [website](https://lastcallmedia.com) breaks every time we push code to it!  We want your help to add some tests to help us automate some basic quality control tests. What's breaking is:

* The "More Entries" button on https://lastcallmedia.com/blog sometimes fails to load additional blog posts onto the page when it is clicked. We would like to verify that the "More Entries" button loads additional posts onto the page when it is clicked.
* The contact form on https://lastcallmedia.com/contact sometimes allows users to submit the contact form without filling out the CAPTCHA. We would like to verify that the form **cannot** be submitted without solving the CAPTCHA (note: no need to actually perform a successful submission here ;)).

Stretch goal:
* Google Analytics sometimes fails to capture the pageview event when visitors use our site. We would lke to verify that the event is being sent.

We've heard a lot about this really great tool called [Cypress](https://www.cypress.io/), and we'd like you to use it to help us develop these tests. We've created this repository to help you get started. Please write some Cypress tests for us. The tests will be run from our local machines, and should target the production site (https://lastcallmedia.com).

To get started, run:

```
npm install
npm run cypress:open
```

