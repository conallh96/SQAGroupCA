# Code Reviews #
## Introduction ## 

**Code review** is a systematic examination of source code often from new features added by a dev team. The review is usually conducted by **peers** within the organisation and is intended to **find and fix** mistakes often overlooked in the initial development stage, improving both the overall **quality of software** and the **skills of the developer**.

## Checklist ##
While reviewing code made by you or your colleagues there are generally a few questions you can ask yourself about the code.

1. Is the code written following the **coding standards** and **guidelines**?
2. Am I able to **understand** the code easily?
3. Can I **unit test/ debug** the code easily to find the root cause?
4. Is the same code **duplicated** more than twice?
5. Is this function or class **too large**? If the answer is yes, is the function or class doing **too many things**?

![alt text](https://i0.wp.com/d331tpl5vusgqa.cloudfront.net/wp-content/uploads/2015/08/Experienced-Code-Reviewer.png?ssl=1 "An example of that need to be asked.")

If you find the answer is **yes** to any of the above questions then you can leave a comment with a suggestion of what to *alter* or *change*.

## What Makes A Good Checklist ##
You might find yourself asking what makes a good checklist and what separates the good review checklists from the ineffective ones.

1. A **good** checklist helps the reviewers task move **much quicker** and review in a more **reliable** and **consistent** way by reducing the overall amount of information that the reviewer needs to remember in order to correctly anaylse and **compare the findings** with the associated checklist. It focuses on **top-priority** issues and doesn’t exert the reviewer with too many tasks.

2. A **bad** checklist encourages **nitpicking** and creates an unhealthy relationship between colleagues which may be percieved in a condescending manner. It also can ignore the importance of **velocity**, and unintentionally **hinder the progress of the team**. If the checklist is **cumbersome**, **redundant** with other processes, or not **consistently applicable and relevant**, it can become a great **waste** of time, resources, authors and reviewers will tend to completely ignore without guilt or hesitation, feeding into an unhealthy atmosphere.

## Common Code Review Approaches ##

### The Email Thread ### 
As soon as the code is ready for review, it is sent to colleageus via **email**. Although more flexible for the reviewers, an email thread full of different opinions can get **complex and confusing** for the original developer.

### Pair Programming ###
This approach puts the developers side by side, checking eachothers work as they go. It's an excellent way for **senior developers to mentor junior developers**. This method can be hard on resources requiring more time and personnel compared to other methods.

### Over The Shoulder ###
This method involves a colleague sitting down at your workstation and **reviewing your code as you explain why you wrote it**. This is certainly a lightweight approach but can be **too light** in terms of tracking work and appropriate documentation.

### Tool Assisted ###
Considered the **best method** for reviewing code as it uses software integrated into IDE and SCM development frameworks. This way everything can be tracked automatically, less resources required and no meetings needed.

## Bad Practices
While Code Reviews can be a good opportunity to fix or improve a product as well as improve the skills of the developer, they can often create negative relationships between developers and their seniors due to adoption of some common bad practices. Senior members of development teams often use Code Review to impose unrealistic demands and this can result in frustrated developers and decreased productivity.

### Reviewer Inconsistency
When submitting a piece of code for review, a developer's work is subject to the review of a number of members of the development team. If there is no agreed upon approach to code reviewing, for example a checklist, reviewers can often give feedback with contradicting views and suggestions that result in the developer running back and forth to refactor code to meet each reviewers specofic desired style or standard.
For example, a developer may implement a new feature available in the Java library that allows them to complete a task with much fewer lines of code. This work may be praised by some more forward thinking developers however a less up to speed or perhaps more traditional developer may consider it unclear or over complex. Receiver differing feedback and suggestions due to no fixed coding standard and review process will lead to the developer being uncertain of their work and frustrated wth their progress.

### Overwhelming Feedback
When giving negative feedback, it is important to present it in a fair and contructive way in order to avoid overhelming team members and harming their confidence. Some reviewers tend to spend the reviewing process flagging every instance of every error, leaving copious amounts of comments criticizing the developer's work. This creates a tense environment in within the team which can easily be avoided by taking a more constructive approach to reviewing the piece of code. If there is an error in the developer's work, it is likely it will be repeated a number o fti mes as they thougt it was an appropriate way to complete the task. A clear and concise explaination of the error and how to solve it in the place of the first instance will allow the developer to undertsand and learn from the issue rather than bog them down with criticism. This will enable the code reviewing process to create a  positive environment of education and improvement rather than one of tension and negativity.

## References ## 
* Gutha, R. (2015, August 31). Code Review checklist, to perform effective code reviews. Retrieved March 29, 2021, from https://www.evoketechnologies.com/blog/code-review-checklist-perform-effective-code-reviews/

* Avery, L. (2019, November 11). What belongs in an effective code review checklist. Retrieved March 30, 2021, from https://www.pullrequest.com/blog/what-belongs-in-an-effective-code-review-checklist/

* Smartbear. (2020, September 15). Common code review approaches. Retrieved March 30, 2021, from https://smartbear.com/learn/code-review/what-is-code-review/

* Schults, C. (2019, January 08). The 4 code review practices that make devs quit - submain blog. Retrieved March 31, 2021, from https://blog.submain.com/code-review-practices/

* Sankarram, S. (2018, April 29). Unlearning toxic behaviors in a code review culture. Retrieved March 31, 2021, from https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c



