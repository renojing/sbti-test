# 添加远程仓库地址（把下面的 YOUR_USERNAME 改成你的 GitHub 用户名）
git remote add origin https://github.com/renojing/sbti-test.git

# 拉取远程仓库内容并合并
git pull origin main --allow-unrelated-histories

# 推送到 GitHub
git push -u origin main
