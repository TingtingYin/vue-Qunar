# travel

> travel project

### 多页应用
1. 页面跳转返回html
2. 优点 ： 首屏时间快（只经过了一次http请求），SEO（搜索引擎可以识别html中的内容）效果好
3. 缺点： 页面切换慢
### 单页应用
1. vue应用是单页面应用
2. 页面跳转靠js渲染
3. 优点：页面切换块
4. 缺点：首屏时间慢，SEO差
### vue中页面跳转
> 用<router-link></router-link>
### template标签注意事项
> template标签只能向外暴露一个根标签
### meta标签
> 移动端用户通过手指放大缩小网页是无效的
### reset.css
> 所有浏览器显示的效果基本一致
### border.css
> 1像素边框显示，不同设备显示物理一像素边框
### 移动端click事件延迟300ms的解决
1.  npm install fastclick --save
### iconfont
> TODO
###----------项目初始化完毕---------------

1. npm install stylus --save
2. npm install stylus-loader --save
### rem
> 1rem等于html根元素设定的font-size的px值,这里是reset.css中设置的50px.如果css里面没有设定html的font-size，则默认浏览器以1rem=16px来换算。
### header初步（icon没有做）
### iconfont的使用
> iconfont官网创建项目，图标加入购物车
### 代码优化1-抽离共用样式
1. @import '../../../assets/styles/variables.styl'
2. @import '~@/assets/styles/variables.styl'
3. 给目录style起别名：@import '~styles/variables.styl'

改完之后记得重启！！！！
### 分支开发
1. github上创建分支index-swiper
2. 本地git pull
3. git checkout index-swiper
### 轮播图
> vue-awesome-swiper
1. npm install vue-awesome-swiper@2.6.7 --save
新版本不好用
2. Swiper.vue
3. 去掉左右箭头和灰线
4. 轮播图显示图片
5. 轮播图下方组件抖动---------
network-fast3G测试，发现test文字先出现，轮播图显示时，test才在轮播图下方
  > 原因： 轮播图没有设置高度，请求到之后才会把容器撑开
6. 显示页码小圆点-蓝色
7. 显示页码小圆点-白色
8. 轮播图v-for
9. 轮播图循环展示
### 提交分支
1. git checkout master
2. git merge origin/index-swiper

### Icons.vue
1. 8个图标正常显示



