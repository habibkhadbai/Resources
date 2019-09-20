# Resources


# List of Resources


# TakeAways from Learn-co
## Section 01 - Getting Started

There is a lot to learn about data science, but most of the time you're predicting a continuous value (regression), predicting a category (classification), identifying unusual data (anomaly detection) or generating recommendations.
Data science is not just about selecting and tuning machine learning models. Much of the value comes from understanding the business needs and formulating the problem thoughtfully. And most of the effort is in the early stages of finding, cleaning, exploring and simplifying the data so it's ready to be run against your models.
It's important to use professional tools. Jupyter Notebook is a great environment for combining your notes and your code. Git allows you to keep track of your changes. GitHub allows to share them with your team. Conda virtual environments ensure that the libraries you use for one project won't break another project you were working on.

## Section 02 - Git

### _Bash and the Command Line_ 
Recall some of our primary tools for navigating the command line: cd, ls, pwd, mkdir and nano. You can use cd .. to move up a directory level and cd ~/Documents for folders starting at the user's home directory. You can use ls -a to view hidden files and ls -la for a long listing of all files. (Again the l argument is for long form and the a in both cases for all files, including those beginning with . indicating that they are hidden.) You can also make directories with the mkdir command. You saw how to use nano to make and edit files from the command line. Other editors such as emacs and vim can be worthwhile if you are doing more substantial command line editing.

### _Git Background_
Remember that git was not only designed as a version control system, but a means for collaborative development. It was originally released in 2005 by Linus Torvalds, to help facilitate development of the Linux kernel. While there is still much to learn about git, you saw some of the primary concepts all developers interact with when using git to collaborate on projects.

### _Git Commands_
<li>You've seen a decent amount of git commands including git add, git commit, git branch, git checkout and git merge. Also very important is to know how to access documentation so that you can both review and extend your knowledge. For example, to see a list of git commands in general, start with git --help.</li>
You can then also review individual commands with 'git help ' such as git help add (Afterwards press q to quit the commands documentation.)
In the synopsis, you can see optional parameters such as in git add --all which you previously used before.
Similarly, for the commit documentation, take a look at git help commit (and subsequently use q to quit.)
Here, you might notice additional arguments that you can begin to use, such as a, which you see listed in the synopsis. Then, if you look under the options header, you will see a full description.
So for example, you could combine this with the m option as git commit -am "your commit message". (Indeed this is a useful shortcut; by doing this you can bypass the git add command in your workflow in updating files being tracked by git.)
At some point, you will also run into some trouble with git and have merge conflicts or other idiosyncrasies between versions of your code. You have seen how git annotates merge conflicts, and can also use git stash to temporarily store changes.