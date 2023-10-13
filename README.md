# [@Malix-Off](https://github.com/Malix-Off) Template

## GitHub Files

Fully featued with GitHub files

## GitHub Actions

Optimized for [Trunk-Based Development](https://trunkbaseddevelopment.com/)

## Features

- On issue create:
  - [ ] [Create a branch named as the issue ID and link it to the created issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-a-branch-for-an-issue)
    - On first commit push to this branch:
      - [ ] Create a draft pull request to the upstream issue if any, else master
- On push to master:
  - [ ] Create a draft release with a tag annoted with the latest semver tag incremented by one patch 
