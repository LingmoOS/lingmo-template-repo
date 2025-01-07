# lingmo-template-repo
This is a template repo for Lingmo

## Branch Protection and Merge Bot

Please add branch protection rule in repo settings to better protect the repo and enable the function of merge bot!

Please do not use the rulesets page as the merge bot dosen't support this currently.

Example configuration: 
 - Branch name pattern: `m*[aest]?[rn]`
 - Require a pull request before merging
   - Require approvals: >= 1
   - Dismiss stale pull request approvals when new commits are pushed
   - Require approval of the most recent reviewable push
 - Require status checks to pass before merging (Optional, if any)
 - Require conversation resolution before merging
 - Do not allow bypassing the above settings

