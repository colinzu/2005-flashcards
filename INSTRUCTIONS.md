# Deploying to GitHub Pages

Follow these steps to deploy the flashcards application to your GitHub account:

## 1. Create a new GitHub repository

1. Go to [GitHub](https://github.com/) and sign in to your account
2. Click on the "+" icon in the top-right corner and select "New repository"
3. Name your repository (for example, "cits2005-flashcards")
4. Make it public or private as you prefer
5. Click "Create repository"

## 2. Push the local repository to GitHub

Follow the instructions on the GitHub page to push an existing repository. It will look something like this:

```
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your actual GitHub username and repository name.

## 3. Set up GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select the branch you want to deploy (usually "main")
5. Click "Save"

## 4. Access your website

After a few minutes, your site will be available at:
`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY`

For example: `https://johndoe.github.io/cits2005-flashcards`

## Making updates

Whenever you make changes to your application:

1. Commit your changes: `git commit -am "Description of changes"`
2. Push to GitHub: `git push`

Your site will automatically update with the new changes after a few minutes. 