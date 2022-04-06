# 登录页面
###  作者：闰月飞鸟；时间：2020/03/14
###  实现功能
---
 1. 从全局配置的theme中获取，背景图片和logo
 2. 开发模式下，下标显示开发模式。
 3. 登录页面初始化的时候需要重置token，并关闭token计时器。
 4. App,自动版本检查，对比服务器版本和本地版本，不同时出更新确认提示，并在确认后更新
 5. 第一次登录弹出使用协议，选择不再提醒后不再主动 也可以单独点开阅读。只有点击同意才能继续登录使用
 6. 登录验证，登录成功后
	- 将token,expireDate存入store中token模块，用在main.js开启定时器
	- 加载菜单和用户信息，并存入store中home模块和user模块--->重定向到首页，
 7. 忘记密码，跳转手机验证--->手机验证成功--->修改密码！
 8. 自由切换登录方式，短信验证登录与账户密码登录
 9. 初次登录或未点击“不再提醒”时，弹出协议声明。也可以主动阅读。
 
 
 