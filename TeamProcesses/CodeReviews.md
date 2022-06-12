# A pull request should:
1. have one or more corresponding tickets, linked properly.
2. have test code or have instructions on how to test the new code.
3. be considered an integral part of development process where you incorporate your team members' feedback, not just a formality where a cursory sign-off is done.

# When filing a pull request
1. You should be the first person to review your own PR. Before you file a PR, treat the work like someone else's and review your own code.
* Elaboration: Humans are often more critical of others. If you treat your PR like someone else's, then you're more likely to identify room for improvement.
2. Add supplementary comments wherever code comments are not enough.
* Elaboration: Some information should not be conveyed through code comments. For example, if you removed dead code, add a PR comment like "Removed dead code."
3. Expect multiple rounds/iterations of code reviews.
* Elaboration: Reviewers didn't get to spend as much as time as the filer, so expect them to have other thoughts as they get more familiar with your changes.
4. Don't take review comments personally. 
* Elaboration: Reviewers are not humiliating you but giving you constructive feedback to your code that will be merged to the code base that is collectively owned.

# When reviewing a pull request
1. Every team member should spend some time reviewing new pull requests every day.
* Elaboration: This reduces the turnaround time. Remember that what goes around comes around.
2. Every code base is collectively owned by the team that maintains it. Therefore, every reviewer is responsible for every PR, even if the reviewer didn't write a single line of code or refused to review the PR.
* Elaboration: It is not one person's responsibility. The filer, the reviewers, and the procrastinators who refused to review the PR are all equally responsible for merged PRs. If you don't review the PR properly, you're not doing your job.
4. Check three things: logic, performance, and style.
   1. Logic: Does the new code address the problem brought up in the ticket(s)?
   2. Performance: Is there better code that does the same work? For example, can you do it faster or with less memory or with less space?
   3. Style: Is the new code formatted the same way as existing code? Is the code easy to follow for developers with little context? Does it have proper variable names and comments that contribute to readability? Is it written in a sufficiently maintainable way that a future developer can make changes easily?
