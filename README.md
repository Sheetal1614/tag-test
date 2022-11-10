# tag-test
understand the concept of tags in git.

A lightweight tag is very much like a branch that doesn’t change — it’s just a pointer to a specific commit.


Annotated tags, however, are stored as full objects in the Git database. They’re checksummed; contain the tagger name, email, and date; have a tagging message, and can be signed and verified with GNU Privacy Guard (GPG).

The -m specifies a tagging message, which is stored with the tag. If you don’t specify a message for an annotated tag, Git launches your editor so you can type it in.