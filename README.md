# merge-me

Tool for CMs to automatically merge stale content work with neb.

## Dependencies
- git
- neb

# Installation
Just `git clone https://github.com/tomjw64/openstax-cm-merge-me.git` wherever you want to keep the tool.
To update: go to the cloned directory and `git fetch && git pull`

# Usage
`[DEBUG=true] [HUMAN=true] <path/to/merge-me> <path/to/collection_directory> <neb_env> <path/to/out_directory>`

You can be in any directory you want, and merge-me will work in a temp directory inside the current working directory, which will be cleaned up for you when the merge is complete.

To view the diff that `merge-me` found (via git) change directories to `out_directory` and compare the `mine` branch with the `theirs` branch. This can be done with `git diff theirs`. Please review this diff before ever publishing your changes.
