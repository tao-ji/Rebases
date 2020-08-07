# Rebases

Each line represents one rebase in the format: [*repo: PR_num : pre_commits: post_commits: local_pre_commits: local_post_commits: matched_indexes*].

- *pre_commits*: an ordered list of commits in the first-parent of the head branch before rebasing.
- *post_commits*: an ordered list of commits in the first-parent of the head branch after rebasing.
- *local_pre_commits*: SHAs of *pre_commits* restored in our local machine.
- *local_post_commits*: SHAs of *post_commits* restored in our local machine.

The ordered list of commits is represented as [HEAD, ..., fork-point].
