# 豆组筛选
豆瓣小组爬虫微信小程序版本，支持自定义小组，多关键词置顶／过滤、中介过滤


## 预览
微信小程序审核后面通过不了了，所以扫码看到的是旧版本的小程序（git tag 0.4.0）<br/>
![截屏](https://github.com/jiahui92/taro-douban-group-filter/blob/master/assets/qrcode.jpg)<br/>
<img src="https://github.com/jiahui92/taro-douban-group-filter/blob/master/assets/s-index.png" style="height: 320px;margin-right: 10px;" />
<img src="https://github.com/jiahui92/taro-douban-group-filter/blob/master/assets/s-content.png" style="height: 320px;" />


## 启动
* yarn
* yarn dev:weapp

## Todo
* [x] 小组管理
* [x] 置顶名单
* [x] 白名单
* [x] 中介过滤
* [x] pages/content
* [x] pages/help
* [ ] Input组件优化
* [ ] MAX_PAGE等抽取到配置中，方便以后在设置中调整
* [ ] 收藏
* [ ] 小组id显示为小组名称
* [ ] 一键导入小组（根据用户主页链接or用户id）
* [ ] 中介过滤规则
  * site:douban.com 18591619696
  * 豆瓣帖子
  * 注册时间



## bug
* [ ] 支付宝的rich-text不展示图片（可能是配置问题）
* [ ] 支付宝真机运行request请求html会报json解析错误

