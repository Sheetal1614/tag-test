# tag-test
understand the concept of tags in git.

A lightweight tag is very much like a branch that doesn’t change — it’s just a pointer to a specific commit.


Annotated tags, however, are stored as full objects in the Git database. 


The -m specifies a tagging message stored with the tag. If you don’t specify a message for an annotated tag, Git launches your editor so you can type it in.

In the “detached HEAD” state, if you make changes and then create a commit, 

wadasdsdsd


the tag will stay the same, but your new commit won’t belong to any branch and will be unreachable, except by the exact commit hash.