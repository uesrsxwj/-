# 小红书爬虫
小红书爬虫/js逆向实现/可抓取搜索数据/评论数据/发送评论/发送私信/自动点赞收藏等
## 实现过程
- 通过js逆向破解前端 "x-s": x_s, "x-t"，"x-s-common"，"x-b3-traceid"，"searchId"等参数
- 调用python进行api封装
## 功能特性
- 爬虫搜索内容
- 爬取笔记详情
- 爬取笔记图片或者视频
- 采集用户评论（包含二级评论）
- 自动发送评论
- 自动关注，点赞，收藏
- 发送私信
## 基础设置
- 需要用户cookie（账号信息）值进行本账号爬取或发布
- 保存可支持数据库和execl，csv保存
## 展示
- ![爬虫运行示例](images/spider_example.png)
- ![爬虫运行示例](images/spider_example.png)
### 环境要求
- Python 3.x
- requests：用于发送HTTP请求
- execjs：调用js文件
