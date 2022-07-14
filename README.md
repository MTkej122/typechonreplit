# typechonreplit
在Replit部署Typecho博客 + [Butterfly主题移植](https://blog.wehaox.com/archives/typecho-butterfly.html#cl-3 )


教育版：

将以下代码粘贴至Replit Shell后回车

`git clone https://github.com/Sayafx/typechonreplit.git && mv -b typechonreplit/* ./ && mv -b typechonreplit/.[^.]* ./ && rm -rf *~ && rm -rf typechonreplit`

当加载完 Detected change in environment, reloading shell...
在Shell输入`sh main.sh`初始化，初始化完成后点击绿色 ▶ Run 运行

默认请使用原生sqlite数据库

Fork自[valetzx/typechonreplit](https://github.com/valetzx/typechonreplit)，由Sayafx修改完善。