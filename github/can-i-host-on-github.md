<!-- TODO Reuse the article from documentation/doc-separation and make a it _guide_ -->

GitBook integrates perfectly with [GitHub](https://github.com) as a hosting solution for the source of your book. When configured correctly, this has several effects:

- The Editor will make changes directly to the GitHub repository
- GitBook will watch for updates on GitHub and trigger website/pdf updates accordingly

Integrating with GitHub is done using the following process:

1. [Set up permissions](#permissions)
2. [Export your book to GitHub](#importing)
2. [Link your book to a GitHub](#linking)
3. [Set up webhooks](#webhooks)

## 1. Set up permissions {#permissions}

To integrate your book with GitHub, you need to authorize GitBook to access your GitHub account to some extent. From your [account's settings](https://www.gitbook.com/settings), connect your GitHub account and choose what you will allow:

- **Default permissions**: Allows you to authenticate with GitHub on GitBook.
- **Access to public repositories**: Allows editing books on your public GitHub repositories from the GitBook Web editor.
- **Access to private repositories**: Same as above, but for private repositories too.
- **Access to webhook**: Allows GitBook to create webhooks on your book repositories to trigger builds automatically.

## 2. Use GitHub as your primary book repository 

This process involves two procedures:

* [importing your GitBook repository to GitHub](#importing)
* [linking your GitHub repository with GitBook](#linking)

### 2.1 Import your book repository to GitHub {#importing}

**NOTE** If you authenticate to GitBook using a SSO service like GitHub or Google, make sure you set a GitBook password in your `Settings` before proceeding. 
Importing will fail unless you do.

1. On your book's landing page, click **Settings**.
2. Scroll down to the **Git URL** and copy the path.
3. Click **GitHub** in the left settings pane.
4. Click the **Export to GitHub** button.
5. In the **Old repository's clone URL** field, paste the GitBook Git URL you copied in step 2.
6. In the **Your new repository details** field, type in the name for your new repository.
7. Click **Begin Import**.
8. If prompted for login credentials, these are your GitBook username (typically your email) and your password (you set prior to starting this procedure.

### 2.2 Link your GitHub repository to your GitBook book {#linking}

1. On your book's landing page, click `Settings`.
2. Click **GitHub**.
3. Type the name of your exported book repository in the following format: `<github-username>/<github-repository-name>`
4. Click **Save**

You do not need to enter the full GitHub address, nor the `.git` extension. For example: `GitbookIO/help.gitbook.com` if you were using the source for the GitBook Help FAQ.

## 3. Setting up webhooks {#webhooks}

The final step is to configure a webhook on your GitHub repository that will let GitBook know when your repository is updated.

After completing [step 2.](#linking), a new **Integration** panel will appear on your book's GitHub settings page.
To add the webhook, you can either:

- Click on the **Add webhook** button to automatically create the webhook in your GitHub repo
- Add the provided **Webhook URL** manually to your GitHub repository with access to **Push** events

Either way, clicking on the **Check webhooks** button will lead you to your GitHub repo settings page where you should see the newly created webhook.

The next push event to your GitHub repository will trigger a new update of your book on GitBook.
