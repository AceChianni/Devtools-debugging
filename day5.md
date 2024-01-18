# Web Debugging and Optimization Exercise

## Overview

This exercise is designed to improve your skills in web debugging and optimization. You will be working with an intentionally flawed web application. Your task is to identify and document the problems in the provided HTML, CSS, and JavaScript files.

## Instructions

Copy this README.md into your Devtools REPO in a new MD file called Day-5.md

### Step 1: Identify Problems

Go through the provided files (`index.html`, `style.css`, and `app.js`). Each file contains several marked problems (indicated by comments like `<!-- Problem 1: -->`, `/* Problem 5: */`, etc.). Your task is to identify what each problem is and why it is an issue.

### Step 2: Document Each Problem

In this README.md file, document each problem. Write a sentence for each problem explaining what the issue is and why it's problematic. Use the format below for your documentation:

#### Problem 1:

- Missing Elements: Missing metadata and title in application

#### Problem 2:

- Image size: Large image without alt attribution

#### Problem 3:

- J Query: CDN library could cause issues

#### Problem 4:

- CSS Issues: Use of inline styling without tag

#### Problem 5:

- Key Words: important key word used too frequently

#### Problem 6:

- Unused Classes: classes are defined, but unused in the CSS or HTML

#### Problem 7:

- Image Size: Large size for small screen optimization without set sizes

#### Problem 8:

- Selectors: Overly specific selectors in code to select h2 container

#### Problem 9:

- Performance issues: DOM manipulation using for loops with the "data" object

#### Problem 10:

- Blocked Loop: loop is blocking and may cause unresponsiveness

#### Problem 11:

- JQuery Cont: Library used for entire body of code, mixing vanilla JS and J query

### Step 3: Propose Solutions

For each identified problem, propose a solution or an optimization strategy. Briefly describe how you would fix the issue.

#### Problem 1:

- Solution: [Your proposed solution here]

#### Problem 2:

- Solution: Add alt attribute to provide alternative text for image.

#### Problem 3:

- Solution: hosting jQuery locally or using another mechanism.

#### Problem 4:

- Solution: using a <style> tag or creating external CSS file

#### Problem 5:

- Solution: Remove unnecessary !important declarations.

#### Problem 6:

- Solution: Remove unused classes

#### Problem 7:

- Solution: Use max-width

#### Problem 8:

- Solution: Simplify selectors

#### Problem 9:

- Solution: creating specific iteration to filter out own properties

#### Problem 10:

- Solution: Using asynchronous operations

#### Problem 11:

- Solution: choose vanilla JavaScript or jQuery for DOM manipulation to maintain consistency

### Step 4: Reflect

After completing the exercise, I learned how to utilize lighthouse to help find bugs and issues within the code. It also reinforced some of the best practices when it comes to creating an optimized code for multiple devices.

## Submission

Submit this README.md file with all the problems documented and solved, along with your reflection. Ensure that your explanations are clear and concise.

---

This exercise is an opportunity to practice critical web development skills. Pay close attention to detail and think about how each issue affects the overall performance and user experience of the web application.
