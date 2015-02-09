This will be my first real commit.

I'm going to commit something else and then revert to this.

Timeline:
* I made a commit at e3729772, it was great
* I made a commit at 1a984091, it was bad
* I wanted to revert back to e3729772 while preserving the history at 1a984091

So, at the command line, once I've already committed and pushed 1a984091:

* git revert --no-commit e3729772..HEAD
* git commit
* git push
