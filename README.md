# gecko-dev
mirror of gecko-dev, minus the commit logs

### how to use
- create your feature branch, make changes, push to this repo (super-friends copy)
- open PRs against master, land in master

### how we will keep synced with upstream (mozilla's copy):
- every so often, someone (probably jared) will apply the latest changes to the upstream branch
  - following this basic approach from SO: http://stackoverflow.com/questions/931882/how-to-apply-a-git-patch-from-one-repository-to-another
- then we'll open a pull request to merge them into master, and life may get "interesting" at that point

#### why no commit logs?
gecko-dev is awkwardly huge in 2 ways: sheer disk size (3 gigs, wat), and number of commits (over 400,000). We don't really need those commit logs here; you can jump over to mozilla's fork to investigate the history of bits of code. Hopefully this makes our fork a little easier to push and pull...I kinda doubt it though.
