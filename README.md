Sandbox
=======

A repo which is soley used for playing around and getting used to git. Please do not place any code
you want preserved into this repository, as it may be occasionally wiped. Also note that this repo uses
[The Unlicense](http://unlicense.org/), meaning any code inside of it is public domain, so don't push
your new game engine code to here.



##Helpful Links##
[The Pro Git book, one of the bibles of Git](http://git-scm.com/book)

[A nice intro to git, delivered as a blog post](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1)

[An overview of git commands from Atlassian](https://www.atlassian.com/git/tutorials/setting-up-a-repository)

[Useful aliases for your .gitconfig](http://durdn.com/blog/2012/11/22/must-have-git-aliases-advanced-examples/)

[An automated .gitignore generator](https://www.gitignore.io/)

[P4Merge, a top-tier tool for merging files](http://www.perforce.com/product/components/perforce-visual-merge-and-diff-tools)

[KDiff3, one of the best open-source mergetools](http://kdiff3.sourceforge.net/)

## General Tips & Tricks ##

*     Don't force push. Ever. -[Matt Bucci](https://github.com/mattbucci)
*     Write good commit messages. Messages like "did \*\*\*\*" or "broke it, fixed na0"
      might be cute to you now, but someone is going to want to murder you if they ever have to make
      a revision based off of 10 commit messages that say the same, noninformative thing. -[Robert Wang](https://github.com/rleewang)
*     Instead of doing waiting a long time between commits and pushes, commit really often when you
      code. Then, before you push, use a rebase to make it look like one giant commit. (Do not do this
      to a public repo if you don't know what you're doing. People may hate you for a very long time). -[Matt Bucci](https://github.com/mattbucci)
*     If you don't like the default CLI interface, [SourceTree](http://www.sourcetreeapp.com/) is an
       excellent app that offers you the full power of git (and Mercurial!) in a nice graphical package.
*     If you're a masochist and prefer the command line, make sure to create
      [pretty log aliases](https://stackoverflow.com/questions/1057564/pretty-git-branch-graphs)
      to get a better idea of what's going on with your project's history and lineage. -[Kevin Song](https://github.com/chipbuster)

##Suggested Activities##

####Beginner:####

*     If you're a true beginner, start by making a personal git repo and getting used to the flow of
       modify-stage-commit. Because git can be used to track anything, you can even use it to track things
       like essays! If you don't like where the essay ends up, just use `git checkout` to get back to the last
       version you liked and keep going. (This document was made using git as a version control)
       (IMPORTANT: If you do this, make sure you don't push your essay to a public repository before
       it's turned in! [Atlassian Bitbucket](https://bitbucket.org/) allows you to make a few private repos for free.
*     Once you have a feeling for simple things, do some bigger projects! Placing projects like the CSE 111
       (Databases) project into git serves two purposes: it lets you collaborate with people and it
       stops you from breaking your only working copy--you can always revert!

#### Intermediate: ####

*     Once you have the basics of git down, start playing with more advanced commands like bisect,
       blame, and cherry-pick. Collaborate with other people and learn how to do three-way merges with
       tools like [P4Merge](http://www.perforce.com/product/components/perforce-visual-merge-and-diff-tools)
       or [KDiff3](http://kdiff3.sourceforge.net/).
*      If you like to learn by playing games, Gazler's [githug](https://github.com/Gazler/githug) may be
        your style.


#### Advanced: ####

Unfortunately, we don't really have any advanced git users. If you get to this point, feel free to write
this section of the post!
