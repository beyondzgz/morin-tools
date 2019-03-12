# morin-tools
morin-tools是一款实用的php开发工具，所提供的工具均在项目生产环境检验使用，希望大神们多提宝贵意见。

## composer安装

`composer requrie morin/php dev-master`

## 使用

`use morin\php\Morin;`

带refer的跳转
Morin::href('http://baidu.com');

api接口返回json
Morin::json();

按天向指定目录写日志
Morin::logs();

生成唯一key
Morin::gukey();

生成唯一标识符
Morin::guid();

订单号
Morin::order_num();

curl请求
Morin::curl();

距离当前时间
Morin::passed_time(time() - 60);

随机字符串
Morin::noncestr();

加密
Morin::encrypt();

解密
Morin::decrypt();

递归无限分类
Morin::build_tree();

中文星期几
Morin::week2cn();