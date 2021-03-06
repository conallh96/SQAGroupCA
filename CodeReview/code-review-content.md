# Code Reviews
## Introduction  

**Code review** is a systematic examination of source code often from new features added by a dev team. The review is usually conducted by **peers** within the organization and is intended to **find and fix** mistakes often overlooked in the initial development stage, improving both the overall **quality of software** and the **skills of the developer**.

## Checklist 
While reviewing code made by you or your colleagues there are generally a few questions you can ask yourself about the code.

1. Is the code written following the **coding standards** and **guidelines**?
2. Am I able to **understand** the code easily?
3. Can I **unit test/ debug** the code easily to find the root cause?
4. Is the same code **duplicated** more than twice?
5. Is this function or class **too large**? If the answer is yes, is the function or class doing **too many things**?

![alt text](../Images/codeReviewImage1.png "An example of that need to be asked.")

If you find the answer is **yes** to any of the above questions then you can leave a comment with a suggestion of what to *alter* or *change*.

## What Makes A Good Checklist 
You might find yourself asking what makes a good checklist and what separates the good review checklists from the ineffective ones.

1. A **good** checklist helps the reviewers task move **much quicker** and review in a more **reliable** and **consistent** way by reducing the overall amount of information that the reviewer needs to remember in order to correctly analyse and **compare the findings** with the associated checklist. It focuses on **top-priority** issues and doesn’t exert the reviewer with too many tasks.

2. A **bad** checklist encourages **nitpicking** and creates an unhealthy relationship between colleagues which may be perceived in a condescending manner. It also can ignore the importance of **velocity**, and unintentionally **hinder the progress of the team**. If the checklist is **cumbersome**, **redundant** with other processes, or not **consistently applicable and relevant**, it can become a great **waste** of time, resources, authors and reviewers will tend to completely ignore without guilt or hesitation, feeding into an unhealthy atmosphere.

## Common Code Review Approaches 

- ### The Email Thread  
As soon as the code is ready for review, it is sent to colleagues via **email**. Although more flexible for the reviewers, an email thread full of different opinions can get **complex and confusing** for the original developer.

- ### Pair Programming 
This approach puts the developers side by side, checking each other's work as they go. It's an excellent way for **senior developers to mentor junior developers**. This method can be hard on resources requiring more time and personnel compared to other methods.

- ### Over The Shoulder 
This method involves a colleague sitting down at your workstation and **reviewing your code as you explain why you wrote it**. This is certainly a lightweight approach but can be **too light** in terms of tracking work and appropriate documentation.

- ### Tool Assisted 
Considered the **best method** for reviewing code as it uses software integrated into IDE and SCM development frameworks. This way everything can be tracked automatically, less resources required and no meetings needed.


- ### View other topics: 
* [Home Page](../README.md)
* [Code Review Bad Practices](/CodeReview/code-review-bad-practices.md)
* [Coding Standards](../CodingStandards/coding-standards-content.md)
* [Task Estimations](../TaskEstimation/TaskEstimation.md)


## References ## 
* [Gutha, R. (2015, August 31). Code Review checklist, to perform effective code reviews](https://www.evoketechnologies.com/blog/code-review-checklist-perform-effective-code-reviews/)

* [Avery, L. (2019, November 11). What belongs in an effective code review checklist](https://www.pullrequest.com/blog/what-belongs-in-an-effective-code-review-checklist/)

* [Smartbear. (2020, September 15). Common code review approaches](https://smartbear.com/learn/code-review/what-is-code-review/)







