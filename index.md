# How I resolved the Github `index.md` file edit issue

## Issue Description :
I was following the instructions to edit index.md file under the guidelines of tutorial -'communicate using markdown' but the **Edit (✏️) button was inactive** in the Files Changed tab.

### Initial Confusion 
I tried to resolve it on my own by clicking in a loop from preview,code,raw file etc......but it was of no use then I went to search for issue.

#### Root Cause
It turns out that editing directly from a "pull request view or changed files option" does not allow file edits-even for repo owners.

##### Resolution Steps:
1.I navigated to the **main repository code view**.

2.Switched to the `start-markdown` branch(where the file exists).

3.Opened the `index.md` file **directly**.

4.The **Edit file (✏️)** button became active.

5.And as a proof I have written this edit.

###### Final Outcome
Editing the file directly from the correct branch outside the pull request allowed me to complete the step and continue the course.

Let's add an image. Include descriptive text in the square brackets. This text is read aloud for people using screen readers. It's also shown at times when your image doesn't display, such as when there's a poor connection. You can see the syntax for images below:
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
