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
<img  src="https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo.gif"/>
</div>


# 📸 安装 Installation 
[VSCode Plugin Market](https://marketplace.visualstudio.com/items?itemName=clarkyu.vscode-sql-beautify)


# 💥 特点 Features 

## 1. Beautify SQL

一键美化你的SQL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+f`即可使用！ 

Beautify your SQL!  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+f` just like you normally would.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo.gif)

## 2. Beautify SQL DDL (Only for hive-sql)

一键美化你的DDL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+l`即可使用！ 

Beautify your SQL DDL!  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+l`.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo2.gif)

## 3. Extract SQL DDL (Only for hive-sql)

一键从你的Insert语句中提取的DDL！请确保你使用的语言是`SQL`，选择需要优化的代码块，按下`Alt+Shift+;`即可使用！ 

Extract ddl from insert sql !  Make sure the language is set to `SQL`,then select your sql code and press `Alt+Shift+;`.

![demo](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/demo3.gif)

## 4. Customize your own style 🐱‍🏍
你可以在vscode中文件-首选项-设置-扩展中找到一些自定义内容。详细的说明，可以阅读wiki-[功能说明](https://github.com/clarkyu2016/sql-beautify/wiki/%E5%8A%9F%E8%83%BD%E8%AF%B4%E6%98%8E-Features)！

Customize your own sql-beautify style in [settings-extension]. For more detail, please read wiki [Features](https://github.com/clarkyu2016/sql-beautify/wiki/%E5%8A%9F%E8%83%BD%E8%AF%B4%E6%98%8E-Features) to get more details about features of this extension

![customize](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/customize.png)



# 💡 注意 Attention

* 这个插件在hql语句上更加兼容，因为它是我的主要工作语言。如果你在其他类型sql上使用，请小心使用，尤其是你的代码比较复杂的时候。This extension is more compatible in `Hive SQL` than in other sql language. If you develop on other sql language, it may cause some problems when the code is complex.

* 请小心使用本插件，建议对代码一段段进行格式化，而不是对整个文件一次性进行格式化。
Please be careful when use this plugin. Do not use it for the whole file. Recommend using it on code blocks one by one.

* 如果你真的遇到什么问题了，请先`Ctrl+z`恢复你的代码，然后可以联系我修复可能存在的问题。If you have some problems, try to use `Ctrl+z` to recover your code and contact me to fix the bug if you wish.


# 😎 更迭日志 Release Notes  
### 0.3.13 (2022/06/15)
* 修正了注释下面接with语句的格式化问题@BryceQin
* FIx [the bug of COMMENT and With](https://github.com/clarkyu2016/sql-beautify/issues/40) @BryceQin
* 修正了DDL中表名带有特定关键字时会出现错误@YouboFAN
* FIx [the bug of DDL with keywords](https://github.com/clarkyu2016/sql-beautify/issues/39) @YouboFAN
* 修正了:= 会被添加空格导致失效@lpzzz
* FIx [the bug of :=](https://github.com/clarkyu2016/sql-beautify/issues/38) @lpzzz

### 0.3.9 (2022/05/27)
* 调整了引号内的格式化逻辑，修正以前的错误问题(看起来很难遇到的[“大优化”](https://github.com/clarkyu2016/sql-beautify/wiki/%E5%BC%80%E5%8F%91%E6%97%A5%E5%BF%97%EF%BC%88%E4%B8%AD%E6%96%87%EF%BC%89#%E6%96%B0%E5%A2%9E%E4%BA%86%E5%AF%B9%E5%BC%95%E5%8F%B7%E5%86%85%E5%AD%97%E7%AC%A6%E4%B8%8D%E6%93%8D%E4%BD%9C%E7%9A%84%E9%80%BB%E8%BE%91-20220527))
* Adjusted logic for formatting "string" inside quotes


 [**More Release Notes**](https://github.com/clarkyu2016/sql-beautify/blob/main/CHANGELOG.md)

# 🎅 联系我 Contact Me

如果有任何问题，欢迎在Issues上留言提问题给我。也可以通过我的微信和我联系

If you have any problem,welcome to submit issues or You can contact me via wechat.

![wechat](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/wechat1.jpg)

