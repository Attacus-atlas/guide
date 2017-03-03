# guide
回到git_project那里，在这个目录上继续右击，点击Git Bash，现在就出现一个和开始使用那个Git Bash一样的窗口，不过现在是在git_project目录下使用了，现在输入如下命令：

git remote add origin git@github.com:bxxfighting/NowToDo.git

其中bxxfighting是我在网站上注册时使用的用户名，NowToDo.git是我为这个项目建立的另一个仓库名，在网站上显示是这样的



由于我建立仓库的时候创建README.md之时，已经算一次提交了，我需要先在本地同步一下仓库的内容,命令如下：

git pull git@github.com:bxxfighting/NowToDo.git

下面就要把我们本地的上传到仓库上去了，首先执行增加命令，如下：

git add .

add后面加了一个点，是想要提交所有文件，如果想提交指定的文件，可以写文件名，执行完增加命令后，要执行提交命令，如下：

git commit –m “NowToDo_v1.0版本”

-m后面跟提示信息，这个提示信息是一定要写的，不仅是规则，同时也方便我们记录我们提交的过程，写清晰为什么提交或修改了什么是非常有用的，提交完成后，我们就要把它推送到远程仓库上去了，命令如下：

git push git@github.com:bxxfighting/NowToDo.git


