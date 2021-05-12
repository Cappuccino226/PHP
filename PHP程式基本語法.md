### PHP 基本語法
```
01: <html>
02: <head>
03: <title>php 特殊定義符號</title>
04: </head>
05: <body>
06: <?
07: echo "方法一";
08: ?>
09: <?php
10: echo "方法二";
11: ?>
12: <SCRIPT LANGUAGE="php">
13: echo "方法三";
14: </SCRIPT>
15: <%
16: echo "方法四";
17: %>
18: </body>
19: </html> 
```
### 執行結果>>
```
第 06~08 行，方法一：<? 程式碼 ?> 最簡單表達方式；SGML 的處理指令。 
第 09~11 行，方法二：<?php 程式碼 ?> 最正統表達方式；XML 的處理指令。
第 12~14 行，方法三：<SCRIPT LANGUAGE="php"> 程式碼 </SCRIPT>，為 HTML 的 script 表達格式。
第 15~17 行，方法四：<% 程式碼 %> ，與 ASP 語法相同表達格式，但容易與 asp 混洧，且須在 php.ini 的設定檔中，設定 asp_tags 為 On 才
可使用。 
```
