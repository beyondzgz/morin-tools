# morin-tools
morin-tools是一款实用的php开发工具，所提供的工具均在项目生产环境检验使用，希望大神们多提宝贵意见。

##composer安装

`composer requrie morin/php dev-master`

##使用

`use morin\php\Tools;`

带refer的跳转
Tools::href('http://baidu.com');

api接口返回json
Tools::json();

按天向指定目录写日志
Tools::logs();

生成唯一key
Tools::gukey();

生成唯一标识符
Tools::guid();

订单号
Tools::order_num();

curl请求
Tools::curl();

距离当前时间
Tools::passed_time(time() - 60);

随机字符串
Tools::noncestr();

加密
Tools::encrypt();

解密
Tools::decrypt();

递归无限分类
Tools::build_tree();

中文星期几
Tools::week2cn();