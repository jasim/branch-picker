# branch-picker

Super simple visual branch picker for git. Useful when you've got lots of branches.

### Usage

Run the script in your git repository, select a branch with j and k (or up down), hit enter to switch to it. Looks like this:

    Pick a branch
    > AddLogin
      SaveLocation
      master
    Use j/k and enter to select. '/' = search. 'm' = master. 'd' = delete. 'D' = force delete.

For bonus points, create a symlink somewhere in your path:

    cd /usr/bin
    ln -s /path/to/branch.rb br

Now you can run it by entering `br` (or whatever).
