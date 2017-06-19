夏天到了，所以主题名字就叫Summer吧。主题参考自[https://cn.vuejs.org/v2/api/](https://cn.vuejs.org/v2/api/)。emoji作者[ColinXu](http://www.iconfont.cn/user/detail?uid=496384)。

由于每个人单页的迥异，所以我把自定义的单页去掉了。单页样式自定义可以参考下面的思路：
```golang
{{if eq $.single.Title "Friends"}} 
    {{template "friends.html" $}}
{{end}}
{{if eq $.single.Title "Music"}} 
    {{template "music.html" $}}
{{end}} 
```
关于警告框，在笔记编辑器里选中文字加下划线就可以了。

主题已上架[主题市场](https://leanote.com/member/blog/theme)，有什么问题欢迎留言。