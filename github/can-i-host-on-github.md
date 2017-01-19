<!-- TODO Reuse the article from documentation/doc-separation and make a it _guide_ -->

GitBook integrates perfectly with [GitHub](https://github.com) as a hosting solution for the source of your book. When configured correctly, this has several effects:

- The Editor will make changes directly to the GitHub repository
- GitBook will watch for updates on GitHub and trigger website/pdf updates accordingly

Integrating with GitHub is done in 3 steps:

1. Setting up [GitHub Integration](#github-integration)
2. [Grant access to your repositories](#grant-access)
3. Linking your book to a GitHub repository
  1. [Existing books](#existing-books)
  2. [Create a new book using GitHub](#create)

### 1. Setting up GitHub Integration {#github-integration}

To integrate your book with GitHub, you need to authorize GitBook to access
your GitHub account to some extent. Setup GitHub by clicking on the **Install
GitHub integration on this account** button from your [GitHub account's
settings page](https://www.gitbook.com/settings/github).

This will redirect you to GitHub's integration install page where you can
install and configure the GitBook integration for GitHub.

### 2. Grant access to your repositories {#grant-access}

From GitHub's integration page, choose either all repositories or only grant access to some of them.

Click on the **Install** button.

### 3.1 Linking your book to a GitHub repository {#existing-books}

From your book's GitHub settings page, you can easily specify to which GitHub repository your book will be linked.

Click on the button **Select a Repository**.

Select one and click on the **Sync** button.

### 3.2 Create a new book using GitHub {#create}

From the [new book page](https://www.gitbook.com/new):

1. Below the three default templates, click on the arrow down and choose **GitHub**.
2. If you didn't already setup GitHub, you will be asked to install the
   integration and come back. Otherwise, fill in a title and an optional
   description while choosing a GitHub repository to link to this new book.
3. Click on the **Create book** button
