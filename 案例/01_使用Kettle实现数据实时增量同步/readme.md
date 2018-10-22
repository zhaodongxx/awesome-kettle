# 使用Kettle实现数据实时增量同步

## 与案例对应的文章
[**使用Kettle实现数据实时增量同步**](https://blog.csdn.net/dora_310/article/details/80511793)

## Usage

这个案例实际应用还需要以下步骤：
1. 修改数据库链接   在主对象/转换/DB链接/
3. 运行sql代码，在源数据表生成需要同步的数据表和数据
3. 启动

> 使用发送邮件组件需要自行配置, 前端时间大家直接使用我的配置，往我的邮箱里发送报错邮件，我是一脸懵逼的，所以我把邮箱密码删除了

> sql代码在`./im_message.sql`


**如果启动有问题，欢迎提[issue](https://github.com/zhaodongxx/awesome-kettle/issues)**