Git test：
step1：文件自身的创建是和Git没有关系的，可以用windows的可视化操作创建，也可以用终端指令创建任意文件or目录。
step2：🧊使用命令`git add`将任意一个文件添加到Git仓库，可以认为是暂时提交到Git仓库中的一个池子pool中
step3：🧊使用命令`git commit`将前面add操作添加到池子pool中的文件提交到仓库，因此add只能添加一个文件，但是commit可以一次性将pool中的所有文件提交。
step4：自定义修改文件内容，保存文件内容。
step5：🧊使用命令`git status`查看当前仓库内的文件和上一次commit操作后的文件差异，提示在主分支`On branch master`被修改过了，`Changes not staged for commit:`但还没有准备提交的修改文件`modified:   readme.txt`，推荐你使用命令`git add <file>`去将这个文件添加到pool中以备后续commit，或者使用命令`git restore <file>`去忽略这部分改动。`no changes added to commit`没有新的通过add文件到pool中去用于commit。
step6：创建一个新的分支dev
step7：创建一个新的分支feature1，想想垃圾，还是直接在main上修改文件
step8：分支管理
step9：工作的部分add到pool了
step10：工作了一部分，但是还没add到pool

