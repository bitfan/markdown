# markdown
测试markdown的项目

## 页面内锚链接
其实最终以GitHub为准，如果实在不知道，可以先写一个标题，提交到GitHub，然后用右键拷贝链接看那个标题的锚链接是什么。
> Here's a tip -- if you're having trouble with your anchor not working due to misspellings or odd characters, simply hover over your heading on Github, then hover or click the link icon that appears to the left. You can then right click to copy the link location, left click it to go to the URL and view it in your address bar, or simply stay hovered over it and view it in the status bar of your browser.

可以测试以下几种锚链接：
### English Anchor
这个标题是英文的

### English和中文混合
这个标题是中英文混合但是英文在前面

### 中文English混合的
这个标题是中英文混合但是第一个字符是中文

### 中文标题
这个标题只有中文

### Ready, set, GO!
这个标题中带有标点符号


下面是链接：
[English Anchor](#english-anchor)：空格用`-`代替；所有字母小写
```md
[English Anchor](#english-anchor)
```

[English和中文混合](#english和中文混合)：注意第一个字母小写
```md
[English和中文混合](#english和中文混合)
```

[中文English混合的](#中文english混合的)：注意英文要转成全小写
```md
[中文English混合的](#中文english混合的)
```

[Ready, set, GO!](#ready-set-go)：标点符号全部省略
```md
[Ready, set, GO!](#ready-set-go)
```

