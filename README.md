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


## 📸 安装 Installation 
[VSCode Plugin Market](https://marketplace.visualstudio.com/items?itemName=clarkyu.vscode-sql-beautify)


## 💡 注意 Attention

* 这个插件在hql语句上更加兼容，因为它是我的主要工作语言。如果你在其他类型sql上使用，请小心使用，尤其是你的代码比较复杂的时候。This extension is more compatible in `Hive SQL` than in other sql language. If you develop on other sql language, it may cause some problems when the code is complex.

* 请小心使用本插件，建议对代码一段段进行格式化，而不是对整个文件一次性进行格式化。
Please be careful when use this plugin. Do not use it for the whole file. Recommend using it on code blocks one by one.

* 如果你真的遇到什么问题了，请先`Ctrl+z`恢复你的代码，然后可以联系我修复可能存在的问题。If you have some problems, try to use `Ctrl+z` to recover your code and contact me to fix the bug if you wish.


## 💥 特点 Features 

### Beautify SQL

一键美化你的SQL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+f`即可使用！ 

Beautify your SQL!  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+f` just like you normally would.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo.gif?raw=true)

### Beautify SQL DDL (Only for hive-sql)

一键美化你的DDL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+l`即可使用！ 

Beautify your SQL DDL!  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+l`.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo2.gif?raw=true)

### Extract SQL DDL (Only for hive-sql)

一键从你的Insert语句中提取的DDL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+;`即可使用！ 

Extract ddl from insert sql !  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+;`.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo3.gif?raw=true)


## ✨ 最新更新 What's new on 0.1.30?

你可以自由选择逗号位置后置还是前置(默认前置，更多内容可以参考[开发日志](https://github.com/clarkyu2016/sql-beautify/wiki/%E5%BC%80%E5%8F%91%E6%97%A5%E5%BF%97%EF%BC%88%E4%B8%AD%E6%96%87%EF%BC%89))

You can choose fix the comma location to the end of the line.(NO RECOMMENDED)

![comma](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/comma.png?raw=true)

## ✨ 最新更新 What's new on 0.1.21?

你可以选择把关键词转换成大写还是小写（默认是转化大写）

You can choose convert key words to uppercase or lowercase in Settings.(Default is Uppercase)

## 🎅 联系我 Contact Me

如果有任何问题，欢迎在Issues上留言提问题给我。也可以通过我的微信和我联系

If you have any problem,welcome to submit issues or You can contact me via wechat.

![wechat](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/wechat1.jpg?)