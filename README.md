# 《黑之缘工作室网站使用手册 🧐》

欢迎光临！！🤓 
<br><br>
📫 工作室邮箱 ：blackdestinystudio@gmail.com <br>
🔐 邮箱的密码 ：*那本漫画的英文名全小号* @ *谢尔生日月份 + 日期*  （中间的@包括）
<br><br>
通过这本废话连篇手册，您将可以

- [了解网站构造](#intro)
- [编辑网站](#edit)
- [添加作品](#works)

<a id="intro"></a>
### 简单介绍 👷‍♂️

这个网站如看上去一样简单，只有 index.html 一页，主旨是轻便好照顾与更新  ~~加上制作人懒惰又技术不够~~。虽然现在不像以前那么热切地讨论、发布作品了，但希望以后还是有这样的一天~ 
在这个主页里边有用
![image](https://github.com/blackdestinystudio/website/assets/134148493/0d2d3090-1056-4c4e-9844-551a50e6ca39) \
这种线条来区分页面的不同模块，大致上为

1. 菜单
2. 关于我们
3. 成员介绍
4. 作品介绍
5. 版权尾页

如果想要做什么变动只要直接去相关模块看就好了! (☞ﾟヮﾟ)☞

<a id="edit"></a>
### 如何编辑 🔨

- 点开code，可以看到这个网站的所有文件，如这个 README.me，index.html, style.css 等
- 点开 index.html，可以看代码
- ![image](https://github.com/blackdestinystudio/website/assets/134148493/23002e19-5434-4330-bcc7-3cc70df98516)
- 看右边有一个铅笔符号，就是编辑啦
- 改东该西，完成后，点右上角一个绿色的 Commit Changes...
- ![image](https://github.com/blackdestinystudio/website/assets/134148493/6273c8bb-e5cb-4c3b-be08-4ac0dbe94b13)
- 然后会有这样的窗口
- ![image](https://github.com/blackdestinystudio/website/assets/134148493/c96ad78d-e50f-4112-8338-72329e2745d7)
- 再点绿色按钮就OK了

<a id="works"></a>
### 添加作品 📕

- 只需要在 index.html 里 《作品介绍》那边找到下面的提示 
- 每个作品都是被一个 ```<div class="col">``` 包住的东西
- 拷贝贴在最后一个 col 的下面，把里边的内容替换就好啦 （记得符号要小心，不然会变成乱码 <(￣ c￣)y▂ξ）
- 游戏封面的话，在文件夹找 assets -> works 里丢图片，复制好照片名，然后在 img tag 里改地址就好啦

```
            <!---------- 添加作品复制这里开始 ---------->

            <div class="col">
                <div class="card text-white bg-dark">
                    <img src="./assets/works/照片名字改这里.png格式" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title mb-3">作品名字 (括号年份)</h5>
                        <h6 class="card-subtitle mb-2 text-muted">
                            <ul>
                                <li>👷‍♂️ 参与的成员</li>
                                <li>🏷 游戏？小说？漫画？</li>
                                <li>🔗 <a href="链接放这里">下載遊戲</a></li>
                            </ul>
                        </h6>
                        <p class="card-text">
                            游戏介绍放这里
                        </p>
                    </div>
                </div>
            </div>
            <!---------- 添加作品复制这里结束 ---------->
```
<br><br>
### 尾声 🐴

以上，就是这本手册的内容~
虽然不知道谁会看（汗），但还是感谢你的阅读 👋( ´_ゝ` )
