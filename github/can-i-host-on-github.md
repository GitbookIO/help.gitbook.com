<!-- TODO Reuse the article from documentation/doc-separation and make a it _guide_ -->

GitBook integrates perfectly with [GitHub](https://github.com) as a hosting solution for the source of your book. When configured correctly, this has several effects:

- The Editor will make changes directly to the GitHub repository
- GitBook will watch for updates on GitHub and trigger website/pdf updates accordingly

Integrating with GitHub is done in 3 steps:

1. Setting up [GitHub Integration](#github-integration)
2. [Grant access to your repositories](#grant-access)
3. Linking your book to a GitHub repository
    3.1 [Existing book](#existing-book)
    3.2 [Create a new book using GitHub](#create)

### 1. Setting up GitHub Integration {#github-integration}

To integrate your book with GitHub, you need to authorize GitBook to access
your GitHub account to some extent. From your [account's
GitHub settings](https://www.gitbook.com/settings/github), connect your GitHub
account using the **Connect GitHub** button and install the GitBook integration
on GitHub using the **Install GitHub integration on this account** button.

This will redirect you to GitHub's integration install page where you can
install and configure GitBook integration for GitHub.

### 2. Grant access to your repositories {#grant-access}

From GitHub's integration page, choose either all repositories or grant access to just some of them.

Click on the **Install** button.

### 3. Linking your book to a GitHub repository {#existing-book}

From your book's GitHub settings page, you can easily specify to which GitHub repository your book will be linked.

Click on the button **Select a Repository**. This should list the repositories
you granted access in the previous step.

Choose one and click on the **Sync** button.

### 3. Create a new book using GitHub {#create}

From the [new book page](https://www.gitbook.com/new):

1. Below the three default templates, click on the arrow down and choose **GitHub**.
2. If you haven't properly connected to GitHub configured the integration, you
   will be able to do so from here. Otherwise, fill in a title and an optional
   description while choosing a GitHub repository to link to this new book.
3. Click on the **Create book** button
