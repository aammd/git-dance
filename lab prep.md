
Hi Everyone,

to prepare for our git learning experience, here are a few steps to complete first:

install git

install rstudio

register for a github account
RECOMMENDED: sign up for your 5 free private repos

configure git for ssh access


1. Pull the current changes from github right when I start, ensuring I am working from a clean copy of the code (e.g., no changes in any files)
2. Load the package and run the tests to be sure everything works before my changes:
    library(devtools)
    load_all()
    test()
3. If (2) is not successful, then figure out why and help fix the code/tests so it all works
4. Once tests pass, make the changes I want to make to R files, etc.
5. Write/modify test files that exercise my new code showing how it works and giving it both good and bad data to see it perform correctly
6. Run test() and re-iterate through steps (4-6) until all tests pass
7. Document code, run document() until all documentation errors are gone
8. git pull from the repo to be sure you still have the most recent copy.
   8a. If not, resolve any merge conflicts.
9. git commit final changes, and git push all changes to the remote repository
10. Check travis CI results to ensure build is still passing

