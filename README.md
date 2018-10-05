# テクノロジー（藤原） 10/4課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```
var str = "hello";
undefined
var num = 123;
undefined
var flag = true;
undefined
var total
undefined
var total = 100 + 150 + 200 +;
VM1310:1 Uncaught SyntaxError: Unexpected token ;
var total = 100 + 150 + 200 ;
undefined
var str = "hello";
undefined
var num = 123;
undefined
var flag
undefined
var flag = true;
undefined
var prefList = ["北海道", "青森", "岩手", "宮城", "秋田"];
undefined
console.log(prefList[0]);
VM1516:1 北海道
undefined
console.log(prefList[3]);
VM1558:1 宮城
undefined
var  prefHash = {"kanto": "関東地方", "chubu": "中部地方", "kinki": "近畿地方", "chugoku": "中国地方", "shikoku": "四国地方"};
undefined
console.log(prefHash["kanto"]);
VM1769:1 関東地方
undefined
console.log(prefHash["kinki"]);
VM1815:1 近畿地方
undefined
console.log(prefHash.kanto);
VM1870:1 関東地方
undefined
console.log(prefHash.kinki);
VM1920:1 近畿地方
undefined
var pre
undefined
var prefHash1 = {"kanto": "関東地方", "chubu": "中部地方"};
undefined
var prefHash2 = {kanto: "関東地方", chubu: "中部地方"};
undefined
var prefHash3 = {};
undefined
prefHash3["kanto"] = "関東地方";
"関東地方"
prefHash3["chubu"] = "中部地方";
"中部地方"
var prefHash4.kanto = "関東地方";
VM2228:1 Uncaught SyntaxError: Unexpected token .
var prefHash4 = {};
undefined
prefHash4.kanto = "関東地方";
"関東地方"
prefHash4.chubu = "中部地方";
"中部地方"
var str ="JavaScriptよりもSwift!";
undefined
console.log(str.length);
VM2474:1 19
undefined
var date = new Date();
undefined
console.log(date.toLocaleString());
VM2611:1 2018/10/5 11:24:16
undefined
var str = navigator.platform + "\n" + navigator.userAgent + "\n";
undefined
window.alart(str);
VM2718:1 Uncaught TypeError: window.alart is not a function
    at <anonymous>:1:8
(anonymous) @ VM2718:1
window.alert(str);
undefined
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
