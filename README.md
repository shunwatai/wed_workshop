This is a readme file for wed workshop

git status to see what files created
.md for mark down, it is a feature for github for nice format on github website
after type "git status", then you can add it by "git add ."

"git commit" to commit the files you just "git add", this is for record down the changes the you add/modify on the repository after you commit, you will see the following:

    [master b433093] This is the first commit on the WED workshop
    1 file changed, 6 insertions(+)
    create mode 100644 README.md

The string after master is a sha1 hash value, you can type "git log" to check
create mode 644, for first 100 I dont know\n

Now, make some change on the README file and type "git status", see red, now
"git diff" to see the different before and after\n

After the second change, "git add README.md" and "git commit" again
Now you can try to "git push", type your uname and pw of github\n

Now you can "git log" to see all the commits history, also you can go to the
github website and move to that repository, then click the "commits" to see\n


Up to this point, it's the time to try "pull request", because the followin steps are github's functions, most of it done on the gui web page.\n

1. go to the webpage of the your friends repository, then find the "fork"
button to fork it to your github.\n
2. once you forked, git clone that repository in the command line first and
then make some changes, "git add", "git commit", "git push" to push back to
your forked repository.\n
3. now go back to the webpage of your github, click the "pull request" button
to make to request to your friend.\n
