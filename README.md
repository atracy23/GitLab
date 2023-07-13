# Welcome to GitLab
- Release Manager: Micah Smith
- Developer 1: Angela Tracy
- Developer 2: Joseph Youskievicz
- Developer 3: Mishaela Pederson

---

## Current Task: Create "styles" branch
Now that we have some content in the form of a great quote from Albert Einstein, we will need to spice up the *index.html* page. We will accomplish this by creating a new branch, *styles*, and adding some formatting in the CSS file.

*Reminder: The steps in this exercise must be completed in order. Please do not proceed past the steps currently shown in this README.*

### Member Who Must Complete: Developer 3 - Mishaela

### Option 1: Use Git CLI
1. Open a new Terminal session in your local repository.
2. Pull the latest changes from origin with the command *git fetch*.
3. Create a new branch with the command *git checkout -b styles*.
4. Open *styles.css* in your preferred text editor or IDE and add some basic styles. Style the *blockquote* element and the page's background color.
5. Open *index.html* and add a *link* tag referencing *styles.css* to the *head* element.
6. The author attributed to the quote appears to be incorrect. It should, in fact, be attributed to Justin Bieber. Change the author's name in the *blockquote* element to show this.
7. Stage your changes with the command *git add .* (Remember to include the period!).
8. Commit your changes to your local repository with the command *git commit -m [Message]*. Include a message in quotes that summarizes the commit.
9. Push the commit to origin with the command *git push -u origin styles*.
10. Create a pull request in origin's *styles* branch.

### Option 2: Use GitHub Desktop
1. Under the *Current branch* tab, click the *New branch* button.
2. Enter the name of the new branch, *styles*, then click *Create branch*. GitHub Desktop will automatically switch to the new branch.
3. Open *styles.css* in your preferred text editor or IDE and add some basic styles. Style the *blockquote* element and the page's background color.
4. Open *index.html* and add a *link* tag referencing *styles.css* to the *head* element.
5. The author attributed to the quote appears to be incorrect. It should, in fact, be attributed to Justin Bieber. Change the author's name in the *blockquote* element to show this.
6. In GitHub Desktop, ensure that each file is staged by checking the box next to the file name.
7. Enter a Summary and Description of the commit in the bottom left corner.
8. Click *Commit to styles*.
9. Publish the new branch with your commit to origin by clicking *Publish branch* at the top.
10. Create a pull request in origin's *styles* branch.
