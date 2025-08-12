<style>@import url("//readme.codeadam.ca/readme.css");</style>

## Firebase

Firebase, Inc. is a set of backend cloud computing services and application development platforms provided by Google.

> <small>Wikipedia (n.d.). Firebase. Retrieved March 15, 2024, from [https://en.wikipedia.org/wiki/Firebase](https://en.wikipedia.org/wiki/Firebase)</small>

## Steps

To complete this task, follow these steps:

1. Register for a Google account (if you don't already have one).
2. Go to the [Firebase](https://firebase.google.com/) website and create a project. Provide a project name, you don't need analytics, and click `Create Project`.

   ![Create Project](images/screenshot-firebase-create-project.png)

3. Click `All Products` on the left and choose `Realtime Database`.

   ![Realtime Database](images/screenshot-firebase-realtime-database.png)

4. Click `Create Database`, the default location is fine, so click `Next`. Choose `Start in test mode` and click `Enable`. You database has now been created.

5. In the `Data` tabs, add the following data:

   ![Comments Data](images/screenshot-firebase-data.png)

> Note: The web interface for adding and editing data can take a little getting used to!

6. Click the `Rules` tab and confirm that your rules are wide open:

   ![Firebase Realtime Database rules](images/screenshot-firebase-rules.png)

> Note: Do not leave your rules wide open once your project is ready to go live. These rules allow anyone to view and make changes to your Realtime Database.

7. Using the [Firebase Documentation](https://firebase.google.com/docs/database) and the [firebase-realtime-database](https://github.com/codeadamca/firebase-realtime-) and [firebase-sandbox](https://github.com/codeadamca/firebase-sandbox), display the list of comments from the Realtime Database in an HTML document.

## Submitting this Task

After you have completed your Firebase task, upload a screenshot or a working URL to the **Firebase** assignment in [Blackboard](https://learn.humber.ca/).g

[&#10132; Back to Task List](/)

---

<a href="https://brickmmo.com">
<img src="https://cdn.brickmmo.com/images@1.0.0/brickmmo-logo-coloured-horizontal.png" width="200">
</a>

<script src="https://cdn.brickmmo.com/bar@1.0.0/bar.js"></script>
