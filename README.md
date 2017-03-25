# 尝试开发一些chrome小插件

> 开发一些简单的chrome插件实用小程序

基本结构：
manifest.json 是chrome插件的入口配置文件，chrome会先读取入口配置文件，根据配置文件，决定加载用户自定义的程序；

* browser_action 决定插件的行为
* * default_popup 是插件弹出的气泡内容，默认是一个html页面，通过js代码实现应用逻辑
* * default_icon 是插件在浏览器地址了显示的icon
* permissions是插件要请求获得的浏览器权限

## kaiyan-videos

> 简单的练手应用，获取开眼视频，并且展示前四个当日更新的视频

## screen-capture

> 练手应用，调用chrome接口，实现截屏功能

## color-picker

> 一个简单的屏幕取色器
