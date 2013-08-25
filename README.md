Linux Australia Constitution and Policies
=========================================

This holds the definitive copy of the Linux Australia Constitution and 
policies.

All constitutional changes will be created on branches and then moved into
the master branch after they have been voted on. Each motion at the AGM or SGM
should be created as a single commit (Hint. Use rebase a lot!). Every time 
changes are made to be submitted to Fair Trading a version should be tagged.

Policies are created and approved by the council but pull requests are welcome for
discussion.

The motions that go to the email list should be generated by using git log to
show the commit message and

    git diff -r reva..revb --word-diff=plain to show the differences
