<!-- TODO Reuse the article from documentation/doc-separation and make a it _guide_ -->

GitBook integrates perfectly with [GitHub](https://github.com) as a hosting solution
for the source of your book. When configured correctly, this has several effects:

- All updates made to your book from the Editor will also update the GitHub repository.
- All updates made to your GitBook or GitHub repository will be reflected on the other and update your published book accordingly.

Integrating with GitHub is done in 3 steps:

1. Setting up our [GitHub Integration](#github-integration)
2. [Granting access](#granting-access) to your repositories
3. [Linking a book](#linking-a-book) to a GitHub repository

### 1. Setting up our GitHub Integration {#github-integration}

First, you need to install our GitHub integration on the account of the owner of the book(s) you want to be hosted on GitHub.

- If the owner of the book is an organization, log in with a GitBook account with admin permissions for that organization.
  Go to the GitHub section of the organization's settings page. From here, use the dropdown button to select the GitHub organization
  you want to sync your GitBook organization with and click on the **Install GitHub integration** button.

- Otherwise, log in with your personal account. Go to the [GitHub section of your settings page](https://www.gitbook.com/settings/github)
  and click on the **Install GitHub integration** button.

You should have arrived on the GitHub integration's page for GitBook.

### 2. Granting access to your repositories {#granting-access}

On the GitHub integration's page, select which repositories you want to grant GitBook access to.

Confirm the installation by clicking the **Install** button.

### 3. Linking a book to a GitHub repository {#linking-a-book}

#### 3.1 Linking an existing book

Go to the GitHub section of your book's settings and select the GitHub repository to link this book to and confirm by clicking on the **Sync** button.

At this point, the GitBook and GitHub repositories are likely to be out of sync.
This case can also happen if you edited both your book and your GitHub repository in parallel.

Whenever this is the case, you can come back to this page and select which content
you would like to use as the source of truth between GitBook and GitHub to force
re-syncing their content.

Be careful though, forcing your content to sync **will totally replace** the destination's
existing content, so be sure to know what you're doing.

#### 3.2 Creating a new book from a GitHub repository

From the [new book page](https://www.gitbook.com/new), select the **GitHub**
template on the left. If you didn't already setup GitHub, you will be asked to install the
integration and come back.

Once this is done, fill in the title and the optional description and select
which GitHub repository you would like to link this new book to.

Finally, click on the **Create book** button.
