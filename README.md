# [@Malix-Off](https://github.com/Malix-Off) Template

## GitHub Files

Fully featued with GitHub files

## GitHub Actions

Optimized for [Trunk-Based Development](https://trunkbaseddevelopment.com/)

## Features

- On issue create:
  - [ ] [Create a branch named as the issue ID and link it to the created issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-a-branch-for-an-issue)
    - On first commit push to this branch:
      - [ ] Create a draft pull request to the [parent issue](https://docs.github.com/en/issues/managing-your-tasks-with-tasklists/about-tasklists#about-tasklists-and-issue-hierarchy:~:text=You%20can%20create-,parent,-and%20child%20relationships) if any, else master
- On push to master:
  - [ ] Create a [draft release](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository#:~:text=release%20later%2C%20click-,Save%20draft,-.%20You%20can%20then) with a tag annoted with the latest semver tag incremented by one patch 
