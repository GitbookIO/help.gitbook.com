# What are Change Requests ?

Change requests let you tell others about changes you want to include in the primary version. Once a change request is opened, you can discuss and review the potential changes with collaborators and make follow-up changes before the request is accepted and merged in the primary version.

### Create a change request

All collaborators with edit access can create a change request from the editor.

1. On the GitBook Editor, click **Create a change request**.![](/assets/editor-create-cr.png)
2. You'll be prompted to type a title and a description for your change request. 
3. Click **Send**

### Review a change request

Once you've created a change request, you can continue editing it.

Other contributors can review your proposed changes, add review comments, contribute to the change request discussion, and even edit the changes.

After you're happy with the proposed changes, you can **Accept the changes**.

### Accept the changes

Once the change request is ready. You can accept and **merge it** from the online view.

If the change request has conflicts with the primary version, you'll be redirected to a resolution view in the online editor. 

If you decide you don't want the changes, you can close the change request without merging. The change request can then be reopened at any time without any loss.

### Branches and change requests

Each book on GitBook.com is backed by a [Git repository](/books/how-can-i-use-git.md). Creating a change request, creates a new branch `changes/<id>` . Pushing commits to this branch will add changes to your request; Merging this branch will accept and merge the change request.

