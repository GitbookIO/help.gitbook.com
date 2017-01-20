If some of your books are linked to GitHub repositories, you might
encounter an error telling you GitBook does not have the permissions
to access every or a specific repository.

In this case, you either:
- did not grant access to this repository to our [GitHub integration](#github-configuration),
- linked a book on your personal account with a [GitHub repository
belonging to an organization](#organizations-repositories).

### Configure GitBook repository access {#github-configuration}

If you encounter a `Repository access` error on your GitHub settings page,
you will be prompted with an alert which includes a **Configure** link.

Clicking on it will lead you to your GitHub integration settings page were
you see the list of repositories that you granted GitBook access to.

If you did not select **All repositories** and don't see the repository
that one of your books is linked to, you can easily add it to the list
of your accessible repositories.

### GitHub organizations' repositories {#organizations-repositories}

It used to be possible to link a GitHub repository belonging to a GitHub
organization to one of your user account's book.

GitBook now uses the new GitHub integrations system to manage the sync
between your books and external repositories. While this simplify many aspects
in integrating GitHub with GitBook, the only drawback is that your organizations'
repositories are not accessible using your user account anymore.

If you find yourself in this case, follow the 3 following steps:

1. [Create a new organization](../orgs/how-can-i-create.md)
2. [Sync it](can-i-host-on-github.md#github-integration) with the GitHub organization that owns the repository(ies)
3. [Transfer the ownership](../books/how-can-i-transfer-ownership.md) of your concerned book(s) to this organization
