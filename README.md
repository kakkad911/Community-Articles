# XinFin Resources

* [Contributing to the XinFin content repository](./#contributing-to-the-xinfin-content-repository)
  * [Creating and changing articles](./#creating-and-changing-articles)
    * [Current Content Requirement](https://github.com/XinFinOrg/Community-Articles/tree/master/Content%20Contribution%20Requirement) 
    * [Create an article](./#create-an-article) 
    * [Edit an article](./#edit-an-article)
    * [Make a change to a PR](./#make-a-change-to-a-pr)
    * [Request an article change](./#request-an-article-change)
  * [Getting started with GitHub](./#getting-started-with-github)
    * [Create a fork of this repository](./#create-a-fork-of-this-repository)
    * [Keeping your fork up to date](./#keeping-your-fork-up-to-date)    
  * [Writing guidelines](./#writing-guidelines)
  * [Support and feedback](./#support-and-feedback)

**Important:** You need to log in to public GitHub, not the enterprise GitHub, to contribute. If you have questions then Join our [Telegram Developer Group](https://t.me/XinFinDevelopers) or join our [Public Slack Group](https://launchpass.com/xinfin-public) and put up your queries.

## Contributing to the XinFin content repository

This file describes the general process for maintaining source code for content published at various [XinFin utility website](https://xinfin.org/xdc-utility.php).

**Note**: If you already have a GitHub account, you can quickly edit an existing article by clicking on the Edit This Article button on the left-hand side of the page.

## Creating and changing articles

Use the following instructions to create a new article, make edits to an existing one, or suggest edits via an issue.

Articles are grouped into one directory per Utility \(e.g:/mycontract, /tradefinex, /infactor etc\). Each directory contains one utility or product each.

### Create an article

Follow these steps to create a new article within a product folder of the **XinFinOrg/Community-Articles** repo.

1. Go to the [XinFin'Community-Articles folder](https://github.com/XinFinOrg/Community-Articles) and click the utility/product for which you want to create an article.
2. Click **Create new file**.
3. Enter a name for your article in the text box at the end of the **XinFinOrg/Community-Articles/**_**productName**_**/** string. The name should be in the format **your-article-name.md** and should reflect the title of the article.
4. Enter header information using the format shown in the following example:

   ```text
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
   ```

5. Write your article in Markdown. Markdown guidelines are at [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
6. When you have finished writing your article, review it in the **Preview** tab.
7. At the bottom of the page, click **Propose new file**.
8. Create a pull request \(PR\). On the "Open a pull request" page, check the following settings:

   * `base fork: XinFinOrg/Community-Articles`
   * `base: master`
   * `head fork: {your-username}/xinfin...`
   * `compare: {your-branch}`

   If the settings are not correct, use the drop down menus to select the correct settings. The fork menus may not be present.

9. Describe the reasons for your change in the comment box, and then select **Create pull request**.

**Note:** If your article includes images, send an email to [info@xinfin.org](mailto:info@xinfin.org) with the image files. Note where the images belong in the article by using comments: `<!--this is a comment-->`.

1. Request reviews of your PR \(pull request\) from the Information Development team in the

   `#general` channel in Slack.

Your content will be reviewed. Depending on the review feedback, you might be asked to make additional changes. The editorial team will merge your pull request once your contribution is reviewed.

### Edit an article

Follow these steps to edit an existing article within a product folder of the **xinfinorg/Community-Articles** repo.

1. Go to the [XinFin content folder](https://github.com/xinfinorg/community-articles/) and click the product/utility for which you want to edit an article.
2. Find the article you want to edit and click to open the file.
3. At the top of the article, click the pencil \(Edit this file\) icon.
4. Make any edits to the article directly through the GitHub website.

   **Note:** If you are using a desktop client or the command line, and you are forking or cloning the repository, be sure to make your changes in a new branch. Doing so ensures that you are producing a pull request \(PR\) rather than committing changes directly to the master.

5. When you have finished editing the article, review it in the **Preview** tab.
6. At the bottom of the page, click **Propose file change**.
7. On the "Open a pull request" page, check the following settings:

   * `base fork: xinfinorg/Community-Articles`
   * `base: master`
   * `head fork: {your-username}/xinfinorg...`
   * `compare: {your-branch}`

   If the settings are not correct, use the drop down menus to select the correct settings. The fork menus may not be present.

8. Describe the changes that you made in a PR message.

   Use the following guidelines to create the PR message:

   * Provide a brief description of the change, starting with an imperative verb. For example, "Add a paragraph about... ."
   * If you make a complex edit, explain why you are making the edit in the larger box under **Commit changes**. For example, if you are changing the formatting of an article because a list should be ordered instead of unordered, say, "Switch list in middle of article to ordered to show clear progression of steps".

9. Click **Create pull request**.
10. Request reviews of your PR from the Information Development team in the `#general` channel in Slack.

Your PR will be reviewed. Depending on the review feedback, you might be asked to make additional changes. The How-To editorial team will merge your pull request once your contribution is reviewed.

### Make a change to a pull request \(PR\)

You might be asked by a member of the editorial team to update your PR. Follow the steps below to make an update to your PR.

1. Go to the [XinFin content folder](https://github.com/xinfinorg/community-articles/) and select the **Pull requests** tab.
2. Find and click your PR.
3. Click the **Files changed** tab.
4. Click the pencil icon next to the file that you want to change.
5. Make your change in the editor.
6. Provide a brief description of the change.
7. Click the **Commit directly to the** `your-branch-name` **branch** option, and then click **Commit changes**.
8. Request reviews of your PR from the Information Development team in the `#general` channel in Slack.

The How-To team will comment on the PR if any more changes need to be made.

### Request an article change

To request a change, create an issue by clicking **Issue** near the top of this page. Describe the changes that you are requesting.

## Getting started with GitHub

To contribute to the How-To repository, you need a GitHub account. If you do not have a GitHub account, you can sign up for one [https://github.com/join](https://github.com/join).

### Create a fork of this repository

Before you create a new article or make edits to an existing one, create a _fork_ of the How-To repository.

1. In the top-right corner of the page, click the **Fork** button.
2. In the pop-up box, select your personal GitHub account.

A personal copy of the How-To repository is created in your GitHub account. You can access your fork by going to the [GitHub home page](https://github.com) and selecting **Community-Articles** under **Your repositories**.

### Keeping your fork up to date

Because your forked copy of the repository is not live, you need to periodically update it with changes from the live repository. A status message above the latest commit activity informs you whether your forked repository is current with the master How-To repository. If the status says `This branch is X commits behind xinfinorg:master`, update your repo by clicking the **Pull request** button to the right of the message.

**Note:** If you get a message that the xinfinorg:master branch is up-to-date with commits from your master branch, click the "switching the base" link.

**WARNING:** To avoid any merge conflicts or difficulties when making a pull request, always check that your copy of the fork is up to date with the master repository.

## Writing guidelines

Use the following general writing guidelines:

* Use sentence-style capitalization for titles and headings
* Use active voice
* Use present tense
* Write to the user by using second person and imperative mood
* Write clear and consistent step text
* Use consistent text formatting
* Clarify pronouns such as _it_, _this_, _there_, and _that_
* Clarify gerunds and participles
* Write clear and consistent code examples
* Use consistent terminology

Following are some specific guidelines for How-To content:

* For the first-level headings in an article, use the H3 level \(designated by \#\#\#\). Avoid using more than three levels of heading in an article \(H3, H4, and H5\). If you need more than three levels, you should consider breaking your article into two or more articles.
* When an article mainly provides step-by-step instructions for users to follow, begin the title of the article with an imperative verb. For example: How to Setup Masternode.
* If a title contains a special character, such as a colon, enclose the title with single quotation marks.
* When code includes placeholders, show them in camelCase and enclose them in angle brackets. For example, `<hostName>`.
* To link to another article, use the following format: `[<articleName>](/community-articles/<articleName>)`. For example, `[How to setup Bond ](/community-articles/mycontract/howtosetupbond)`. Note the use of the leading slash.
* When creating complex lists, such as procedures with sublists, graphics, and code examples, use the spacing guidelines at [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet\#lists](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#lists).

## Support and feedback

If you find a problem, open a GitHub issue.

If you need additional assistance then Join our [Telegram Developer Group](https://t.me/XinFinDevelopers) or join our [Public Slack Group](https://launchpass.com/xinfin-public)

