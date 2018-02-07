# 健身圈
    一个集电商与社交与一体的俱乐部平台。用户可以在app里寻找中意的健身课程，交上兴趣相符的朋友，还可以发表心情。
    由于个人开发者无法获得使用支付宝或者微信支付的调用权限，与购买相关的功能均无法使用。例如订单，购买，评论商家等。
    测试版上面的俱乐部和课程图片是随意上传的，也就是图文无关。
    体验仅限安卓版,安装包在android/jian-shen-quan.apk
    由于短信接口剩余使用次数不足，可能无法注册用户,请使用下面账号进行体验
    账号：15502627152 密码：123456
    账号：13367719632 秘密：123456

### 演示视频
[安卓(android)](https://pan.baidu.com/s/1o8Shfho) 测试使用手机：小米6 提取密码: rd2z
<br>
[苹果(ios)](https://pan.baidu.com/s/1sliFJ3J) 测试使用手机：iphone7 plus 提取密码: xpmy
<br>
[俱乐部管理(web)](https://pan.baidu.com/s/1cFEy4Y) 测试使用浏览器：safari 提取密码: 4vxb

### 主要技术
    后台管理
    使用angular4作为核心框架
    使用ngrx进行状态管理
    使用ng-zorro作为基本UI
    使用百度地图进行定位
    使用docker部署

    移动端
    使用angular4 + ionic3作为核心框架
    使用ngrx进行状态管理
    使用sockjs + stompjs进行即时通讯
    使用百度地图进行定位

    服务端
    使用spring boot作为核心框架
    使用spring security整合jwt进行权限控制
    使用spring jpa进行数据库操作
    使用spring data rest进行常用查询
    使用spring websocket实现即时通讯
    将上传的文件保存到cos（腾讯云的对象存储）
    使用网易云SMS实现短信发送

    使用docker部署
    服务端(微服务版)
    使用spring cloud作为核心框架
    使用spring cloud eureka进行服务注册与发现
    使用spring cloud zuul构建网关服务
    使用spring cloud feign进行微服务调用
    使用docker compose统一部署各个微服务

## 安卓(android)
如果无法显示图片请下载后查看(图片位于android/images)
<br>
![android1](https://github.com/LieRabbit/jianshenquan-show/blob/master/android/images/android1.png)
![android2](https://github.com/LieRabbit/jianshenquan-show/blob/master/android/images/android2.png)
![android3](https://github.com/LieRabbit/jianshenquan-show/blob/master/android/images/android3.png)
![android4](https://github.com/LieRabbit/jianshenquan-show/blob/master/android/images/android4.png)
![android5](https://github.com/LieRabbit/jianshenquan-show/blob/master/android/images/android5.png)

## 苹果(ios)
如果无法显示图片请下载后查看(图片位于ios/images)
<br>
![ios1](https://github.com/LieRabbit/jianshenquan-show/blob/master/ios/images/ios1.png)
![ios2](https://github.com/LieRabbit/jianshenquan-show/blob/master/ios/images/ios2.png)
![ios3](https://github.com/LieRabbit/jianshenquan-show/blob/master/ios/images/ios3.png)
![ios4](https://github.com/LieRabbit/jianshenquan-show/blob/master/ios/images/ios4.png)
![ios5](https://github.com/LieRabbit/jianshenquan-show/blob/master/ios/images/ios5.png)

## 俱乐部管理系统(web)
如果无法显示图片请下载后查看(图片位于web/images)
<br>
![登陆](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/login.png)
![首页](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/home.png)
![俱乐部](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/club.png)
![俱乐部--编辑上](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/club-edit1.png)
![俱乐部--编辑下](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/club-edit2.png)
![商品](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/commodities.png)
![商品--编辑上](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/commodity-edit1.png)
![商品--编辑下](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/commodity-edit2.png)
![货品](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/goods.png)
![货品--编辑](https://github.com/LieRabbit/jianshenquan-show/blob/master/web/images/goods-edit.png)
