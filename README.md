<h1 align="center">GitHub Logs <a href="https://twitter.com/intent/tweet?text=GitHub%20Logs%20-%20Extracting%20OSINT%20Insights%20from%2015TB%20of%20GitHub%20Event%20Logs%0A%0Ahttps%3A%2F%2Fgithub.com%2Ftrickest%2Fgithub-logs"><img src="https://img.shields.io/badge/Tweet--lightgrey?logo=twitter&style=social" alt="Tweet" height="20"/></a></h1>
<h3 align="center">Extracting OSINT Insights from 15TB of GitHub Event Logs</h3>

We've developed 3 Trickest workflows that processed and enriched the entire GitHub Event Logs dataset, giving us some valuable insights. Now, the entire community can benefit from these results.

Did you know that exactly 16 GitHub users have the special `site_admin` status on the public GitHub platform? Are you interested in finding out which users are associated with a specific company using a `grep` command? Or perhaps you want to identify deleted user accounts that could pose risks like impersonation or dependency confusion? Maybe you're curious about the top 10 most popular repositories across GitHub in terms of stars, forks, or watchers.

If any of this catches your interest, check out our highlights report: [Uncovering OSINT Insights from 15TB of GitHub Logs](https://trickest.com/reports/uncovering-github-osint-insights/).

## What's Inside?
The repository consists of CSV files that contain the user and repository details organized into two main folders: `users` and `repos`. Inside each folder, you'll find a main folder that contains the complete dataset: `all_user_info` and `all_repo_info`. We've also included partial datasets for specific criteria like `users_site_admin`, `users_deleted`, `users_company`, `repos_archived`, `repos_deleted`, `and repos_sorted_stars`.

```
github-logs
├── repos
│   ├── all_repo_info
│   │   ├── all_repo_info00000.csv
│   │   ├── all_repo_info00001.csv
│   │   └── ...
│   ├── repos_archived
│   ├── repos_deleted
│   ├── repos_disabled
│   ├── repos_private
│   ├── repos_sorted_forks
│   ├── repos_sorted_stars
│   └── repos_sorted_watchers
└── users
    ├── all_user_info
    ├── users_company
    ├── users_deleted
    ├── users_email
    ├── users_github_star
    ├── users_hireable
    └── users_site_admin
```

If you're looking for inspiration on how to use this data or if you're curious about how we collected it, check out the [insights report](https://trickest.com/reports/uncovering-github-osint-insights/).

## Build your own workflows
We believe in the value of tinkering; cookie-cutter solutions rarely cut it. Sign up for a [Trickest](https://trickest.com) demo to access the workflows we used, customize them, explore many more workflows, or even create your own from scratch!

[<img src="images/banner.png" />](https://trickest-access.paperform.co/)
