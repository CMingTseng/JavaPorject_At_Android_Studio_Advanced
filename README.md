# Advanced --- Pure JAVA @ Android
> 這個方式可以在專案中切換編譯Android App 或是 純Java 

# 開一個新專案!
![N|Solid](http://i.imgur.com/V6yeJM2.jpg)

# 確認開好了
![N|Solid](http://i.imgur.com/9u5aT9J.jpg)

# 右鍵 新增一個 Module
![N|Solid](http://i.imgur.com/XM2mhEi.jpg)

# 選擇Java Library
![N|Solid](http://i.imgur.com/bJwogRP.jpg)

# 輸入必須的資訊

```sh
Library name部分需要注意 這攸關後面編譯出來的jar檔名稱
```
![N|Solid](http://i.imgur.com/fTpgsp7.jpg)

# 看一下setting.gradle確認新增了
![N|Solid](http://i.imgur.com/BZtVp7r.jpg)

# 把範例FirstJava的內容補上
![N|Solid](http://i.imgur.com/SGATiKf.jpg)

# 編輯Run組態設定檔1
```sh
加入Java的單獨支援
```
![N|Solid](http://i.imgur.com/OpKDk3d.jpg)

# 編輯Run組態設定檔2
```sh
新增Application
```
![N|Solid](http://i.imgur.com/ejHmMG6.jpg)

# 編輯Run組態設定檔3 : 完整packagename名稱
```sh
填入Main Class 的完整packagename名稱 (貼心的有提示)
```

# 編輯Run組態設定檔4 : Use classpath of module
```sh
記得填入 Use classpath of module (這是要指定的)
```
![N|Solid](http://i.imgur.com/MOHYSaT.jpg)

# 編輯Run組態設定檔5 : 支援輸出jar
![N|Solid](http://i.imgur.com/esnTM7m.jpg)
![N|Solid](http://i.imgur.com/msPky5g.jpg)
![N|Solid](http://i.imgur.com/48wopD3.jpg)
![N|Solid](http://i.imgur.com/WcUYEg0.jpg)
# 切到JAVA設定檔嘗試執行看看 
![N|Solid](http://i.imgur.com/BHcTxy0.jpg)
# 執行JAVA前跑的gradle情形 
![N|Solid](http://i.imgur.com/r2fzB5i.jpg)
# 執行結果 
![N|Solid](http://i.imgur.com/Ql9d0CG.jpg)
# jar檔執行結果 
![N|Solid](http://i.imgur.com/Ly6Q5pB.jpg)
