git 初始化  ssh方式
echo "# demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:diaolinyu/demo.git
git push -u origin main

git 命令
git push origin HEAD:refs/for/master
git reset --soft origin/master
git reset --soft commitId


