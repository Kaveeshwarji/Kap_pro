# Contributing

When contributing your details to this repository, follow the steps mentioned below. If you want to make any other change apart from adding your details, please open an issue, or get in-touch with the maintainers of this repository before making a change.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Pull Request Process

You will be making changes to the `js/participants.js` file in order to add your details.

### STEP 1

**Fork** this repo.  
This will create a copy of this repo under your GitHub account.

![Fork](https://i.ibb.co/cwZFmW5/fork.jpg)

### Step 2

**Clone** your forked copy of this repo down to your local machine:
```bash
git clone https://github.com/<INSERT-YOUR-USERNAME>/Kap_pro.git

# Example
git clone https://github.com/puneetb22/Kap_pro.git
```

### STEP 3

**Change directory** command to get inside the folder where the repo files are:
```bash
cd Kap_pro
```

### STEP 4

**Create a new branch**:
```bash
git checkout -b addname/<INSERT-YOUR-USERNAME>

# Example
git checkout -b addname/puneetb22
```
> In the example, `addname/puneetb22` is the name of the new branch.

> This command creates a new branch and switches to that new branch

### STEP 5

Its time to make the change to `js/participants.js` file by adding your details. Open the file in your text editor.

**Copy** the following template:
```javascript
  {
    name: "<YOUR-NAME>",
    college: "<YOUR-COLLEGE>",
    city: "<YOUR-CITY>",
    github: "<YOUR-GITHUB-PROFILE-LINK>",
    linkedin: "<YOUR-LINKEDIN-PROFILE-LINK>",
    website: "<YOUR-WEBSITE-LINK>",
  },
```

**Paste** it under the last participant's details, something like this:
```javascript
// Example
const participants = [
  {
    name: "Punit Baviskar",
    college: "Amity University Mumbai",
    city: "Pune",
    github: "puneetb22",
    linkedin: "https://www.linkedin.com/in/puneetb22/",
    website: "https://punitbaviskar.me",
  },
  {
    name: "<YOUR-NAME>",
    college: "<YOUR-COLLEGE>",
    city: "<YOUR-CITY>",
    github: "<YOUR-GITHUB-USERNAME>",
    linkedin: "<YOUR-LINKEDIN-PROFILE-LINK>",
    website: "<YOUR-WEBSITE-LINK>",
  },
];
```

Now **edit** it with your own details.

### STEP 6

**Stage** and **commit** changes:
```
git add js/participants.js
git commit -m "add <YOUR-NAME> to participants list"
```

### STEP 7

**Push** changes to your forked repo on GitHub:
```bash
git push origin <BRANCH-NAME>

# Example
git push origin addname/puneetb22
```

> Replace `<BRANCH-NAME>` with the name of the branch you created in STEP 4, such as addname/puneetb22

### STEP 8

Head over to GitHub, and refresh the page. On the repo you should see a new `Compare & pull request` button. Click it.

![Pull request](https://i.ibb.co/3NT428b/7yscx.png)

Now click the `Create pull request` button.

### STEP 9

Thats it! Your part is done!  
Now wait for the maintainer of the repo to mark the PR as `accepted`.

**Congrats on your first PR!**
