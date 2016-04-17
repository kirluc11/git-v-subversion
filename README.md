# Git V Subversion
In this document, we will explain whatcVersion Control Systems (VCS) are and why they are needed for collaborative software projects.
We also included a comparison of the two most popular VCS, Git and Subversion (SVN).

## Why Version Control?
You need a VCS so you can go back to a previous working version of your project in case you mess up.
This is the single most important feature of any VCS.
For your private files, everyone of you has most likely already done something like this:

![designers files](http://i.imgur.com/VbWttOp.jpg)

But for software development, this ~~isn't a good~~ is a terrible solution. Things can get messy pretty fast, and everything gets even more complicated when multiple developers join in.

This why we need a system to handle our revisions &mdash; a VCS.

### Use Cases
Altough nobody we know likes to talk about *Use Cases*, please excuse us for this one time.

Here are the most important uses for a VCS.

#### Backup and Restore
We already mentionted this as the most important use and the very reason VCS were invented.
You can go to any moment in time you'd like to, it's all there. If used correctly, a VCS makes you never lose any of your precious code.

#### Finding Bugs
Whenever you change something about your project, your VCS will want you to provide a short description of what you did.
This, in combination with the ability to compare different versions of your code, brings you many benefits. For example, it makes easier for you to compare different versions and find out exactly when a certain unwanted feature was introduced.

<blockquote><p>99 little bugs in the code<br>99 little bugs in the code<br>Take one down, patch it around<br>117 little bugs in the code</p>&mdash; Alexander (@irqed) <a href="https://twitter.com/irqed/status/358212928404586498">19. Juli 2013</a></blockquote>

#### Different Versions
Not only does a VCS let you go back in time, but you can also can switch between different versions. Want to try something that could possibly break your code? You can use *Sandboxing*, testing your changes in a separate area.

#### Collaboration
Using a VCS everyone on your team can work on every file at the same time. Later, the VCS lets you merge the files together. In contrast, if you used a shared folder instead, this would not be possible.

#### Statistics
When using a VCS, every change is documented, which leads to nice side effects. For example, you can analyze how many lines in the source were modified by which team member, or at which time of the day the most changes were made.
When combined with data visualization, some very interesting things can be done.

For example, look at [this visualization](http://ghv.artzub.com/#repo=PizzaWebshop&climit=1000&user=thekaindorfcompany&run) of our previous [PizzaWebshop Project](https://github.com/TheKaindorfCompany/PizzaWebshop).

## Which VCS are there?

This article will focus on Git and SVN, altough there are also other VCS worth noting, such as Mercurial or CVS.

### Centralized vs Distributed
<blockquote>
<p>There are many version control systems out there. Often they are divided into two groups:<br>“centralized” and “distributed”.</p>
&mdash; Giancarlo Lionetti <a href="http://blogs.atlassian.com/2012/02/version-control-centralized-dvcs">14. February 2012</a>
</blockquote>

#### Centralized VCS (CVCS)
When using a CVCS, you have one central copy of you code base on a server. All changes will affect this central copy directly.
Every programmer probably does the following steps when working with a CVCS.

1. pull changes from the central server
2. make own changes
3. commit changes to the central server

Easy enough, right?

#### Distributed VCS (DVCS)
DVCS are the younger kind of VCS. They don't rely on one central version, but every developer has the full project, including its history, on their hard drive. But a DVCS ~~can~~ most likely will still have a central repository. Your workflow when using a DVCS could look something like this.

1. *pull or clone from any repository* &mdash; optional
2. make own changes
3. commit changes to the local repository
4. *push to any repository* &mdash; optional

## Sources
Stackoverflow answer: "Git is not better than Subversion" &mdash; <cite>http://stackoverflow.com/a/875/2167159</cite>

Git SCM Wiki: "GitSvnComparison" &mdash; <cite>https://git.wiki.kernel.org/index.php/GitSvnComparison</cite>

GitHub Help: "What are the differences between SVN and Git?" &mdash; <cite>https://help.github.com/articles/what-are-the-differences-between-svn-and-git</cite>

Tutorials Point: "SVN Basic Concepts" &mdash; <cite>http://www.tutorialspoint.com/svn/svn_basic_concepts.htm</cite>

Better Explained: "A Visual Guide to Version Control" &mdash; <cite>http://betterexplained.com/articles/a-visual-guide-to-version-control/</cite>

Tower: "Why Use a Version Control System?" &mdash; <cite>https://www.git-tower.com/learn/git/ebook/en/mac/basics/why-use-version-control</cite>

Stackoverflow answer "A Version Control System should make your Life easier" &mdash; <cite>http://stackoverflow.com/a/1408464/2167159</cite>

Atlassian: "What is Version Control: Centralized vs. DVCS" &mdash; <cite>http://blogs.atlassian.com/2012/02/version-control-centralized-dvcs</cite>

## Acronyms
| Abbreviation | Meaning                |
|--------------|------------------------|
| VCS          | Version Control System |
| SVN          | Subversion             |


