### $GLOBALS
```
https://www.php.net/manual/zh/reserved.variables.globals.php

$GLOBALS — 引用全局作用域中可用的全部變量

說明：一個包含了全部變量的全局組合數組。變量的名字就是數組的鍵。
```


### $_POST
```
https://www.php.net/manual/zh/reserved.variables.post.php

$_POST -- $HTTP_POST_VARS [已棄用] — HTTP POST變量

說明：$HTTP_POST_VARS包含相同的信息，但它不是一個超全局變量。(注意$HTTP_POST_VARS和$_POST是不同的變量，PHP處理它們的方式不同)
```

### $_GET
```
https://www.php.net/manual/zh/reserved.variables.get.php

$_GET -- $HTTP_GET_VARS [已棄用] — HTTP GET變量

說明：$HTTP_GET_VARS包含相同的信息，但它不是一個超全局變量。(注意$HTTP_GET_VARS和$_GET是不同的變量，PHP處理它們的方式不同)
```

### $_Server
```
https://www.php.net/manual/zh/reserved.variables.server.php

$_SERVER -- Server and execution environment information —服務器和執行環境信息

說明：$_SERVER是一個包含了諸如頭信息(header)、路徑(path)、以及腳本位置(script locations)等等信息的數組。
```

### $_Cookie
```

```

### $_Session
```
https://www.php.net/manual/zh/reserved.variables.files.php

說明：當前腳本可用SESSION變量的數組。更多關於如何使用的信息，參見Session函數文檔。

常用的 Session 函式庫
session_start：啟用一個新的或開啟正在使用中的session。
session_destroy：清除正在使用中的 session。
session_name：取得正在使用中的名稱或將名稱更新為新的名稱。
session_module_name：取得或更新正在使用中的模組。
session_save_path：存取目前使用中的 session 路徑。
session_id：存取目前使用中的 id。
session_register：註冊一組新的 session。
session_unregister：刪除一個正在使用中的 session。
session_is_registered：檢查目前使用中是否已經有此變數。
session_decode：資料解碼，解碼成功回傳 true。
session_encode：資料編碼，編碼成功回傳 true。

https://www.webtech.tw/info.php?tid=33
```
```

# PHP Session 使用範例說明
```
PHP Session 使用範例說明
https://www.wibibi.com/info.php?tid=135
```



### $_FILES
```
https://www.php.net/manual/zh/reserved.variables.files.php

$_FILES -- $HTTP_POST_FILES [已棄用] — HTTP文件上傳變量
```


### $_REQUEST
```

```


### $_ENV
```

```


### $http_response_header
```

```


### $argc
```

```

### $argv
```

```
