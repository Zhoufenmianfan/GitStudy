Git test：
step1：文件自身的创建是和Git没有关系的，可以用windows的可视化操作创建，也可以用终端指令创建任意文件or目录。
step2：🧊使用命令`git add`将任意一个文件添加到Git仓库，可以认为是暂时提交到Git仓库中的一个池子pool中
step3：🧊使用命令`git commit`将前面add操作添加到池子pool中的文件提交到仓库，因此add只能添加一个文件，但是commit可以一次性将pool中的所有文件提交。
step4：自定义修改文件内容，保存文件内容。