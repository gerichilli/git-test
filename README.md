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

## 3. Https vs SSH

```
ssh-keygen -t ed25519 -C "your_email@example.com"
```

- Go and find .pub file -> Copy the key to github SSH setting

## 4. Common Git Command

### Git flow

- Working directory -> Staging Area `git add`
- Staging Area -> .git directory (Repository) `git commit`
  -m
- .git directory -> Remote Area `git push origin master`

### Common commands

- `git config`
- `git init`
- `git clone`
- `git status`
- `git commit`
- `git push`

### Teamwork Commands

- `git pull` = `git fetch` + `git merge`
- `git merge`
- `git checkout -b new-feature`: tạo một branch mới có tên là new-feature và switch đến branch mới này
- `git branch`: Check list các branch
