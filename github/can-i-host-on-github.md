---
related:
    - github/how-can-i-export-to-repo.md
    - github/how-can-i-import-repo.md
    - github/how-can-i-resolve-github-sync-errors.md
---

<!-- TODO Reuse the article from documentation/doc-separation and make a it _guide_ -->

GitBook integrates perfectly with [GitHub](https://github.com) as a hosting solution
for the source of your book. When configured correctly, this has several effects:

- All updates made to your book from the Editor will also update the GitHub repository.
- All updates made to your GitBook or GitHub repository will be reflected on the other and update your published book accordingly.

Integrating with GitHub is done in 3 steps:

1. Setting up our [GitHub Integration](#github-integration)
2. [Granting access](#granting-access) to your repositories
3. Linking a book to a GitHub repository
  1. [Linking an existing book](./how-can-i-export-to-repo.md)
  2. [Creating a new book from a GitHub repository](./how-can-i-import-repo.md)

### 1. Setting up our GitHub Integration {#github-integration}

First, you need to install our GitHub integration on the account of the owner of the book(s) you want to be hosted on GitHub.

- If the owner of the book is an organization, log in with a GitBook account with admin permissions for that organization.
  Go to the GitHub section of the organization's settings page. From here, use the dropdown button to select the GitHub organization
  you want to sync your GitBook organization with and click on the **Install GitHub integration** button.
  ![](/assets/sync-github-org.png)

- Otherwise, log in with your personal account. Go to the [GitHub section of your settings page](https://www.gitbook.com/settings/github)
  and click on the **Install GitHub integration** button.
  ![](/assets/install-github-integration.png)

You should have arrived on the GitHub integration's page for GitBook.

### 2. Granting access to your repositories {#granting-access}

On the GitHub integration's page, select which repositories you want to grant GitBook access to.

![](/assets/select-github-integration-repositories.png)

Confirm the installation by clicking the **Install** button.
