# datasciencecoursera
$ cd github-services
$ git remote add upstream git://github.com/pjhyett/github-services.git
$ git fetch upstream

# then: (like "git pull" which is fetch + merge)
$ git merge upstream/master master

# or, better, replay your local work on top of the fetched branch
# like a "git pull --rebase"
$ git rebase upstream/master
