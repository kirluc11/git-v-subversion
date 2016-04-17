# Git V Subversion
In this document, we will explain whatcVersion Control Systems (VCS) are and why they are needed for collaborative software projects.
We also included a comparison of the two most popular VCS, Git and Subversion (SVN).

## Why Version Control?
You need a VCS so you can go back to a previous working version of your project in case you mess up.
This is the single most important feature of any VCS.
For your private files, anyone of you has probably already done something like this:

![designers files](http://i.imgur.com/VbWttOp.jpg)

But for software development, this ~~isn't a good~~ is a terrible solution. Things can get messy pretty fast, and everything gets even more complicated when multiple developers join in.

This why we need a system to handle our revisions &mdash; a VCS.

### Use Cases
Altough nobody we know likes to talk about *Use Cases*, please excuse us for this one time. Here are the most important uses for a VCS.

#### Backup and Restore
We already mentionted this as the most important use and the very reason VCS were invented.
You can go to any moment in time you'd like to, it's all there. If used correctly, a VCS makes you never lose any of your precious code.

#### Finding Bugs
Whenever you change something about your project, your VCS will want you to provide a short description of what you did.
This, in combination with the ability to compare different versions of your code, brings you many benefits. For example, it makes easier for you to compare different versions and find out exactly when a certain unwanted feature was introduced.

<blockquote class="twitter-tweet" data-lang="de"><p lang="en" dir="ltr">99 little bugs in the code<br>99 little bugs in the code<br>Take one down, patch it around<br>117 little bugs in the code</p>&mdash; Alexander (@irqed) <a href="https://twitter.com/irqed/status/358212928404586498">19. Juli 2013</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

#### Different Versions
Not only does a VCS let you go back in time, but you can also can switch between different versions. Want to try something that could possibly break your code? You can use *Sandboxing*, testing your changes in a separate area.

##Sources
Stackoverflow answer: "Git is not better than Subversion" &mdash; <cite>http://stackoverflow.com/a/875/2167159</cite>

Git SCM Wiki: "GitGitSvnComparison" &mdash; <cite>https://git.wiki.kernel.org/index.php/GitSvnComparison</cite>

GitHub Help: "What are the differences between SVN and Git?" &mdash; <cite>https://help.github.com/articles/what-are-the-differences-between-svn-and-git</cite>

Tutorials Point: "SVN Basic Concepts" &mdash; <cite>http://www.tutorialspoint.com/svn/svn_basic_concepts.htm</cite>

Better Explained: "A Visual Guide to Version Control" &mdash; <cite>http://betterexplained.com/articles/a-visual-guide-to-version-control/</cite>

Tower: "Why Use a Version Control System?" &mdash; <cite>https://www.git-tower.com/learn/git/ebook/en/mac/basics/why-use-version-control</cite>

Stackoverflow answer "A Version Control System should make your Life easier" &mdash; <cite>http://stackoverflow.com/a/1408464/2167159</cite>

##Acronyms
| Abbreviation | Meaning                |
|--------------|------------------------|
| VCS          | Version Control System |
| SVN          | Subversion             |
