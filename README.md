# Project: Parrot

[![GitHub forks](https://img.shields.io/github/forks/hunterhug/pigeon.svg?style=social&label=Forks)](https://github.com/hunterhug/pigeon/network)
[![GitHub stars](https://img.shields.io/github/stars/hunterhug/pigeon.svg?style=social&label=Stars)](https://github.com/hunterhug/pigeon/stargazers)
[![GitHub last commit](https://img.shields.io/github/last-commit/hunterhug/pigeon.svg)](https://github.com/hunterhug/pigeon)

![](/logo.gif)

友好的EDM营销工具. SEE: [https://github.com/hunterhug/pigeon](https://github.com/hunterhug/pigeon)

|执行程序|操作系统|
|----|----|
|edm64_linux   |Linux 64位操作系统|
|edm32_linux |Linux 32位操作系统|
|edm64.exe |Window 64位操作系统|
|edm32.exe |Window 32位操作系统|
|edm_mac|Mac操作系统|

Please come [here](https://github.com/hunterhug/pigeon/releases) to download software.

请到这里下载软件: [点我](https://github.com/hunterhug/pigeon/releases)

## How To Use?(如何使用)

1. Edit your Email auth config in `config.txt`.
2. Edit `email.txt` by row which you send to.
3. Edit `subject.txt` which is the content you want to send.
4. If you want attach file, you can put those file in `attach`(Suggest .tar)
5. Click `edm.exe`(this is in the same document with *.json)

-----

1. 编辑`config.txt`, 主要是帐号密码
2. 编辑`email.txt`, 邮箱地址按行写, 我们要发邮件到这些邮箱
3. 编辑`subject.txt`, 这是邮件的正文(格式可以是HTML)
4. 如果想上传附件, 请将文件放在`attach`文件夹.(建议压缩成一个文件比较好)
5. 点击`edm.exe`运行.(该执行文件必须与配置文件在同一文件夹下, 下一次运行前记得清空`attach`文件夹并修改正文`subject.txt`)

## How To Config(如何配置)

### 1.`config.txt`

```
smtp-mail.outlook.com
587
xxxxxx@live.com
password123
```

Four row(四行): 

1. `smtp host`
2. `smtp port`
3. `your email account`
4. `password`. 

第一二行是`smtp`配置主机和端口, 第三第四行是邮箱帐号密码.

|服务|SMTP主机|SMTP端口|备注|测试情况|
|----|----|----|----|----|
|Outlook(建议使用微软!)|smtp-mail.outlook.com|587|邮箱密码|测试成功Success|
|腾讯企业邮箱|smtp.exmail.qq.com|465|密码: 请到设置-账户生成`客户端专用密码`|测试成功Success|
|Gmail|smtp.gmail.com|465|启用[IMAP](https://mail.google.com/mail/u/0/#settings/fwdandpop),同意[不安全应用](https://myaccount.google.com/lesssecureapps)|测试中(有墙)|
|QQ Mail|smtp.qq.com|465|密码: 请设置[授权码](http://service.mail.qq.com/cgi-bin/help?subtype=1&&id=28&&no=1001256)|待测

### 2.`email.txt`

```
wanggang.wg@alibaba-inc.com
yangbo.xuyb@alibaba-inc.com
```

Email by row. 邮箱按行写入!

### 3.`subject.txt`

```
This is test subject, then by row 这是一个主题, 下面空一行

This is context for test 这是一个正文
```

As you look above. 写完主题后空一行, 写正文. 支持HTML


# Support

如果你觉得项目帮助到你,欢迎请我喝杯咖啡

微信
![微信](https://raw.githubusercontent.com/hunterhug/hunterhug.github.io/master/static/jpg/wei.png)

支付宝
![支付宝](https://raw.githubusercontent.com/hunterhug/hunterhug.github.io/master/static/jpg/ali.png)


# License

啥啥版权都没有，随便用！！！