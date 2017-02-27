# What are Change Requests ?

When you're working on a book, you're going to have a bunch of changes or ideas in progress at any given time. Some of them are ready to be published, some are waiting to be reviewed by your collaborators, and others are just not ready at all. **Change Requests** exist to help you manage this and keep a clean workflow.

When you create a change request in your book, you're creating an environment where you can try out new ideas. Changes you make on a request don't affect the primary version. You're free to experiment and make changes, safe in the knowledge that your changes won't be accepted and merged until they're ready to be reviewed.

Once you start using change requests, your workflow will become faster and more focused. Each change request will make a cohesive and distinct set of changes, that can be reviewed independently from others. Your published version will always stay polished and coherent. And you will have a high-level view of your book's evolution.

### Create a change request

All collaborators with edit access can create a change request from the GitBook Editor. In the Editor, click **Create a change request**.

![](/assets/editor-create-cr.png)

You'll be prompted to type a title and a description for your change request, so that others know what is being worked on. Once done, you can see it in the **Change Request** tab of your book on GitBook.com.

![](/assets/gitbookcom-cr-view.png)

As you can see, the Change Request is empty for now. You can now freely make changes to your content from the Editor.

### Review a change request

As you work on your change request, you and your team will be able to **preview** the result, **comment** and make suggestions, helping you **improving the quality of your content**. All this can be done from your change request's page. Change requests are designed to encourage these healthy workflows.

### Accept the changes

Once the change request is ready, you can accept and **merge it** from the online view. Once merged, the changes will make it to the primary version and will be published. Good job!

If you are not happy with the changes, you can also close the change request without merging it. The change request can be reopened anytime without any loss.

> Note: If the change request has conflicts with the primary version, you'll be asked to resolve these conflicts. This happens when changes are made to the same content on the primary version, while your change request is open. _Resolving conflicts will not accept the change request_, but it will ensure that you stay up-to-date with the latest changes in your book. This step can be taken at any time. The earlier, the better.

### Advanced: change requests and branches

Each book on GitBook.com is backed by a [Git repository](/books/how-can-i-use-git.md). Creating a change request, creates a new branch `changes/<id>` . Pushing commits to this branch will add changes to your request. Merging this branch will automatically accept and merge the change request.

