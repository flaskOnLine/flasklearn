# flasklearn
Hello Git

### Git

#### 获取仓库
- git init
    - 在本地自己创建一个仓库
- git clone xxx
    - 从指定位置克隆一个仓库

#### git 操作
- git pull
    - 拉取代码
    - 从远端服务器中拉取代码
- git push
    - 将本地代码推送到服务器
- git add
    - 添加版本追踪
    - 添加文件变更标记
- git commit
    - 将变更提交到本地仓库
    
- git status
    - 查看工作空间状态
- .gitignore
    - git忽略规则
    - 写入这个文件中的文件或目录，git不会进行跟踪
    
#### 指令操作
- git status
    - 查看工作空间状态
    - 如果存在红色和绿色文件，代表还有代码没有进行提交
    - 需要进行追踪， git add
- git add 
    - 添加文件到版本控制中去
    - git add filename
    - git add . / git add -A 添加所有变更文件
- git commit
    - 提交文件到本地仓库
    - 记得写提交日志
- git push
    - 推送代码
    - git push origin main
    - 将当前代码推送到远端对应的分支
