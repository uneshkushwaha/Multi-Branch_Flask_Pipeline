1. Pushed the code through Git on Github
2. Created a new job named - Multibranch-flask-python
3. Clicked on Multibranch pipeline option and Selected OK
4. Left Display name and Descripition as it is.
5. You will see Github option is branch source - it is shown there because Github plugin for branch is installed there.
After selecting Github - it will shows all the options related to Github
Paste the repo link from Github - credentails (PAT) requries from Github if the repo is private.

Behaviours:

Exclude branches that are also filed as PRs - ` that means build the branch until the PR exist then build the PR jobs to avoid duplicate.`

Only brancehs that are filed as PR - ` only build when the PR is open OR it means those branches whose build are succeed, pushed, and  pull request is made - then that branches  should not include as if already is in  pull request , adding or modifying code in that branches doesn't make sense as that changes would not reflect.`
