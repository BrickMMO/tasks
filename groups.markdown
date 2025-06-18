<style>@import url("//readme.codeadam.ca/readme.css");</style>

## GitHub for Groups

[GitHub](https://github.com/) is even more important when working in groups. It allows a groups of developers to:

- Share code with group members
- Work on the same files without overwriting changes made by other developers
- Revert code to a previous state if mistakes are made

## Errors

When working with Git and GitHub in groups, sometimes you will receive errors that you may not be able to resolve. When you're first learning these errors can be really frustrating. Here is one solution that will always work:

1. If you have significant changes, make sure to save those somewhere.
2. Delete your local copy of the project.
3. Clone a fresh copy from the GitHub repo:

   ```sh
   git clone https://github.com/BrickMMO/tasks.git
   ```

4. Reapply your changes.
5. Add current changes to the main copy:

   ```sh
   git add .
   ```

6. Commit changes to the main copy:

   ```sh
   git commit -am "Describe latest changes"
   ```

7. Push the changes to your GitHub repo:

   ```sh
   git push origin main
   ```

There are better resolutions for some situations. However, this resolution has gotten me out of several jams.

## Stack Overflow

![Stack Overflow](images/logo-stack-overflow.png)

Alternatively, you can Google your error, in which case you will likely find a resolution on [Stack Overflow](https://stackoverflow.com/). Or you can post a question to [Stack Overflow](https://stackoverflow.com/). Before you post a question, make sure you read the [How to Ask a Question](https://stackoverflow.com/help/how-to-ask) in the Stack Overflow documentation.

We will discuss [Stack Overflow](https://stackoverflow.com/) in more detail during the [Stack Overflow Task](stack-overflow).

## Group Development Loop

There are multiple methods of working in a groups on the same GitHub repository. You can invite other developers to be contributors of the repo, there are detailed instructions in my [github-demo-branching](https://github.com/codeadamca/github-demo-branching) repo. Or you can fork the repo and contribute by submitting Pull Requests. There are details instructions in my [github-demo-forking](https://github.com/codeadamca/github-demo-forking) repo.

Here is a basic example of forking a repo:

1. Navigate to the GitHub repo you would like to contribute to and fork this repository by clicking `Fork`. All the default values are fine. Then click `Create fork`. You will now have a repository in your GitHub account with the specified name.
2. Then clone your new repo:

   ```sh
   git clone https://github.com/<GITHUB_USERNAME>/<REPO_NAME>.git
   ```

3. Then make changes to the repo content.
4. Add, commit and push these changes:
   
   ```
   git add .
   git commit -am "<CHANGE_DESCRIPTION>"
   git push origin main
   ```

5. Using a browser, navigate to your GitHub forked repo, click `Pull requests`, and click `New pull request`.

   ![New Pull Request](images/screenshot-pull-request.png)

6. Confirm the branch, review the code you are submitting, and click `Create pull request`.

   ![Submit Pull Request](images/screenshot-pull-submit.png)

   The original GitHub repo owner will be notified of the pull request!

## Details

Some of these tasks are an exercise in paying attention to the details. **Read** the instructions! Follow the instructions **carefully** and **slowly**! Copy the examples **exactly**! Follow the existing naming conventions.

## Steps

To complete this task, follow these steps:

1. Create a fork of the [BrickMMO contributions](https://github.com/BrickMMO/contributions) repo.

2. Clone **your** new repo to your computer. **DO NOT clone the BrickMMO repo!**

3. Open up your code editor and point it to the new project folder. It will be named something like `forked-contributions`.

4. Create a page in the students folder. Name this page using your GitHub username (for example `codeadamca.markdown`). Use lowercase and kebab case (for example `BetVilen_45` becomes `betvilen-45.markdown`). Copy the code from another student page as a starting point. 

5. Add your image to the images folder in your repo. Name your image using your GitHub username (for example `codeadamca.jpg`). Use the same conventions used in step 3, lowercase and kebab case). Image should be exactly 80 x 80 pixels.
   
   If you have never resized an image, do a quick Google of the term `resize image` and you will get lots of suggestions. I would recommend [Pixlr](https://pixlr.com/) or Photoshopo if you have a copy. 

6. Add your information to your page (GitHub, LinkedIn, portfolio, etc...). Do **not** include personal contact information like email or phone number. 

7. Add a table with a list of BrickMMO projects you have contributed to. At this point just include the `Tasks` project and link it to `https://tasks.brickmmo.com/`. Here is an example of the projects table:

   ```markdown
   | Project |                                                                                  |
   | ------- | -------------------------------------------------------------------------------- |
   | Tasks   | [https://tasks.brickmmo.com/](https://tasks.brickmmo.com/)                       |
   ```

8. Add your name to the student table in the appropriate HTTP5114 class pages. Here is an example of the student table:

   ```markdown
   | ![Adam Thomas](images/codeadamca.png) | Adam Thomas | [codeadamca](students/codeadamca) |
   ```

9. When you are done, push the updates to **your** GitHub repo:

    ```
    git add .
    git commit -am "Added Adam to HTTP5114"
    git push
    ```

    Use a meaningful commit message.

10. Then navigate to **your** `forked-contributions` repo in a browser and submit a pull request. You can do this by clicking the `Contribute` button and then `Pull Request`.

> You can check our my page as an example:  
> [https://contributions.brickmmo.com/faculty/codeadamca](https://contributions.brickmmo.com/faculty/codeadamca)

> Or you can view the Markdown here:  
> [https://github.com/BrickMMO/contributions/blob/main/faculty/codeadamca.markdown](https://github.com/BrickMMO/contributions/blob/main/faculty/codeadamca.markdown)

## Submitting this Task

Once your instructor has approved your pull request, copy a link to your forked repo and submit it to the **Groups** assignment in [Blackboard](https://learn.humber.ca/).

For example, my link would be [https://contributions.brickmmo.com/faculty/codeadamca](https://contributions.brickmmo.com/faculty/codeadamca).

[&#10132; Back to Task List](/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
