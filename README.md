# workflow

Example Git Work Flow

### How to check the head

cd .git
cat HEAD
ref: refs/heads/main

1. git pull
2. git checkout -b feature/my-new-feature
3. git push - u origin feature/my-new-feature

```bash
~/D/M/v/w/w/.git   main  cat refs/heads/main
8894d12bbbb4f61f3d895bf8867d710dabac8d9a
~/D/M/v/w/w/.git   main 
```

### How to use diff

1. git diff HEAD README.md
2. git log --pretty=oneline
