# musicWeb
用uni-app模仿的网易云移动端<br/>
主要实现了播放器内核、发现页面、音乐搜索、歌单分类、歌单详情、播放列表、音乐播放页面以及评论页面等主要功能，兼容了微信小程序，app端陆续完善，后续将会逐步完成更多功能<br/>

### 效果预览<br/>![](/static/Screenshot/home.png)   ![](/static/Screenshot/hotSearch.png) 
![](/static/Screenshot/searchResult.png)     ![](/static/Screenshot/songsList.png) 
![](/static/Screenshot/playlistDetails.png)     ![](/static/Screenshot/playList.png)
![](/static/Screenshot/musicPlayPage.png)   ![](/static/Screenshot/lyrics.png) 
![](/static/Screenshot/comment.png)

### 技术方案<br/>
使用uni-app+uView-ui+vuex<br/>后端使用的 [NeteaseCloudMusicApi](https://binaryify.github.io/NeteaseCloudMusicApi/#/?id=neteasecloudmusicapi)，感谢[Binaryify](https://github.com/Binaryify)对接口文档不断维护与更新<br/>
播放器核心采用vuex+prototype挂载一个可供全局访问的audio实例来实现<br/>
歌词滚动用的是[微&风](https://github.com/bing-idea)老哥的插件[uni-app 自定义歌词显示组件](https://github.com/bing-idea/bing-lyric-demo),非常感谢<br/>
最后也非常感谢[uView-ui](https://github.com/YanxinNet/uView)，非常好用的移动端ui库<br/>

#### 下载使用<br/>
clone下来后使用HBuilder打开，选择运行到指定终端即可

#### 本项目仅供学习交流使用



