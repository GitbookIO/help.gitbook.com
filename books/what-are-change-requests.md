# What are Change Requests ?

When you're working on a book, you're going to have a bunch of changes or ideas in progress at any given time. Some of them are ready to be published, some are waiting to be reviewed by your collaborators, and others are just not ready at all. **Change Requests** exist to help you manage this and keep a clean workflow.

When you create a change request in your book, you're creating an environment where you can try out new ideas. Changes you make on a request don't affect the primary version. You're free to experiment and make changes, safe in the knowledge that your changes won't be accepted and merged until they're ready to be reviewed.

Once you start using change requests, your workflow will become faster and more focused. Each change request will make a cohesive and distinct set of changes, that can be reviewed independently from others. Your published version will always stay polished and coherent. And you will have a high-level view of your book's evolution.

### Create a change request

All collaborators with edit access can create a change request from the GitBook Editor. In the Editor, click **Create a change request**.

![](/assets/editor-create-cr.png)

You'll be prompted to type a title and a description for your change request, so that others know what is being worked on. Once done, you can see it in the **Change Request** tab of your book on GitBook.com.  
  
![](/assets/gitbookcom-cr-view.png)

### Review a change request

Once a change request is opened, you can discuss and review the potential changes with collaborators and make follow-up changes before the request is accepted and merged in the primary version \(**Opened change requests are always editable**\).

After you're happy with the proposed changes, you can **Accept the changes**.

### Accept the changes

Once the change request is ready. You can accept and **merge it** from the online view.

If the change request has conflicts with the primary version, you'll be redirected to a resolution view in the online editor.

If you decide you don't want the changes, you can close the change request without merging. The change request can then be reopened at any time without any loss.

### Branches and change requests

Each book on GitBook.com is backed by a [Git repository](/books/how-can-i-use-git.md). Creating a change request, creates a new branch `changes/<id>` . Pushing commits to this branch will add changes to your request; Merging this branch will accept and merge the change request.

