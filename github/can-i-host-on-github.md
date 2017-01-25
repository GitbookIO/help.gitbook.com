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

First, you need to install our GitHub integration on the account of the author
of the book(s) you want to be hosted on GitHub.

- For your personal account, you can go directly to your [GitHub account's
settings page](https://www.gitbook.com/settings/github) and click on the **Install
GitHub integration on this account** button.

- For an organization, you will find the same GitHub tab in the organization's
settings page. From here, select an organization and click on the **Install** button.

In both cases, this will lead you to the GitHub integration's installation page.

### 2. Granting access to your repositories {#granting-access}

On the GitHub integration's installation page, select which repositories you
want to grant GitBook access to. It is now possible to select all or only some of them.

Finally, click on the **Install** button.

### 3. Linking a book to a GitHub repository {#linking-a-book}

#### 3.1 Linking an existing book

Go to your book's GitHub settings page and click on the **Select a Repository** button.
After you selected one, click on the **Sync** button.

At this point, chances are high that your GitBook content and your GitHub repository
are out of sync. This case can also happen if you edited both your book and your GitHub
repository in parallel.

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
