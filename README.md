# git-flow

Let's practice Git flow!

* Pick an issue, 
* Create a branch from dev: 
  * `git checkout -b feat/blalba dev`
* Open a pull request to `dev`!

Once we have enough content to create a release: 

Spotting an issue on our release candidate?

* Create a `bugfix/v1-blabla` branch
* Open a pull request to `release/v1` directly!

Ready to release?

* Merge `release/v1` in `main`. 
* Release!
* Merge `release/v1` in `dev`.
* Delete `release/v1`.

For any issue discovered after the release, send hotfixes to `main` directly!

* Create a `hotfix/v1-blabla` branch
* Merge it both in `main` and `dev`.

https://nvie.com/posts/a-successful-git-branching-model/
