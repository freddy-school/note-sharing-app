# Note-Sharing App

## mission statement
**Build a community for students to access relevant resources.**

## Getting Started developing 

To begin, you may want to review this [Git Guide](http://rogerdudler.github.io/git-guide/) for a quick introduction to Git basics.

### Workflow
####Tips
- To do a lot to this stuff lazygit is very helpfull
- install `sudo apt install gh` to auth the repo to comit from the coud michn if needed lazygit auth will not work as we have to have 2-factor-auth

1. **Set up a server**: Create a droplet on DigitalOcean using an Ubuntu OS image.
2. **Clone the repository on your local machine**:

    `git clone https://github.com/freddy-school/note-sharing-app`

    Create a new branch to work on:

```
git checkout -b feature/your-feature-name
```

Sync your branch with the latest changes from the main branch:

git pull origin main

Make your changes: After you’ve completed your feature, stage and push your work:
```
git add .
git commit -m "Add description of your feature here"
git push origin feature/your-feature-name
```

Merge your branch with main:
```
git checkout main
git rebase feature/your-feature-name
```
Resolve any conflicts if they arise. Use your preferred Git GUI tool or refer to online resources for assistance.
Push the updated main branch:

git push origin main

On the cloud server (e.g., the DigitalOcean droplet), clone or update the repository:

```
git clone https://github.com/freddy-school/note-sharing-app
```

or, if already cloned:

    git pull origin main

    Run or test the app to ensure everything works as expected.

## Upcoming Features

- [ ] **File Upload**: Enable users to upload files.
- [ ] **File Viewing and Downloading**: Allow users to view and download files.
- [ ] **File Size Check**: Implement a check to ensure uploaded files are within an acceptable size limit.
- [ ] **Usernames**: Add support for usernames to identify users.
- [ ] **Mandatory Upload**: Make uploading files a requirement in certain situations or for certain users.
- [ ] **File Organization GUI**: Provide a user interface to sort files by subject, year level, notes, and revision materials.
- [ ] **Public Metrics and Social Pressure**: Display public metrics to encourage users to upload more files.
- [ ] **Cost Tracker and Donation Page**: Show the running costs of the app and provide a donation page to support its upkeep.
