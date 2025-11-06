<style>@import url("//readme.codeadam.ca/readme.css");</style>

## GitHub for Individuals

[GitHub](https://github.com/) is one of the most popular and important development tools you will use. It keeps a history of your development activity and can be used as a tool to show potential employers your code and coding habits.

![GitHub Contributions](images/screenshot-contributions.png)

GitHub can also be used to help multiple developers work on the same code set without overwriting each other's additions. However, this task will focus on using the tool as an individual. In this task you will use GitHub to:

- Store and share your code
- Create backups and version control
- Practice using the Git and GitHub CLI

Remember that [Git](https://git-scm.com/) and [GitHub](https://github.com/) are two different things. Just like Gmail is one of many providers of email. GitHub is one of many providers for storing Git repositories.

Git and GitHub can be hard at first. And if you have never used the Command Line, it can be a bit intimidating. However, it might be the most important and widely used development tool.

![Using the Terminal Meme](images/meme-terminal.png)

## Git CLI

In this class we will use Git through the command line. Start by following the [Getting Started - Git Installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). Once you're done run the following command in your Terminal (Mac/Linux) or Git Bash (Windows) to confirm it has been installed:

```sh
git --version
```

![Git Version](images/terminal-git-version.png)

## GitHub CLI

We will also use the [GitHub Command Line Interface (CLI) Tool](https://cli.github.com/). Please download and install the proper version. Once you're done, run the following command in your Terminal (Mac/Linux) or Git Bash (Windows) to confirm it has been installed:

```sh
gh --version
```

Once you have the GitHub CLI installed, use it to login to your GitHub account:

1. Run the following command:

   ```sh
   gh auth login
   ```

2. Select `GitHub.com`.
3. Select `HTTPS`.
4. Answer `Y` to authenticate Git with your GitHub credentials.
5. Select `Login with a web browser`.
6. Press `ENTER`.
7. Enter the eight digit code from the Terminal into the browser and then click `Authorize github`.

   ![Terminal Authorization Code](images/terminal-auth-code.png)

   ![Screenshot Authorization Code](images/screenshot-auth-code.png)

8. Confirm you are logged in by checking the local configuration settings:

   ```sh
   git config -l
   ```

   ![Terminal Git Configuration](images/terminal-git-config.png)

## Individual Development Loop

When using Git and GitHub as an individual, you will usually follow these steps:

1. Create a new repo for your project.
2. Clone the repo to you computer:

   ```sh
   git clone https://github.com/BrickMMO/tasks.git
   ```

   You can find the URL of a GitHub repo here:

   ![GitHub Repo URL](images/screenshot-repo-url.png)

3. Make changes using your code editor.
4. Add current changes to the main copy:

   ```sh
   git add .
   ```

5. Commit changes to the main copy:

   ```sh
   git commit -am "Describe latest changes"
   ```

6. Push the changes to your GitHub repo:

   ```sh
   git push origin main
   ```

When you are working as an individual, you will not need to create any additional branches. You can simply add and commit all your changes directly to the `main` branch like in the examples above.

> You can get detailed instructions of this process on my [github-demo-branching](https://github.com/codeadamca/github-demo-branching) repo.

## Recommendations

Use Git and GitHub as much as possible! It will force you to practice the skill, you will have a backup of all your work, and your GitHub contributions chart will start turning green!

I would recommend the following:

1. Create a GitHub repo for each class. Put all your class files in that repo. Push the files from class to your GitHub account at the end of each class (or even more often).
2. Create a GitHub repo for each assignment. You can use these repos to hand assignments in. And you can also use a GitHub repo to host a project (we cover that later in the [Deployment Task](/deployment)).
3. If you're learning a new skill, create a repo and store the code there in case you need it for later.

## Consistency

Be consistent! As a developer you should be obsessed with C\consistency!

- Use consistent naming conventions.
- Give your files nice clean names like `logo-github.png`. Not `IMG-20170407-WA0007_resized.jpg`, `IMG-20170407-WA0007.jpg`, or `Copy of IMG-20170407-WA0007.jpg`.
- Organize your files into classes, and weeks, and topics:

  ```
  http5111
  │   README.md
  │
  └── week1
  │   │   headings.html
  │   │   paragraphs.html
  │
  └── week2
      │   images.html
      │   tables.html
      └── images
          │   logo.jpg
  ```

I have written a set of rules for myself (and all BrickMMO development) to follow when working with GitHub repos and README.md files. These rules are called [\_readme](https://readme.codeadam.ca/). You can use these as a starting point.

## Steps

To complete this task, follow these steps:

1. Create a repo for each of your classes.
2. Clone each of those repos to your compauter.
3. Put your class files into those repos.
4. Add, commit, and push those files to your GitHub account.

## Submitting this Task

Submit your class GitHub repo URLs to the **Individuals** assignment in [Blackboard](https://learn.humber.ca/).

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
