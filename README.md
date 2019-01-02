![mahua](http://upload-images.jianshu.io/upload_images/259-0ad0d0bfc1c608b6.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# zhazhaqiang

## zhazhaqiang是什么?
一个基于微信开发者工具开发的高内聚低耦合的微信小程序开发框架

向zhazhaqiang的开发者Michael Chan致敬!

## zhazhaqiang有哪些功能？

* 首页`列表和搜索`功能
    *  各种分类知识问答
    *  关键字模糊查询搜索
* 活动`列表和搜索`功能
* `发现`模块支持周边搜索
* `个人中心`功能

## 更新记录
2018.12.29 -- v0.0.1:提交0.0.1版本并完成框架搭建和核心功能模块编写

## 使用方式
1.0 下载zhazhaqiang直接运行

## 注意事项
1. 熟悉web前端基本语法，微信开发者工具使用

## 有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流
* 邮件(951123604@qq.com)
* QQ: 951123604
* weibo: [@xiaoqiang是个小疯子](https://weibo.com/p/1005055732746027/home?from=page_100505&mod=TAB#place)
* twitter: [@CharlesDing8](https://twitter.com/CharlesDing8)

## 捐助开发者
在兴趣的驱动下,写一个`免费`的东西，有欣喜，也还有汗水，希望你喜欢我的作品，同时也能支持一下。
当然，有钱捧个钱场（右上角的爱心标志，支持支付宝和PayPal捐助），没钱捧个人场，谢谢各位。

## 感激
感谢以下的项目,排名不分先后

* [mou](http://mouapp.com/) 
* [ace](http://ace.ajax.org/)
* [jquery](http://jquery.com)

# 你的Star是我更新的动力，使用过程如果有什么问题或者有什么新的建议，可以issues,我会及时回复大家！

``` javascript
{
  "pages":[
    "pages/index/index",
    "pages/activity/activity",
    "pages/found/found",
    "pages/personalCenter/personalCenter"
  ],
  "window":{
    "backgroundTextStyle":"light",
    "navigationBarBackgroundColor": "#0068C4",
    "navigationBarTitleText": "渣渣辉说芜湖",
    "navigationBarTextStyle": "white",
    "backgroundColor": "#eeeeee",
    "enablePullDownRefresh": true,
    "onReachBottomDistance": 50
    
  },
  "tabBar": {
    "color": "#626567",
    "selectedColor": "#2A8CE5",
    "backgroundColor": "#FBFBFB",
    "borderStyle": "white",
    "list": [
      {
        "pagePath": "pages/index/index",
        "text": "首页",
        "selectedIconPath": "images/homeSelect.png",
        "iconPath": "images/home.png"
      },
      {
        "pagePath": "pages/activity/activity",
        "text": "活动",
        "selectedIconPath": "images/activitySelect.png",
        "iconPath": "images/activity.png"
      },
      {
        "pagePath": "pages/found/found",
        "text": "发现",
        "selectedIconPath": "images/foundSelect.png",
        "iconPath": "images/found.png"
      },
      {
        "pagePath": "pages/personalCenter/personalCenter",
        "text": "个人中心",
        "selectedIconPath": "images/personalCenterSelect.png",
        "iconPath": "images/personalCenter.png"
      }
    ]
  },
  "networkTimeout": {
    "request": 10000,
    "downloadFile": 10000
  },
  "debug": true
}

```

