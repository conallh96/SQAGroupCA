# Code Reviews #
## Introduction ## 

**Code review** is a systematic examination of source code often from new features added by a dev team. The review is usually conducted by **peers** within the organisation and is intended to **find and fix** mistakes often overlooked in the initial development stage, improving both the overall **quality of software** and the **skills of the developer**.

## Checklist ##
While reviewing code made by you or your colleagues there are generally a few questions you can ask yourself about the code.

1. Am I able to **understand** the code easily?
2. Is the code written following the **coding standards** and **guidelines**?
3. Is the same code **duplicated** more than twice?
4. Can I **unit test/ debug** the code easily to find the root cause?
5. Is this function or class **too big**? If yes, is the function or class doing **too much**?

![alt text](https://i0.wp.com/d331tpl5vusgqa.cloudfront.net/wp-content/uploads/2015/08/Experienced-Code-Reviewer.png?ssl=1 "An example of that need to be asked.")

If you find the answer is **yes** to any of the above questions then you can leave a comment with a suggestion of what to *alter* or *change*.

## What Makes A Good Checklist ##
You might find yourself asking what makes a good checklist and what separates the good review checklists from the ineffective ones.

1. A **good** checklist helps the reviewers task move **much quicker** and review in a more **reliable** and **consistent** way by reducing the overall amount of information that the reviewer needs to remember in order to correctly anaylse and **compare the findings** with the associated checklist. It focuses on **top-priority** issues and doesn’t exert the reviewer with too many tasks.

2. A **bad** checklist encourages **nitpicking** and creates an unhealthy relationship between colleagues which may be percieved in a condescending manner. It also can ignore the importance of **velocity**, and unintentionally **hinder the progress of the team**. If the checklist is **cumbersome**, **redundant** with other processes, or not **consistently applicable and relevant**, it can become a great **waste** of time, resources, authors and reviewers will tend to completely ignore without guilt or hesitation, feeding into an unhealthy atmosphere.

## Common Code Review Approaches ##

1. ### The Email Thread ### 
As soon as the code is ready for review, it is sent to colleageus via **email**. Although more flexible for the reviewers, an email thread full of different opinions can get **complex and confusing** for the original developer.

2. **Pair Programming**
This approach puts the developers side by side, checking eachothers work as they go. It's an excellent way for **senior developers to mentor junior developers**. This method can be hard on resources requiring more time and personnel compared to other methods.

3. **Over The Shoulder**
This method involves a colleague sitting down at your workstation and **reviewing your code as you explain why you wrote it**. This is certainly a lightweight approach but can be **too light** in terms of tracking work and appropriate documentation.

4. **Tool Assisted**
Considered the **best method** for reviewing code as it uses software integrated into IDE and SCM development frameworks. This way everything can be tracked automatically, less resources required and no meetings needed.

## References ## 
* Gutha, R. (2015, August 31). Code Review checklist, to perform effective code reviews. Retrieved March 29, 2021, from https://www.evoketechnologies.com/blog/code-review-checklist-perform-effective-code-reviews/

* Avery, L. (2019, November 11). What belongs in an effective code review checklist. Retrieved March 30, 2021, from https://www.pullrequest.com/blog/what-belongs-in-an-effective-code-review-checklist/

* Smartbear. (2020, September 15). Common code review approaches. Retrieved March 30, 2021, from https://smartbear.com/learn/code-review/what-is-code-review/



