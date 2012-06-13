## Git branches

Master branch on github is generated using `rake generate`
Source branch is branch that we can do changes and execute rake generate on.
Master local branch is set to track changes from master on octopress remote repo.

## Deploying

		rake generate
		rake publish
