<!DOCTYPE HTML >

<html>

  <head>

    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">

    <title>應用addcslashes()函數和stripslashes()函數分別對字串的轉義和還原</title>

  </head>

  <body>

    <?php

      $str = "select * from tb_book where bookname = 'PHP5從入門到放棄'";

      echo $str."<br>";

      $a = addslashes($str);  //對字串中的特殊字元進行轉義

      echo $a."<br>"; //輸出轉義後的字元

      $b = stripslashes($a); //對轉義後的字元進行還原

      echo $b."<br>"; //將字元原義輸出

    ?>

  </body>

</html>

說明上述程式stripslashes()與addslashes()

### addslashes()
```
該函數可用於為存儲在數據庫中的字符串以及數據庫查詢語句準備合適的字符串。

https://www.w3school.com.cn/php/func_string_addslashes.asp
https://sites.google.com/site/phplearnmark/php/php-zhi-ling-qing-dan/zi-chuan-han-shi/php-addslashes

特殊字符是：
單引號(')
雙引號(")
反斜杠(\)
NULL
```

### stripslashes()
```
https://sites.google.com/site/phplearnmark/php/php-zhi-ling-qing-dan/zi-chuan-han-shi/php-stripslashes

stripslashes()函數刪除由addslashes()函數添加的反斜杠。
該函數可用於清理從數據庫中或者從HTML表單中取回的數據。

String stripslashes( $string )
將要轉換的字串 $string 放入 stripslashes 函式的小括號內進行轉換，並返回轉換結果，如果字串 $string 內不含任何反斜線，則反回結果與原本的字串 $string 相同，也就是說 stripslashes 函式並不會改變原始字串的內容。
```


### stripslashes ( string $string ) : string
```
https://www.php.net/manual/en/function.stripslashes.php

定義和用法
stripslashes()函數刪除由addslashes()函數添加的反斜杠。
```
