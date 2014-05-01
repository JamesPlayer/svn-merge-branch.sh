svn-merge-branch.sh
====================

A shell script for quickly merging an SVN branch back into the trunk (with text prompts, a dry-run and warnings).

Compatible on all versions of subversion >= 1.0.0

##Installation
copy svn-merge-branch.sh to a folder that's included in your shell PATH environment variable e.g. /usr/local/bin

##Usage
```
    $ cd to/your/working/copy/
    $ svn-merge-branch.sh BRANCH_NAME
```
BRANCH_NAME - The name of the branch to be merged into the trunk e.g. style-tweaks;
