# Note-Sharing App

## Getting Started

To begin, you may want to review this [Git Guide](http://rogerdudler.github.io/git-guide/) for a quick introduction to Git basics.

### Workflow

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
