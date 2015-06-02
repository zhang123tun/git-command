# git command
git命令

 cygwin安装git ssh gettext
 ssh-keygen 生产key
     .ssh 里面的“私有key”文件要改成 文件所有者只读的形式



git config --global user.name 你的名字
git config --global user.email 你的邮箱
git config --global color.ui true
git config --local core.fileMode false
git config --global core.quotepath false : Linux使用git的时候，如果添加的文件是中文名字，会显示为转义符，虽然不影响上传的结果，但是看着很不方便。这个时候可以使用 这个命令，来禁用对于大于0x80的字符进行转义的功能，这样就可以显示出中文文件名了。

git config -l 列出所有配置
git log --stat 

git add ./git add filename
git commit -m "注释"
git push -u origin master 第一次提交
git push origin master 之后提交
