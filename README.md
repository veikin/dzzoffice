# dzzoffice

### 官方网站:http://dzzoffice.com

### DzzOffice 特点：
* 支持触屏操作，良好支持平板设备访问。
* 继承了windows的使用习惯，操作简单，易上手。
* 云存储、私有云的可视化管理
* 可视化安装向导、安装部署简单
* 大文件上传、批量上传、文件夹上传、拖拽上传
* 多种应用接入方式，强大的扩展性
* 灵活多变的个性化设置


### DzzOffice1.2.5更新说明

1.  增加QQ登陆支持。

2.  增加OneDrive支持（beta)。

3.  阿里云oss增加新节点支持，同时支持自定义节点地址。

4.  消息中心：可以设置成员发布公开消息权限。

5.  更新mime文件类型，增加常用mime支持。

6.  文件下载支持迅雷断点续传。

7.  文件夹左侧列表 按文件夹名称排序。

8.  共享目录权限修改：只要有建立文件夹权限，就可以创建带权限的文件夹（原先只有部门管理员才可以）；

9.  优化迁移工具，自动忽略无法迁移的文件，文件大小限制项不起作用等。

10.  针对Edge浏览器做了一些优化调整。

11.  微信接口类，access_token使用系统缓存，不不再使用memory缓存，防止没有开启memory缓存时过渡消耗使用次数的问题。

12.  用户相关优化：
  
    a.用户姓名支持空格；

    b.用户头像上传使用html5方式，支持移动端；

    c.修复邮箱验证链接无效的bug；

    d:优化独立登陆页手机访问；

13.  增加新建office文档（word,excel,powerpoint)。

14.  文件管理支持搜索用户姓名。

15.  优化文件链接编码方式，有效利用浏览器缓存，提升访问速度。

16.  界面优化：
  
    a.开始菜单按钮，再次点击可以关闭开始菜单。

    b.文件夹左侧列表样式。

17.  用户导入优化：

    a. 为了保证系统管理员的登陆，创始人不允许覆盖导入，会自动调整为增量导入。

    b. 导入用户模板必填项显示为红色字体。

18.  修复Ueditor编辑器的几个问题：
   
    a. 抓取远程图片某些情况不成功；
 
    b. 插入视频会被安全过滤的的问题；
 
19.  修复添加优酷视频无法正确获取缩略图，带参数地址添加后无法播放的问题。

20.  修复更新系统缓存时某些情况下不能正确更新应用的缓存的bug。

21.  修复共享目录移动后造成目录权限不正确的bug。

22.  修复某些操作情况下，用户空间使用量统计错误的bug。

23.  修复ftp权限设置 输入权限码显示不正确的bug。

24.  修复用户资料完成度不起效的bug。

25.  修复分享链接没有正确带入相关参数的bug。

26.  修复机构和用户管理 在IE11下不更新的bug。

27：安全相关：修复若干安全问题。


### 升级方法和步骤

1.  进入您原来的系统，关闭您的站点。进行数据备份

2. 备份文件（如果有程序文件或风格文件的改动）,

3. 下载并解压缩最新版的程序包

4. 程序包解压缩后，可以看到 upload, update 两个目录

5. 上传upload目录中的程序到服务器dzzoffice根目录，如果提示需要覆盖，则选择“是”

6. 将压缩包中 update 目录中的 update.php  程序上传到 install 目录。并删除 install 目录中的 index.php

6. 访问 http://您的域名/install/update.php。

7. 按照程序提示，直至所有升级完毕。删除install/update.php 程序，以免被恶意利用。

8. 进入管理员桌面，更新缓存，并对新功能进行设置和测试。



### 您在升级过程中遇到任何问题，可通过以下途径解决

1. 到我们的讨论区（http://dev.dzzoffice.com）寻求帮助和支持。

2. 商业用户可以根据您购买的服务，使用电话、MSN、QQ、论坛等多种方式寻求技术支持
