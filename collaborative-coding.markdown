<style>@import url("//readme.codeadam.ca/readme.css");</style>

## Collaborative Coding

For this task you will contribute to the BrickMMO Smart City project. 

![What is GitHub](images/meme-what-github.png)

Choose a project from the [BrickMMO Project List](https://github.com/orgs/BrickMMO/projects) and complete one or more isssues.

## Steps

To complete this task, follow these steps:

1. Work in groups of two to three. Take turns being the primary codder.

2. Choose a project from the [BrickMMO Project List](https://github.com/orgs/BrickMMO/projects).
   
3. Choose an issue that is currently labellled as **ToDo**. Mark it as **In Propgress**. Clone the associated repo.

> ![NOTE]
> If you are not yet a member of the BrickMMO organization, ask your instructor to add you. 

4. Clilck the **Assign Yourself** link.

5. Clck the **Create a Branch** link. The default branch name is fine:

6. Use the provided code to create and checout a new banch.

   ```
   git fetch origin
   git checkout 1-branch-name
   ```

   If running the above code causes an error, we need to add one more line to create the branch before we check it out:

   ```
   git fetch origin
   git branch 1-branch-name
   git checkout 1-branch-name
   ```

8. Use VSCode to make the required changes.

9. Commit your changes and push using the branch name:

    ```
    git add .
    git commit -am "Meaningful description"
    git push origin 1-branch-name
    ```

10. Create a **Pull Request**.

11. Your istructor will merge.

## Submitting this Task

After you have completed at least one issue, submit a link to the Pull Request in the **Collaborative Coding** assignment in [Blackboard](https://learn.humber.ca/).

[&#10132; Back to Task List](/)

---

<a href="https://brickmmo.com">
<img src="https://cdn.brickmmo.com/images@1.0.0/brickmmo-logo-coloured-horizontal.png" width="200">
</a>

<script 
    src="https://cdn.brickmmo.com/bar@1.1.0/bar.js"
    data-console="false"
    data-menu="false"
    data-admin="false"
    data-local="false"
    data-https="true"
></script>
