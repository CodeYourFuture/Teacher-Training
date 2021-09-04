# Marking Coursework

## Overview

Every week, our students complete coursework which aims to 

* Put what they've learnt into practice
* Stretch their abilities 
* Display progress in their learning

Each week's coursework consists of 

* Reading 
* Watching videos, either
  * Explainers
  * Introductions, or
  * Code Alongs
* Coding Exercises

and

* Coding Challenges

At the end of each week, students submit homework these challenges and we give feedback on them. **This feedback is a vital part of our students development.**

## **Technical Mentorship: Process**

### **1\) Finding Coursework**

Coursework including code is always hosted as a Pull Request on GitHub. 

Every week of the course has some coursework attached to it. Students open a pull request and unit tests are run. You might want to set up [code review assignment](https://docs.github.com/en/organizations/organizing-members-into-teams/managing-code-review-assignment-for-your-team) system in your buddy team.  
  
[Where do students submit coursework?](marking-coursework.md#where-do-students-submit-coursework)

You can find all of a students open pull requests by using  
  
[https://github.com/pulls?q=is%3Apr+is%3Aopen+author%3A](https://github.com/pulls?q=is%3Apr+is%3Aopen+author%3AChrisOwen101)${author}

And you can fetch from the [GH Search API](https://docs.github.com/en/rest/reference/search) like this if you want to set up a notification:

[https://api.github.com/search/issues?q=is:pr+repo:CodeYourFuture/${repo}/+author:${author}\`](https://api.github.com/search/issues?q=is:pr+repo:CodeYourFuture/${repo}/+author:${author}`)

```text
Exercise 1 (5 minutes)

Can you find the homework from these students? 

1) Git Week 1 - Chris Owen
2) All of ChrisOwen101's open pull requests
```

### **2\) Giving Feedback**

**Be Positive**

Above all else be positive and be kind. Our trainees want to learn and want to understand.

You should pull out small wins from bad code and encourage them to continue and try again. Many of our trainees suffer from low confidence and a well timed comment of motivation can be all it takes to push them to success.

If in doubt, consult our [key rules](/volunteers/education/teaching-tips#the-rules).

**Directing to Resources**

If you can tell that someone has been struggling with a particular area of the homework one key way that you can help is to

1. Acknowledge that they have struggled
2. Re-assure them that many people struggle with such problems
3. Direct them to an online resource that will help them understand the problem better

We should try to shy away from writing long, complex explanations to trainee problems. This can be a time sink, especially when great resources already exist. Try to spend as much time directly interacting with your trainees as you can. In other words: **talk to them.**

_Please note_: Do not just link to documentation! Link to a tutorial or guide that explains the documentation.

**Fixing Bugs**

If the bug is a simple compilation or formatting error it's perfectly fine to suggest a line fix to the issue. For example, an incorrect relative URL is a simple error that does not imply a deeper misunderstanding of the content and so can be safely fixed.

**Prompting to Ask Questions**

Make every error a teaching moment, mention that you see other people struggling with the same concepts and that asking questions on Slack can be a way to remedy their problems.

**Explaining an Obvious Mental Model Issue**

When a trainee implements code in a way that seems nonsensical the root cause can often be a misconception in how they have built their [mental model](https://teachtogether.tech/#s:models). If you can obviously tell from their homework what their misunderstanding is then you are encouraged to correct them.

If they seem to fundamentally misunderstand a concept then it is best to refer them back to the source material.

**Formatting**

It never hurts to remind the trainee of the importance of proper formatting and indentation. They should have [Prettier](https://prettier.io/docs/en/editors.html) installed in VSCode.

All code that our trainees write should follow our[ Style Guide](https://syllabus.codeyourfuture.io/guides/code-style-guide). It's ok to remind them to self review this. 

#### Quickly Giving Feedback

**Visual Studio Github Plug-in**

The VS Code studio plug-in can help speed up moving between pull requests and making comments.

[https://github.com/microsoft/vscode-pull-request-github](https://github.com/microsoft/vscode-pull-request-github)

It allows you to make comments from directly inside and VS Code and allows each comparison between Pull Requests.

#### Use the Code Review tools directly on Github

Do code review directly in Github using [the PR tools](https://docs.github.com/en/github/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request). This is an important skill to demonstrate to your trainees and a good one to develop yourself if you haven't done this much yourself. There's more [stuff in the main docs ](https://docs.codeyourfuture.io/teams/education/homework-feedback)around this, and you might find this useful: [Google Code Review](https://google.github.io/eng-practices/review/reviewer/speed.html) Guide.

### **3\) Grading Coursework**

It is important that we track how well someone is doing on the course, so we can support each person as an individual and respond effectively to their challenges. This can happen in a variety of places, but there should be one Single Source of Truth \(SSOT\).

* Class Tracking Spreadsheet
* Google Classroom
* Trello Cards

Please check in with your team to find out where their SSOT is and how best to update it.

If you'd like to do more intensive marking with your trainees, there is further reading here:

{% embed url="https://syllabus.codeyourfuture.io/guides/marking-guide" %}



### **4\) Label the Pull Request**

When you have given feedback it is important you add the label "_**reviewed**_".

If the homework has not been completed you should also add the tag "_**not-completed**_" 

### **5\) Tracking progress**

It is important to track our students in one central location, so information doesn't get lost and so we can see who needs help and with what. Most commonly, you will do this in a Google Spreadsheet. 

Please consult your team as each school approaches this differently.

## Where do students submit coursework?

The most reliable place to find the coursework for each week is on the relevant homework page for each lesson. For example, this is the first lesson for HTML/CSS

[https://syllabus.codeyourfuture.io/html-css/week-1/lesson](https://syllabus.codeyourfuture.io/html-css/week-1/lesson)

And here is the relevant coursework

[https://syllabus.codeyourfuture.io/html-css/week-1/homework](https://syllabus.codeyourfuture.io/html-css/week-1/homework)



