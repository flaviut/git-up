# git-up
To install, download the script on your path, rename it to `git-up`
and `chmod +x git-up`.

Usage is `git up <remote> [params]`. It iterates through all the the
branches that exist on both local and the remote, and does `git rebase
$params $remote/$branch $branch`. Really simple.

Dependencies are GNU Coreutils and git. Running linux? You'll have
them both installed.

I wanted something like [git up](http://aanandprasad.com/git-up/), but
then realized that it would require me install a shit-ton of ruby
dependencies. I can't be bothered to wait for that, so I wrote my own
script that does something similar.
