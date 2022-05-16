<h1 align="center">
 SQL Beautify
</h1>

<p align="center">
  😀格式化你杂乱无章的sql/hql代码😀
  
</p>
<p align="center">
  VS Code extension that beautifies SQL(HQL).
  
</p>

<div align=center>
<img  src="https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo.gif?raw=true"/>
</div>


# 📸 安装 Installation 
[VSCode Plugin Market](https://marketplace.visualstudio.com/items?itemName=clarkyu.vscode-sql-beautify)


# 💥 特点 Features 

## 1. Beautify SQL

一键美化你的SQL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+f`即可使用！ 

Beautify your SQL!  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+f` just like you normally would.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo.gif?raw=true)

## 2. Beautify SQL DDL (Only for hive-sql)

一键美化你的DDL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+l`即可使用！ 

Beautify your SQL DDL!  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+l`.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo2.gif?raw=true)

## 3. Extract SQL DDL (Only for hive-sql)

一键从你的Insert语句中提取的DDL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+;`即可使用！ 

Extract ddl from insert sql !  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+;`.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo3.gif?raw=true)

## 4. Customize your own style 🐱‍🏍
你可以在vscode中文件-首选项-设置-扩展中找到一些自定义内容。详细的说明，可以阅读wiki-[功能说明](https://github.com/clarkyu2016/sql-beautify/wiki/%E5%8A%9F%E8%83%BD%E8%AF%B4%E6%98%8E-Features)！

Customize your own sql-beautify style in [settings-extension]. For more detail, please read wiki [Features](https://github.com/clarkyu2016/sql-beautify/wiki/%E5%8A%9F%E8%83%BD%E8%AF%B4%E6%98%8E-Features) to get more details about features of this extension

![customize](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/customize.png?raw=true)



# 💡 注意 Attention

* 这个插件在hql语句上更加兼容，因为它是我的主要工作语言。如果你在其他类型sql上使用，请小心使用，尤其是你的代码比较复杂的时候。This extension is more compatible in `Hive SQL` than in other sql language. If you develop on other sql language, it may cause some problems when the code is complex.

* 请小心使用本插件，建议对代码一段段进行格式化，而不是对整个文件一次性进行格式化。
Please be careful when use this plugin. Do not use it for the whole file. Recommend using it on code blocks one by one.

* 如果你真的遇到什么问题了，请先`Ctrl+z`恢复你的代码，然后可以联系我修复可能存在的问题。If you have some problems, try to use `Ctrl+z` to recover your code and contact me to fix the bug if you wish.


# 😎 更迭日志 Release Notes 
### 0.3.6 (2022/05/17)
* 修复了一些错误，感谢@BryceQin, @timegambler和@thx-god
* Fixed some bugs,Thanks for @BryceQin, @timegambler and @thx-god

## 0.3.5 (2022/02/23)
* 感谢[@fourgold](https://github.com/fourgold)新增了两个功能,在小写模式开启下：where后面and和on的对齐，以及注释的对齐
* Thanks for [@fourgold](https://github.com/fourgold) to add new functions and let SQL Beuatify can order the comment and insert indents before 'and' and 'on'
* 再次修复了小写关键词设置下对某些字段名的错误小写
* Fixed some bugs when using lowercase keywords.


# 🎅 联系我 Contact Me

如果有任何问题，欢迎在Issues上留言提问题给我。也可以通过我的微信和我联系

If you have any problem,welcome to submit issues or You can contact me via wechat.

![wechat](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/wechat1.jpg?)

