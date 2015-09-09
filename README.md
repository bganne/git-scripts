# git-scripts

Some random scripts I use to ease my day-to-day life with git:

-	`git-dist-commit`: commit in a main repo using submodules with
	a nice recap message about modified submodules
-	`git-dist-push`: push commit to a remote repo, pushing any
	needed submodule along the way
	WARNING: this use a 'force-push' semantic
-	`git-imap-send`: send patches over imap(s). Directly inspired from
	`git imap-send` which is broken on my Debian testing for some
	unknown reason (it keeps trying doing webdav stuff...)
-	`git-smtp-send`: send patches over smtp(s).
