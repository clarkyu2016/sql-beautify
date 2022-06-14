
## 😎 更迭日志 Release Notes 
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

### 0.3.6 (2022/05/17)
* 修复了一些错误，感谢@BryceQin, @timegambler和@thx-god
* Fixed some bugs,Thanks for @BryceQin, @timegambler and @thx-god

### 0.3.5 (2022/02/23)
* 感谢[@fourgold](https://github.com/fourgold)新增了两个功能,在小写模式开启下：where后面and和on的对齐，以及注释的对齐
* Thanks for [@fourgold](https://github.com/fourgold) to add new functions and let SQL Beuatify can order the comment and insert indents before 'and' and 'on'
* 再次修复了小写关键词设置下对某些字段名的错误小写
* Fixed some bugs when using lowercase keywords.

### 0.3.0 (2023/01/29)
* 修复了小写关键词设置下对某些字段名的错误小写
* Fixed some bugs when using lowercase keywords.@ljfre
* 感谢@italodamato 修复了"Extension 'SQL Beautify' is configured as formatter but it cannot format 'SQL'-files" 的问题
* Thanks for @italodamato to fixed the bug "Extension 'SQL Beautify' is configured as formatter but it cannot format 'SQL'-files" 
* 祝大家2022年新年快乐！

### 0.2.8 (2021/11/01)
* 修复了一些带有注释的问题，包括注释后面重新逗号和括号以及复原的问题
* Fixed some bugs with "Comments".
* 修复了一个ddl美化的bug
* Fixed [a ddl bug](https://github.com/clarkyu2016/sql-beautify/issues/16) @xubuild
* 修复了一些其他的bug
* Fixed some bugs @rongsheng @zhangzhe @wuhuanzi

### 0.2.4 (2021/07/14)
* 删除了每行末尾不必要的空格
* delete [the whitespace character at the end of line](https://github.com/clarkyu2016/sql-beautify/issues/4) @Geek-Roc
* 修复了一些带有注释的问题
* Fixed some bugs with "Comments".

### 0.1.39 (2021/07/14)
* 支持了"With...as..."的格式化
* Support sql with "With...as..."
* fix some bugs @sakura

### 0.1.36 (2021/06/24)
* 修复了一些带有注释的问题
* Fixed some bugs with "Comments".
* 如果你的代码中有很多非常规的注释，请小心使用本插件，可能会有些未知的错误
* If you have many irregular comments in your code, please be careful when use sql-beautify, which may cause some unknown bugs.


### 0.1.32
* Fixed some bugs with "Comments".

### 0.1.32
* Add "Use whitespace to replace Tab in the indentation of subquery" setting.

![tablevswhitespace](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/tablevswhitespace.png?raw=true)

* 端午节快乐！

### 0.1.30
* Add comma location setting.

![comma](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/comma.png?raw=true)

### 0.1.28

* fix [the bug of COMMENT](https://github.com/clarkyu2016/sql-beautify/issues/4) @LiHaoyu1994 

### 0.1.28

* fix [the bug of COMMENT](https://github.com/clarkyu2016/sql-beautify/issues/3) @aleegreat 

### 0.1.24

* add hive-sql format support

### 0.1.22

* fix some bugs

### 0.1.21

* Add Uppercase setting. You can choose convert key words to uppercase or lowercase.(Default is Uppercase)

### 0.1.15

* Add ddl extract.

### 0.1.13

* Fix some bugs of ddl beautify.

### 0.1.8

* Fix `order by` auto-wrap when `order by` in special hql syntax like `row number() over(partition by order by)`

### 0.1.7

* Align words after `as` left

![as](https://clarkyu1993.coding.net/p/tuku/d/pic/git/raw/master/as.gif?raw=true)

### 0.0.12
* Fix some bugs of auto-wrap

### 0.0.9
* Support `CASE WHEN` auto-wrap

### 0.0.7
* Add beautify ddl

### 0.0.4

* Fix some bugs

### 0.0.1

* Initial release
















