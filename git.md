# git使用

## 配置git账户
    
    git config --list #查看当前配置
    git config --list --local #查看当前仓库配置
    git config --list --global #查看全局配置

## 配置全局账户（配置文件位于 ~/.gitconfig中）
    
    git config --global user.name "your_name"   # 如果是提到github上，your_name最好是你的github账户的名字
       
    git config --global user.email "your_email@example.com"  # 如果是提到github上，your_email@example.com最好是你的github账户的邮箱
        

## 配置本地仓库账户 (配置文件位于当前仓库目录的.git/config中）
        
    git config --local user.name "your_name_in_company"  # 如果是提到github上，your_name最好是你的github账户的名字
    
    git config --local user.email "your_company_email@example.com" # 如果是提到github上，your_email@example.com最好是你的github账户的邮箱 
    

## config的三个作用域

    git config --local  local只对某个仓库有效
    git config --global global对当前用户所有仓库有效
    git config --system system对系统所有登录用户有效
    
##
    [常用命令](https://zhuanlan.zhihu.com/p/384819351)