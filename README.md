# Powergit

*add + commit + push*

1. Adds all changed files in the current directory (including any subdirectories)
2. Commits the changes with the message following the command and...
3. Pushes the current branch!


## Install

    cd ~/bin
    curl -O https://raw.githubusercontent.com/jonatanblue/powergit/master/powergit
    chmod +x powergit


## Usage

    $ powergit "pushing straight to master for lulz"
    [master 41341bf] pushing straight to master for lulz
    1 file changed, 2 insertions(+), 1 deletion(-)
    Counting objects: 3, done.
    Delta compression using up to 4 threads.
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (3/3), 401 bytes | 0 bytes/s, done.
    Total 3 (delta 1), reused 0 (delta 0)
    remote: Resolving deltas: 100% (1/1), completed with 1 local objects.
    To git@github.com:jonatanblue/powergit.git
       a8a87b5..41341bf  master -> master


## Disclaimer

Use at your own risk. Always do `git status` and `git diff` first so you know what you're pushing.

