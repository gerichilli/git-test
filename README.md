## 1. View config list

```
git config --list
```

## 2. Setup Github username, email

```
git config --global user.name "your user name"
git config --global user.mail "your mail"
```

## 3. Create a project with git

```
git clone "Paste URL here"
```

- Create github repository

  ```
  git clone REPOSITORY_URL
  git status
  git add .
  git commit -m "content"
  git push -u origin main
  ```

- Create local project -> push lên github repository

  - Create repository

  ```
  git init
  git status
  git add .
  git commit -m "content"
  git branch -M main
  git remote add origin https://github.com/gerichilli/git-test.git
  git push -u origin main
  ```
