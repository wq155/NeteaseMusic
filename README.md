# neteasemusic

> guguji's music demo

这个demo旨在练习vue.js,尝试用vue2.0重构网易云音乐pc版。后台接口是从网上找的开源的[网易云音乐的api](https://binaryify.github.io/NeteaseCloudMusicApi)。
下载到本地并执行`node app`然后监听localhost:3000端口即可访问。

*后台api是本地获取数据必备*

## 安装

``` bash
#down repository
git clone https://github.com/guguji5/NeteaseMusic.git

#switch file catalog
cd NeteaseMusic/neteaseMusic/

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev
```
## 实现功能

 1. H5 audio实现音乐播放                 ★★
 2. 拖拽，点击改变歌曲进度                 ★
 3. 歌词同步展示                         ★★
 4. 歌曲清单功能及上一曲，下一曲功能        ★
 5. vuex组件，单一状态管理                ★★
 6. vue-router路由管理                   ★
