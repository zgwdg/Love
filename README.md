程序员式浪漫~ <a href="https://tanyaodan.com/love" target="_blank">点击查看演示页面</a>这是我进行二次开发后的记录恋爱时长和恋爱故事的网页，我真的好爱好爱憨憨啊~<br>
在网站根目录新建love文件夹后把项目解压缩放入，通过 域名/love/ 就可以进行访问。<br><br>
给页面文字添加span标签，设置id="text-xx"唯一属性，使用contenteditable="true"，开启该元素的编辑模式，用jQuery属性.click()判断点击，用.text()返回此元素的文本内容，并用正则进行判断内容是否合法，然后通过AJAX POST给php处理，php对传入的参数进行过滤，然后读取模版文件，替换模版文件对应内容，保存为新文件并记录操作，最后返回数据给前端，前端处理数据并更新页面。需要给/love/forever/others和/love/forever/loveNote.txt设置777权限嗷~<br>
进入后的首页如下：<br>
![恋爱树首页](/img/love.jpg)<br>
查看我们的故事缩放页面如下：<br>
![我们的故事缩放页面](/img/heart.jpg)<br>
我们的故事页面如下：<br>
![我们的故事中的页面](/img/story.jpg)<br>
你看看你憨憨<br>
![你看看你憨批](/img/憨批.jpg)<br>
你看看我靓仔<br>
![你看看我靓仔](/img/靓仔.jpg)<br>
你憨憨我靓仔<br>
![你憨憨我靓仔](/img/靓仔和憨憨.jpg)<br>
