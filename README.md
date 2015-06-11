This is a readme file for wed workshop(10-June-2015) about how to use github

The following first 3 steps done on the github web interface:

1. Create a repository on your github webpage
2. then you click that repository on the webpage
3. copy that URL of the repository

The following steps done on your local machine

4. open a terminal
5. type "git clone <repoURL>"
6. cd to the directory that you just cloned
7. now you can modified the source code, or add some new files.
8. type "git status" to see the changes, you will see the new file(s) in "red"
colour. Then you can type "git diff" to see the difference before and after
9. now, type "git add <files>"(specific files) or "git add ."(all files)
10. type "git status", now you will see the file(s) in green colour.
11. After added the files, you need to commit what you have done, the commit
function is used to record down the history of the changes like a log,
12. so type "git commit", a commit file will pop out by VI editor, you may just
type what you did, and the ":wq" to exit the VI
13. type "git log" to see the committed history
14. After all the steps above, you can now type "git push" to update the
repository on github, it will require you to enter your username and password
15. go back to the web browser and see the "push" success or not

More details about "git status, commit, log, diff":
"git status" to see what files created/deleted/modified.

.md stand for markdown, it is a feature for github for nice format on github website
For more details, google "github markdown syntax"

"git commit" to commit the files you just "git add", this is for record down the changes the you add/modify on the repository after you commit, you will see the following:

    [master b433093] This is the first commit on the WED workshop
    1 file changed, 6 insertions(+)
    create mode 100644 README.md

The string after master is a sha1 hash value, you can type "git log" to check
create mode 644, for first 100 I dont know

Now, make some change on the README file and type "git status", see red, now
"git diff" to see the different before and after

After the second change, "git add README.md" and "git commit" again
Now you can try to "git push", type your uname and pw of github

Now you can "git log" to see all the commits history, also you can go to the
github website and move to that repository, then click the "commits" to see



Pull request:
Up to this point, it's the time to try "pull request", because the followin steps are github's functions, most of it done on the gui web page.

1. go to the webpage of the your friends repository, then find the "fork"
button to fork it to your github.
2. once you forked, you will see that forked repository on your github page,
now git clone that repository in the command line first and
then make some changes, "git add", "git commit", "git push" to push back to
your forked repository.
3. now go back to the webpage of your github, click the "pull request" button
to make the request to your friend.

The following are for you friend to do:

4. your friend should receive the your "pull request".
5. he/she should first clone your modified cloned repository on his/her local
machine, then build/complie it to test it.
6. if he/she is satisfied your changes, then he/she can accept your pull
request by click the "merge" button on the github web interface to finish the
"pull" process


