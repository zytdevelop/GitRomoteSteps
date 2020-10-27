# 实验楼在线环境使用Github

1. 建立远程仓库
2. 关联在线环境和远程仓库
    - ssh-keygen 生成公钥
    - .pub文件就是生成的公钥
    - 在Github中找到  Settings ->SSH and GPG keys ->new SSH key ->    复制公钥字符串到key文本框
3. 安装git工具 
    - $sudo apt-get install git -y
4. 配置用户名与邮箱
    - $git config --global user.name "你的用户名"
    - $git config --global user.mail "你的邮箱"
5. 检验是否连接成功
    - $ ssh git@github.com
验证是不是添加成功。
6. 克隆仓库到本地
    - $git clone + 仓库的SSH(使用SSH验证以后,不需要每次提交或者下拉操作都输入一次邮箱和密码)


# GIT 命令
- git add  添加文件
- git rm 删除文件
- git reset 撤销操作
- git commit -m "提交事务时的备注"
- git fentch 查看仓库改动
- git pull 下拉仓库同步
