## XinFin Community Content Contribution 

- [Contributing to the XinFin content repository](#contributing-to-the-rackspace-how-to-content-repository)
	- [Getting started with GitHub](#getting-started-with-github)
		- [Create a fork of this repository](#create-a-fork-of-this-repository)
		- [Keeping your fork up to date](#keeping-your-fork-up-to-date)
	- [Creating and changing articles](#creating-and-changing-articles)
		- [Create an article](#create-an-article)
    
		- [Edit an article](#edit-an-article)
		- [Make a change to a PR](#make-a-change-to-a-pr)
		- [Request an article change](#request-an-article-change)
	- [Writing guidelines](#writing-guidelines)
	- [Support and feedback](#support-and-feedback)

**Important:** You need to log in to public GitHub, not the enterprise GitHub, to contribute. If you have questions then Join our [Telegram Developer Group](https://t.me/XinFinDevelopers) and put up your queries. We would love to answer your questions.

You can also join our [Public Slack Group](https://launchpass.com/xinfin-public). Enter your E-mail ID and you will get an invite to our slack.



## Contributing to the XinFin content repository

This file describes the general process for maintaining source code for content published at various utility products.

See [Treat Documentation Like Code](https://www.youtube.com/watch?v=haFooDkKr-A&feature=youtu.be) for a brief video overview of how to edit articles on the How-To support network.
If you are a Racker, search MyLearn for the Treat Docs Like Code course.

**Note**: If you already have a GitHub account, you can quickly edit an existing article by clicking on the Edit This Article button on the left-hand side of the page.

### Getting started with GitHub

To contribute to the How-To repository, you need a GitHub account. If you do not have a GitHub account, you can sign up for one [https://github.com/join](https://github.com/join).

#### Create a fork of this repository

Before you create a new article or make edits to an existing one, create a *fork* of the How-To repository.

1. In the top-right corner of the page, click the **Fork** button.

2. In the pop-up box, select your personal GitHub account.

A personal copy of the How-To repository is created in your GitHub account. You can access your fork by going to the [GitHub home page](https://github.com) and selecting **rackspace-how-to** under **Your repositories**.

#### Keeping your fork up to date

Because your forked copy of the repository is not live, you need to periodically update it with changes from the live repository. A status message above the latest commit activity informs you whether your forked repository is current with the master How-To repository. If the status says `This branch is X commits behind rackerlabs:master`, update your repo by clicking the **Pull request** button to the right of the message.

**Note:** If you get a message that the rackerlabs:master branch is up-to-date with commits from your master branch, click the "switching the base" link.

**WARNING:** To avoid any merge conflicts or difficulties when making a pull request, always check that your copy of the fork is up to date with the master repository.

### Creating and changing articles

Use the following instructions to create a new article, make edits to an existing one, or suggest edits via an issue.

Articles are grouped into one directory per product. Each directory contains one file per article.

#### Create an article

Follow these steps to create a new article within a product folder of the **rackerlabs/rackspace-how-to** repo.

1. Go to the [Rackspace How-To content folder](https://github.com/rackerlabs/rackspace-how-to/tree/master/content) and click the product for which you want to create an article.

2. Click **Create new file**.

3. Enter a name for your article in the text box at the end of the **rackspace-how-to/content/*productName*/** string. The name should be in the format **your-article-name.md** and should reflect the title of the article.

4. <a name="metadata"></a>Enter header information using the format shown in the following example:

           ---
           permalink: title-of-article/
           audit_date:
           title: Title of article
           type: article
           created_date: 'YYYY-MM-DD'
           created_by: Your name
           last_modified_date: 'YYYY-MM-DD'
           last_modified_by: Your name
           product: Name of product
           product_url: product-url
           ---
5. Write your article in Markdown. Markdown guidelines are at https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet.

6. When you have finished writing your article, review it in the **Preview** tab.

7. At the bottom of the page, click **Propose new file**.

8. Create a pull request (PR). On the "Open a pull request" page, check the following settings:

    - `base fork: rackerlabs/rackspace-how-to`
    - `base: master`
    - `head fork: {your-username}/rackspac...`
    - `compare: {your-branch}`

   If the settings are not correct, use the drop down menus to select the correct settings. The fork menus may not be present.

9. Describe the reasons for your change in the comment box, and then select **Create pull request**.

**Note:** If your article includes images, send an email to <how-to@rackspace.com> with the image files. Note where the images belong in the article by using comments: `<!--this is a comment-->`.

10. Request reviews of your PR from the Information Development team in the
    ``#how-to`` channel in Slack.

Your PR will be reviewed. Depending on the review feedback, you might be asked to make additional changes. The How-To editorial team will merge your pull request once your contribution is reviewed.
