# quick-git
My cheat sheet for the most common git operations.

**Create a repository in Github.com or Github enterprise, copy the clone URL**

**Clone the Git**
> git clone git@github.com:sleeperninja/quick-git.git

*As you make changes, you'll come to a breaking point where you want to **commit** a change*

**Check Git Status**
> git status

*This will list changed files, verify your edited files show here, then you can add the changes. I usually end up adding all by using an asterisk*

**Add all**
> git add *

*Or you can add a single file*

**Add a file**
> git add [filename]

*After you add files, it's a good idea to see that your changes took*
> git status

*Everythign should be green that you want in your commit. We're going to commit all changes, and add a meaningful message.*

**Commit changes**
> git commit -am "Updated Git cheat sheet"

*Once you've committed your changes, you can upload them to the git repository, assuming it's your repository.*

**Push changes to repository**
> git push