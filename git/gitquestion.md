## git gui 中文乱码解决方案
在git的配置文件**[.gitconfig]**中设置utf8编码<br>
```<br>
[gui]<br>
	encoding = utf-8

```
## git commit报错
### 错误打印<br>

```<br>
$ git commit -m "add markdown dir"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"

  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'djj@DESKTOP-K7I2PRI.(none)')

```
### 解决方案
在git的配置文件**[.gitconfig]**中配置user<br>
<div style="background:#000; color:#FFF">
[user]<br>
	email = 1015591892@qq.com<br>
    name = ivy<br>
</div>