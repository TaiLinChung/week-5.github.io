# week05 MySQL

## 要求三:
> 1.使⽤ INSERT 指令新增⼀筆資料到 member 資料表中，這筆資料的 username 和 password 欄位必須是 test。接著繼續新增⾄少 4 筆隨意的資料。

> ![](https://i.imgur.com/MG5RUWC.jpg)
> ![](https://i.imgur.com/NK4flzt.jpg)

> 2.使⽤ SELECT 指令取得所有在 member 資料表中的會員資料。

> ![](https://i.imgur.com/QlHimsZ.jpg)

> 3.使⽤ SELECT 指令取得所有在 member 資料表中的會員資料，並按照 time 欄位，由 近到遠排序。

> ![](https://i.imgur.com/ddIwuwV.jpg)

> 4.使⽤ SELECT 指令取得 member 資料表中第 2 ~ 4 共三筆資料，並按照 time 欄位， 由近到遠排序。( 並非編號 2、3、4 的資料，⽽是排序後的第 2 ~ 4 筆資料 )

> ![](https://i.imgur.com/ZxtpSXy.jpg)

> 5.使⽤ SELECT 指令取得欄位 username 是 test 的會員資料。

> ![](https://i.imgur.com/AcoXmoj.jpg)

> 6.使⽤ SELECT 指令取得欄位 username 是 test、且欄位 password 也是 test 的資料。

> ![](https://i.imgur.com/9vLSPAj.jpg)

> 7.使⽤ UPDATE 指令更新欄位 username 是 test 的會員資料，將資料中的 name 欄位改成 test2。

> ![](https://i.imgur.com/NUo8c2v.jpg)


## 要求四:
> 4-1.取得 member 資料表中，總共有幾筆資料 ( 幾位會員 )。

> ![](https://i.imgur.com/wlcWF8H.jpg)

> 4-2.取得 member 資料表中，所有會員 follower_count 欄位的總和。

> ![](https://i.imgur.com/KEYtT7k.jpg)

> 4-3.取得 member 資料表中，所有會員 follower_count 欄位的平均數。

> ![](https://i.imgur.com/TC7jnMB.jpg)


## 要求五:
> 5-1.在資料庫中，建立新資料表紀錄留⾔資訊，取名字為 message。必須包含欄位設定：

>> CREATE TABLE

>> ![](https://i.imgur.com/viazkDz.jpg)

>> BULID FORIENGE KEY

>> ![](https://i.imgur.com/ffaxE5X.jpg)

>> SHOW DATAS UNDER RELATIONAL

>> ![](https://i.imgur.com/F20xTZE.jpg)

> 5-2.使⽤ SELECT 搭配 JOIN 語法，取得 member 資料表中欄位 username 是 test 的所有留⾔，資料中須包含留⾔者會員的姓名。

> ![](https://i.imgur.com/fEUY15n.jpg)

> 5-3.使⽤ SELECT、SQL Aggregate Functions 搭配 JOIN 語法，取得 member 資料表中欄位 username 是 test 的所有留⾔平均按讚數。

> ![](https://i.imgur.com/yhxvlOK.jpg)
