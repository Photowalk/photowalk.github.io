# Moving to Hugo


把博客从WordPress搬家到了hugo，托管到了Github上，耗时一天。近期还会研究下hugo和这个主题，添加一些CSS。

原来的博客和域名还会继续存在，但是可能不会更新了。

最近搭建了Mastodon和Matrix。发现Mastodon使用频率高很多，而Matrix使用下来体验一般般，客户端还需要加把劲，synapse使用python写的，同步人数较多的群的历史信息时会比较慢，并且加入一个大群时，很多时候会失败。

Pixelfed实例近期也会上线。

```shell
git remote -v
git remote rm origin
git remote add origin git@github.com:photowalk/photowalk.github.io.git
hugo new posts/test/index.md
hugo server -D #本地预览 localhost:1313
hugo
cd public
git add .
git commit -m 'change note'
git push -u origin master
```

{{< music server="netease" type="song" id="1896241680" >}}


今年得想办法置办个这玩意儿，从第一代出来就想买了
{{< youtube _aLVuGmwW58 >}}
