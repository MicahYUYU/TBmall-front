## TBMall-Front
### 基于Vue开发的TBMall商城前台页面
### 项目已部署，在线Demo
- 前台商城：http://xmall.exrick.cn/
- 后台管理系统：http://xmadmin.exrick.cn/
### 感谢 [Exrick](https://github.com/Exrick) 的开源 [xmall](https://github.com/Exrick/xmall-front) 项目提供前端页面及框架支持
### 后端全部重新开发接口，实现后台系统管理，后端接口项目请跳转至 [TBMall](https://github.com/Cisen07/TB) 项目仓库查看
### 新增与优化
- [x] 优化页脚、增加商品搜索框组件
- [x] 优化登录注册界面
- [x] 新增搜索页面，实现高亮分页搜索
- [x] 新增捐赠页面，捐赠列表显示
- [x] 全部商品页面实现分页
- [x] 优化订单详情，实现查看订单进度，可对订单进行处理
- [x] 实现生成订单接口、优化地址管理编辑选择
- [x] 实现查看个人订单分页
- [x] 首页升级！重构首页，后台可配置，包括3D轮播图
- [x] 新增分类查看品牌周边等
- [极验验证码移除文档](https://github.com/Exrick/xmall/wiki/%E6%9E%81%E9%AA%8C%E7%A7%BB%E9%99%A4%E6%96%87%E6%A1%A3)
    
![](https://i.loli.net/2018/07/21/5b52e192366a0.jpg "首页")

![](https://i.loli.net/2018/07/22/5b5447c0f2b69.jpg "页脚")

![](https://i.loli.net/2018/07/22/5b5447e84edd9.jpg "搜索框组件")

![](https://i.loli.net/2018/07/22/5b5448040ff95.jpg "搜索结果")

![](https://i.loli.net/2018/07/22/5b54489e41551.jpg "分页")

![](https://i.loli.net/2018/07/22/5b54482cca360.jpg "订单详情")

![](https://i.loli.net/2018/07/22/5b5448494d6b6.jpg "订单进度")

![](https://i.loli.net/2018/07/22/5b54486109ade.jpg "登录界面")
    
### 所用技术

- Vue 2.x
- Vuex
- Vue Router
- [Element UI](http://element.eleme.io/#/zh-CN)
- ES6
- webpack
- axios
- Node.js
- 第三方SDK
    - ~~[极验Test-button人机验证码](http://www.geetest.com/Test-button.html)~~ 因其收费详见[极验验证码移除文档](https://github.com/Exrick/xmall/wiki/%E6%9E%81%E9%AA%8C%E7%A7%BB%E9%99%A4%E6%96%87%E6%A1%A3)
- 第三方插件
    - [hotjar](https://github.com/Exrick/xmall/blob/master/study/hotjar.md)：一体化分析和反馈
    - ~~[搜狐畅言评论插件](http://changyan.kuaizhan.com/)~~ 垃圾广告评论插件 现已更换 [Gitment](https://github.com/imsun/gitment)

### 本地开发运行
- 启动后端 [xmall](https://github.com/Exrick/xmall) 项目后，在 `config/index.js` 中修改你的后端接口地址配置
- Gitment评论配置见 [Gitment](https://github.com/imsun/gitment) 使用到的页面为 `thanks.vue`
- `index.html` 中复制粘贴替换你的 [hotjar](https://github.com/Exrick/xmall/blob/master/study/hotjar.md) 代码
- 若不启动后端项目，勉强预览运行此前端项目可尝试注释掉 `src/main.js` 中第 `8、10、39-61` 行代码
- 在项目根文件夹下先后执行命令 `npm install` 、 `npm run dev`
- 商城前台端口默认9999 http://localhost:9999
## 部署
- 先后执行命令 `npm install` 、 `npm run build` 将打包生成的 `dist` 静态文件放置服务器中，若使用Nginx等涉及跨域请配置路由代理

### 作者其他项目推荐
- [X-Boot前后端分离开发平台](https://github.com/Exrick/x-boot)

    ![](https://i.loli.net/2018/07/21/5b52e274d2085.png)

