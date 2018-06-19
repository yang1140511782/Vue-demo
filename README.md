# [vue-redbk](https://wenqiii.github.io/vue-redbk/dist/index.html#/main3)
### Demo

## 项目描述
### 技术栈
Vue2.0全家桶 + axios + Vuex + Mint-Ui + Mock.js + Stylus
### 主要依赖
* 使用vue-cli2.0搭建项目框架
* 使用vue-router2.7进行页面路由切换
* 使用json server进行http请求获取数据
* mock假数据存储在本地
* 使用stylus编写样式
* vuex进行状态管理
* better-scroll优化滚动效果
* vue-awesome-swiper轮播图
* flexible.js 10rem解决移动端设备兼容
### 主要实现的功能
#### 首页
> 1、tabbar滑动切换和点击切换<br>
> 2、搜索框<br>
> 3、笔记列表的自适应布局<br>
> 4、良好的滚动手感<br>
> 5、侧边栏的进入退出<br>
#### 笔记页
> 1、滑动查看笔记图片<br>
> 2、笔记详情展示<br>
#### 商品页
> 1、滑动查看商品图片<br>
> 2、商品详情展示<br>
> 3、加入购物车的上拉弹出框，选择商品颜色、尺寸、重量及数量<br>
#### 购物车
> 1、已加入购物车的商品展示<br>
> 2、增加、减少商品数量，删除商品<br>
> 3、结算功能<br>
### 待实现功能
> 1、搜索功能<br>
> 2、评论页面的展示<br>
> 3、笔记页面的完善<br>
## 项目总结（所踩过的坑！！）
>     历时半个多月的敲代码过程，终于完成了这款仿小红书的项目(有点小开森~)。项目使用到vue-router进行路由切换，组件化开发让我更加具有组件化思维，vuex的状态管理模式，采用集中式存储管理应用的所有组件的状态，并以相应的规则保证状态以一种可预测的方式发生变化。项目所用到的假数据为小红书官网上的一些数据，以及小红书app上的截图(小红书没有PC端商品图片，只好默默抠图...)。作为一名vue的初学者，开发过程中难免踩过一些坑，一开始并没有用到mint-ui这个移动端布局框架，打算自己手写一个侧边栏，尝试许久，效果总不如人意，然后果断放弃,投入mintui的怀抱，嗯，效果蛮不错的。还有不想在路由中看到#,路由文件中我选择了history模式，结果打包上线时...你懂的，总之开发过程就是填坑过程，期间遇到的一些问题通过查看官网文档，浏览社区大牛的技术分享，最后总能解决的。


For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
