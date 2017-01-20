---
related:
    - github/can-i-host-on-github.md
---

Exporting your GitBook content to a GitHub repository is super simple.

1. [Setup GitHub](#setup-github)
2. [Link your book to a GitHub repository](#link-book)
3. [Resolve potential conflicts](#resolve-conflicts)

### 1. Setup GitHub {#setup-github}

If not already, the owner's account of the book you would like to export
must be configured to use our GitHub integration. See [this article] for
a detailed explanation of how to setup your account with GitHub.

### 2. Link your book to a GitHub repository {#link-book}

Go to your book's GitHub settings page and click on the **Select a Repository** button.
After you selected one, click on the **Sync** button.

From now on, every update of your book will be reflected automatically on
the selected GitHub repository.

### 3. Resolve potential conflicts

If you linked an existing book with an existing GitHub repository, chances are high
that your GitBook content and your GitHub repository are out of sync. This case can
also happen if you edited both your book and your GitHub repository in parallel.

Whenever this is the case, you can come back to this page and select which content
you would like to use as the source of truth between GitBook and GitHub to force
re-syncing their content.

Be careful though, forcing your content to sync **will totally replace** the destination's
existing content, so be sure to know what you're doing.
