# gitskills
- 有点兴奋
- 功能很棒，哈哈

# 学习

## 先从origin克隆下来，
 - 遇到提示
 ```
    The authenticity of host 'github.com (192.30.253.113)' can't be established.
    RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
    Are you sure you want to continue connecting (yes/no)?
 ```   
 - 输入yes，就ok了。哈哈

## 本地建立git然后关联到github
- 在github上新建立的仓库不要初始化README.md文件
- 步骤：
 - 1. git remote add origin git@github.com:jackros1022/gitskills.git
 - 2. git push -u origin master
  - 第一次推送master分支，加参数-u
 - 3. 以后更新同步直接 git push origin master 
 

## 设置忽略文件

 - 直接在.git目录下填写文件夹
 - 比如build/ 、devel/ 就可以了。
  - 不需要加目录后加*，也不需要绝对路径。
  - 已经修改啦

