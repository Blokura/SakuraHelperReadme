---
description: 本章将讲述的是网易云音乐登录问题
---

# 网易云音乐

## 手机号方式登录

如果您希望以手机号方式登录网易云音乐，可直接在程序内打开网易云配置，并在上方登录框中输入您的网易云音乐绑定手机号和密码。

## 其他方式登录

1.浏览器中打开网址 https://music.163.com/

2.在网页右上角登录，并且返回至网站主界面

3.按下F12键，打开开发人员工具，选择Network（中文版为网络）

![Network](../.gitbook/assets/image%20%289%29.png)

4.浏览器地址框中输入网址 [https://music.163.com/weapi/point/dailyTask](https://music.163.com/weapi/point/dailyTask) 并回车

5.在开发人员工具中找到dailyTask

![dailyTask](../.gitbook/assets/image%20%283%29.png)

6.下拉看到cookie，将MUSIC\_U以及\_\_csrf值复制下来

![MUSIC\_U&amp;\_\_csrf](../.gitbook/assets/image%20%2811%29.png)

7.打开助手文件夹，找到【网易云音乐】文件夹（没有可以手动创建），然后新建cookie.txt文件，将刚刚复制的MUSIC\_U和\_\_csrf复制进去即可。

![](../.gitbook/assets/image%20%2815%29.png)

{% hint style="info" %}
注意保存格式如上图 直接复制下来黏贴就是正确格式来的!!

格式：MUSIC\_U=xxxxxxx;\_\_csrf=xxxxxx;

xxxxxx为你自己的数据！
{% endhint %}





