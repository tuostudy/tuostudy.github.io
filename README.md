# tuostudy.github.io
# git 命令行，克隆到本地，注意使用你自己的地址哦！！！
git clone https://github.com/tuostudy/tuostudy.github.io.git
# 进入文件夹
cd study.github.io
# 制作页面，注意名称要是index.html
echo "Hello World" > index.html
# 添加到暂存区
git add --all
# commit 
git commit -m "Initial commit"
# push 到远程
git push -u origin master
