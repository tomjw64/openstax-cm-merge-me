# merge-me

Tool for CMs to automatically merge stale content work with neb.

## Dependencies
- git
- neb

# Usage
`[DEBUG=true] [HUMAN=true] <path/to/merge-me> <path/to/collection_directory> <neb_env> <path/to/out_directory>`

To view the diff that `merge-me` found (via git) change directories to `out_directory` and compare the `mine` branch with the `theirs` branch. Please review this diff before ever publishing your changes.