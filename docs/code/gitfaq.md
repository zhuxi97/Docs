# 常用命令

## git

- gitignore

增加.gitignore 文件，*.log 等 

git add .gitignore
git commit -m "Add .gitignore"

- gitpush

git status

git add .

git commit -m "修改html"

git push origin main 

## docify

- 发布


(base) zhuxi@MacBook-Pro-4 Docs % docsify serve docs          

Serving /Users/zhuxi/zhuximba/Codexproject/Docs/docs now.
Listening at [http://localhost:3000](http://localhost:3000)

可以预览网站

## git的一些命令解释

```bash
# 查看本地改动
git status

# 查看具体改了什么
git diff

# 查看提交历史
git log --oneline --graph -10

# 拉取远程最新代码
git pull origin main

# 推送本地提交到远程
git push origin main

# 查看本地是否有未推送的提交
git log origin/main..HEAD --oneline

# 查看远程是否有本地未拉取的提交
git fetch origin && git log HEAD..origin/main --oneline
```