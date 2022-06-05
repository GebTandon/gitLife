- [List of Github Apis](https://developer.github.com/v3/ )
Events:
- workflows can also run on a CRON schedule. The least time we can select is 5 mins. Run on latest version of a default chosen branch.
- we can also external events to trigger Github actions. Send a Post request to github endpoint, and use repository_dispatch event to respond to exeternal events.
` on: repository_dispatch
    type: [opened, deleted]
`
Environment variables & secrets:
-  Secrets, can be done throught settings at repo level. Secrets cannot be shared with forks of a repo.
- `GITHUB_TOKEN` is a default token, created for github app.
- 

