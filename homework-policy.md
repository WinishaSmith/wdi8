# Homework

## Things to note

- We want to be able to give you some flexibility in your homework schedule.

- There will be roughly 2 hours of homework per night. Homework will take more time for some, and less time for others. It is up to you how you want to partition your time for a given exercise.

- Please read the [Incentives](incentives.md) for completing your homework on-time!

- Turn in **something**. Turning in an incomplete assignment is **infinitely** better than turning in nothing at all. We can't get you the help you need unless we see what you're working on. That said...

- (I'd suggest that we remove this bullet - seems to conflict with other items here and it might cause confusion. I'd prefer to stick to a rule and go with it.) Ultimately *you* decide what is the best investment of your time and energy. Historically, the most successful students have completed most or all of the assignments. However, if you're feeling overwhelmed, it may be a better investment of your time and energy to take a night off from homework. In fact, we may encourage you to do so.

- **Late homework will not be accepted**. If you have issues submitting homework please let us know.

- You can track your homework completion rate in [Garnet](http://garnet.wdidc.org).

## Due Dates and Grading

- You will generally be assigned homework every day. It will **all** be due **Thursday morning at 9:00am**.

- Unless otherwise directed, each assignment should be forked and cloned from a `ga-wdi-exercises` repository, and submitted as a pull request to the original `ga-wdi-exercises` repository from your fork. For more information on pull requests, see below.

- Each week, **one assignment and the lab** will be reviewed and commented upon by your squad instructor.

- The other assignments will be checked only for *meaningful progress* -- that is: you made an effort to complete it, regardless of whether you were successful. These will be checked by **Robin**. In general, feedback will not be given on these assignments by the grading instructor unless you specifically request it.

## What to include with your submission

On **every submission** -- that is, on every pull request (or, sometimes, issue) -- please include:
- **Comfort score**, out of 5
- **Completeness score**, out of 5
- Any comments

### In order to get feedback on your assignment...

...when submitting your pull request or issue, please...

- Ask specific questions, **ending them with a question mark**. We grade *lots* of assignments, and we rely on questions marks to provide a visual queue that we should stop and address something!

  For example:

  > Any thoughts as to why the method on line 49 kept returning 'NaN'?

- If you'd like feedback or an answer to a question from an instructor *other* than the one assigned to check your submission, please include their first name. This will send them an e-mail notification. Without this notification, they will have no way of knowing you asked a question.

  For example:

  > Jesse: On line 85 of `script.js`, is this what you meant by making it an instance method?

## The submission process

All homework assignments will have their own Github repository, under the `ga-wdi-exercises` account.

1. Please **fork** new assignments.
2. Then, **clone** your fork to your computer.
3. Create a feature branch in the format of `yourname_solution`.
4. Complete your work inside it.
5. Then, **push** your completed work to your forked repository.
6. Finally, make a **pull request** to the upstream repository (in `ga-dc`).

For example, the sequence of commands you might follow to complete the above process is:

```
# Click grey 'Fork' button on Github
js1989: ~/wdi $ git clone git@github.com:js1989/homeworkaroo.git
js1989: ~/wdi/homeworkaroo $ cd homeworkaroo
js1989: ~/wdi/homeworkaroo (master) $ git checkout -b johnsmith_solution
js1989: ~/wdi/homeworkaroo (johnsmith_solution) $ touch did_my_homework.txt
js1989: ~/wdi/homeworkaroo (johnsmith_solution *) $ git add did_my_homework.txt
js1989: ~/wdi/homeworkaroo (johnsmith_solution +) $ git commit -m "Added did_hw file. All done!"
js1989: ~/wdi/homeworkaroo (johnsmith_solution) $ git push origin johnsmith_solution
# Click green 'Pull Request' button on Github
```
