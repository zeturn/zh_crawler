# zh_crawler

一个自动爬取知乎（zhihu.com）热搜用于研究学习的爬虫  

A crawler that automatically crawls hot searches on station 知乎 (zhihu.com) for research and learning purpose.

## 运行计划\run plan

|  计划爬取的项目   |  存储位置（相对） | 访问链接 | 更新模式 | 时间表（utc）|
|  -----  | --------- |--------- | ------- | ----  |
| 热搜\hot research  | [zh_crawler/hotsearch/hotresearch/](https://github.com/zeturn/zh_crawler/tree/main/hotsearch/hotresearch) | <https://www.zhihu.com> | 每小时更新\every hour | 0 * * * * |
| 全站\hot question | [zh_crawler/hotquestion/hotquestion/](https://github.com/zeturn/zh_crawler/tree/main/hotquestion/hotquestion) | <https://www.zhihu.com/hot> | 每小时更新\every hour | 0 * * * * |

## 其他项目\Other projects

[b_crawler](https://github.com/zeturn/b_crawler)

## 更新状态\update status

正在更新中...  

in progress...

如果您有希望增加的爬取项目，请提出issues。

Please make an issue if you have any crawler you would like to add.


## 注意事项\Precautions

本仓库内的.py(python)\.sh\.md为后缀的文件遵照MIT协议。  

本仓库内存储.txt文件中内容是爬取到的，这些内容仅供学习交流，严禁用于商业用途。  

  
  
The .py(python)\.sh(shell)\.md(markdown) files in this library are under the MIT agreement.  

The content in the .txt file stored in this library is obtained from crawler. Contents in such file are only provided for learning and communication, and are strictly prohibited for commercial use.

如果我们的爬取行为侵犯到了您的合法权益，请使用官方的电子邮件联系 meaninglesstech@outlook.com


## 参考\reference

https://github.com/justjavac/zhihu-trending-top-search
https://zhuanlan.zhihu.com/p/463667802  
在此感谢
