Postgresql
===
### 1.Can't access to file « $libdir/pgrouting-2.4 » no such file or directory

可能原因：postgresql数据库升级(使用apt等系统软件包管理工具升级)后，pgrouting等相关插件的so文件没有得到更新

解决方法：卸载插件重新安装
> DROP EXTENSION pgrouting; CREATE EXTENSION pgrouting;

或者 使用手动更新命令更新到最新版本
> ALTER EXTENSION pgrouting UPDATE TO '2.5.2'
