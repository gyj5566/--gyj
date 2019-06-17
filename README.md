## 技术栈

vue2 + vuex + vue-router + webpack + ES6/7 + sass + flex + request


## 项目运行

#### 注意：由于涉及大量的 ES6/7 等新属性，node 需要 6.0 以上版本

```
git clone https://github.com/gyj5566/vue-xbk.git

cd vue-xbk/server

npm install 或 yarn(推荐)

启动mySQL

npm start       连接成功

cd ../client

npm install 或 yarn(推荐)

npm run dev

```
## 关于接口数据

此项目的所有接口数据都来源于内部server

# 说明

>  如果对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！ ^_^

>  或者您可以 "follow" 一下，我会不断开源更多的有趣的项目

>  开发环境 macOS 10.12.3  Chrome 56  nodejs 6.10.0

>  如有哪里做的不好您有更好的建议，请直接在 Issues 中提，可以探讨探讨也是好的 👍

>  也是一周简简单单做了做，涉及太多的权限管理，后台不是很好，希望不要介意


# 效果演示

### 移动端扫描下方二维码

<img src="https://github.com/gyj5566/vue-xbk/blob/master/星巴克/新建文件夹/1560760831.png" width="250" height="250"/>



# 目标功能
- [x] 加班/休假状态列表页 -- 完成
- [x] 单个加班/休假详情页面 -- 完成
- [x] 审批流程页 -- 完成
- [x] 登录、注册 -- 完成
- [x] 提交加班/休假 -- 完成
- [x] 页面提示弹出框 -- 完成



# 总结

1、一两个月没动过vue了，就必须再简简单单回忆一下

# 部分截图


### 登录注册页

<img src="https://github.com/gyj5566/vue-xbk/blob/master/星巴克/新建文件夹/流程图/QQ图片20190610202915.jpg" width="365" height="619"/>


### 提交申请页

<img src="https://github.com/gyj5566/vue-xbk/blob/master/星巴克/新建文件夹/流程图/QQ图片20190610202856.png" width="365" height="619"/> <img src="https://github.com/gyj5566/vue-xbk/blob/master/星巴克/新建文件夹/流程图/QQ图片20190610202853.png" width="365" height="619"/>


# 项目布局

```
.
├── build                                       // webpack配置文件
├── config                                      // 项目打包路径
├── src                                         // 源码目录
    ├── api                                     // 接口管理
    │   └── index.js
│   ├── components                              // 组件
│   │   ├── alertmessage.vue                    // 提示框组件
│   │   ├── dialog.vue                          // 列表页点击新建底部弹出组件
│   │   ├── footer.vue                          //底部按钮组件
│   │   ├── header.vue                          // 头部公共组件片
│   │   ├── item.vue                            // 列表每一项组件
│   │   ├── nav.vue                             // 列表页切换状态组件
│   │   ├── piece.vue                           // 白色框显示组件
│   │   ├── typeBox.vue                         // 列表页切换加班/休假组件
│   │   └── user.vue                            // 绿色部分公用组件
│   ├── plugins                                 // 引用的插件
│   ├── router
│   │   └── router.js                           // 路由配置
│   ├── store                                   // vuex的状态管理
│   │   ├── modules                             // store模块
│   │   │   └── list.js                         // 列表页数据
│   │   └── index.js                            // 引用vuex，创建store
│   ├── utils
│   │   ├── request.js                          // 封装axios文件
│   │   └── upload.js                           // 上传文件函数
│   ├── views
│   │   ├── application.vue                     // 申请页
│   │   ├── batch.vue                           // 批量页
│   │   ├── detail.vue                          // 详情
│   │   ├── history.vue                         // 审批历史
│   │   ├── index.vue                           // 列表
│   │   ├── login.vue                           // 登陆注册
│   │   ├── search.vue                          // 搜索
│   │   └── sort.js                             // 排序
│   ├── App.vue                                 // 页面入口文件
│   ├── main.js                                 // 程序入口文件，加载各种公共组件
.

56 directories, 203 files
```

# License

[GPL](https://github.com/bailicangdu/vue2-elm/blob/master/COPYING)
