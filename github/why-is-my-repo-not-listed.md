To import a book from, or link a book to a GitHub repository belonging to a
GitHub organization, the GitHub organization needs to grant access to the
GitBook integration. Otherwise, the repository will not be listed for you to
import.

### Books linked to repositories that belong to an organization

If you already have books linked to repositories that belong to an
organization, you'll need to follow these three steps:

1. [Create a GitBook organization](#new-organization).
2. Sync it with GitHub using our integration.
3. Transfer the ownership of these books to this organization.

### New organization {#new-organization}

#### Check the current status

You can check that GitBook.com is able to access the required GitHub
organization by visiting GitBook's organization settings page (for instance
`https://www.gitbook.com/@org/settings/github`, replace `org` by your GitBook's
organization name).

This page will list the organization book's currently linked to GitHub and
their status regarding the integration (if they're included in the integration
or not).

#### Grant access to GitBook

If the GitBook integration doesn't have access to the GitHub organization, you can either:

- directly grant the integration access to the organization if you are an owner
- or make a request to the organization's owner to grant the access

If you are an owner of the GitHub organization, you'll be able to sync this
organization with GitHub using the **Select a GitHub organization** button,
which will list your organizations on GitHub.

Then, click on the **Install GitHub integration on this account** button, that
will redirect you to the integration install page where you'll be able to
install the integration and choose the repositories you wish to enable
access to.

#### Checking GitBook's settings for GitHub

After the access has been granted to GitHub, go back to the organization GitHub
settings page.

This page will list the organization book's currently linked to GitHub and
show their sync status regarding the GitHub integration.
