---
search:
    keywords: ["github", "organization", "find", "list"]
---

In order to sync one of your GitBook organizations with a GitHub organization, our GitBook OAuth application needs permissions to access this GitHub organization. Otherwise, it will not be listed.

### Check the current status

You can check that the GitBook application is able to access the required GitHub organization by visiting [GitBook's authorization page](https://github.com/settings/connections/applications/e103ee3796d447fab74c).

### Grant access to GitBook

If the GitBook application doesn't have access to the GitHub organization, you can either:
- directly grant the application access to the organization if you are an owner,
- or make a request to the organization's owner to grant the access.

### Reconnecting your GitHub account

After the access has been granted on GitHub, you must update your GitHub Access Token for the GitBook OAuth application.
To do so, simply go to [your settings page](https://legacy.gitbook.com/settings/github) and click on `Reconnect GitHub Account`.
