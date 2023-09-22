---
title: 通过 WebDAV 同步附件
date: 2023-06-28 21:14:03
updated: 2023-09-22 21:38:54
---

# 通过 WebDAV 同步附件

::: tip

国内可用的 WebDAV 网盘只有坚果云。OneDrive，iCloud，百度网盘等等主流网盘均不支持。

:::

1. 注册坚果云账号：

    <https://www.jianguoyun.com/d/signup>

    ::: tip

    不需要下载任何客户端！！

    :::

2. 登录后点击右侧用户名=>账户信息

    ![image](../assets/20230922T210515/20230922T210515_70236.png)

3. 选择安全选项，下滑到底，点击添加应用。
    ![image](../assets/20230922T210515/20230922T210515_42997.png)

4. 完成后，记录下生成的密码。
    ![image](../assets/20230922T210515/20230922T210515_49304.png)

5. 打开 Zotero, `编辑` —— `首选项` —— `同步` —— `文件同步`，`使用 Zotero` 改成 `WebDAV`，并填写你的坚果云的服务器地址：`https://dav.jianguoyun.com/dav` ，用户名是坚果云账号，密码是一开始设置的应用密码（非坚果云账号登录密码），设置好后点击 `Verify` > `Server` 即可。

    ![image](../assets/20230922T210515/20230922T210515_91270.png)

到此处，坚果云的同步设置就完成了。