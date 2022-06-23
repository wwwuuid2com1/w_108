# w_108
ptcms自动采集小说系统源码 电脑版+手机版
<br/></br>
[下载地址](https://www.uuid2.com/108.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>安装教程：
安装宝塔面板一键安装环境 宝塔：www.bt.cn 必装环境：nginx(apache.iis也可)，mysql,php5.6,必须安装扩展：ZendGuardLoader 脚本解密
ionCube 脚本解密
fileinfo 通用扩展
opcache 缓存器 用于加速PHP脚本
memcached 缓存器

1.上传网站文件到网站目录，新建网站伪静态选择thinkphp
2.新建数据库。导入数据库文件shujuku.sql 温馨提示：数据库有点大，导入的时候有点慢，记得多等会。
3.修改数据库信息/application/common/config.php
4. ‘mysql_master_host’ => ‘localhost’, //数据库地址，本机默认 ‘mysql_master_port’ => ‘3306’, //端口 ‘mysql_master_name’ => ‘sql677a_cn’, //数据库名称 ‘mysql_master_user’ => ‘sql677a_cn’, //数据库用户名 ‘mysql_master_pwd’ => ‘4564e’, //数据库密码
5.注意：如果伪静态正常网站还出现404，打开根目录index.php 在倒数第二行添加： define(‘APP_DEBUG’,true); 网站正常后删除
6.登录网站后台：www.xx.com/admin 用户名：danmeixsw 密码： 123123
7.”系统” – “基本设置” – “数据库” – 把第三步再设置一遍 数据库主机： localhost 数据库端口： 3306 数据库名称： 数据库帐号： 数据库密码：
8..”系统” – “基本设置” – 修改为自己的既可 7.”扩展” – “任务管理” – “任务管理” – “全选” – “恢复” -开启自动采集
9.”扩展” – “模块管理” – “网站地图” – 修改为自己的既可
10.”扩展” – “模块管理” – “手机地图” – 修改为自己的既可
11.”用户” – 管理员密码修改<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202105/98b007d465.jpg" alt="ptcms自动采集小说系统源码 电脑版+手机版"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/98b007d942.jpg" alt="ptcms自动采集小说系统源码 电脑版+手机版"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/8e60fe2798.jpg" alt="ptcms自动采集小说系统源码 电脑版+手机版">
