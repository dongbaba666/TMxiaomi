# git与gitup

- git：版本控制工具()

- gitup：网站、远程代码管理仓库、贵圈基友平台(交流、学习)


### 集中式  vs  分布式

    集中式缺点：
        必须联网、比较慢、都使用一个中央服务器，有可能会造成数据丢失

    分布式：
        不用联网就能进行版本控制，速度快


###　初始化版本控制状态
    找到要控制的文件目录，鼠标右键，找到Git Bush Here 点击

    打开控制台，输入一个git init

    版本控制都是基于.git这个隐藏文件的，如果不小心把.git文件删除

    查看git状态
        git status

    通过Tab键补全文件

    通过ll或者ls查看目录的文件

    通过上下键来切换刚才输入的命令


    工作区到暂存区
        git add + 指定文件名
        
        git add.   把当前目录都放到暂存区

    
    暂存区到版本区
        git commit -m "备注(你能直接识别的注释即可)"

        快速把工作区的代码放到版本区
            git commit -a -m


