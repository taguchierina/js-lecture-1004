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
var numA = 2;
undefined
var numB = 3;
undefined
var numC = numA + numB;
undefined
console.log(numC);
VM2839:1 5
undefined
var numD = numA * numB;
undefined
console.log(numD);
VM2906:1 6
undefined
var numA = 1;
undefined
var numB = 2;
undefined
var boolC = numA == numB;
undefined
console.log(boolC);
VM3013:1 false
undefined
var boolD = numA < numB;
undefined
console.log(boolC);
VM3083:1 false
undefined
var boolD = numA < numB;
undefined
console.log(boolD);
VM3151:1 true
undefined
var numA = 1;
undefined
var numB = "1";
undefined
console.log(numA == numB);
VM3258:1 true
undefined
console;log(numA === numB);
VM3318:1 Uncaught ReferenceError: log is not defined
    at <anonymous>:1:9
(anonymous) @ VM3318:1
console.log(numA === numB);
VM3339:1 false
undefined
var strA = "我輩は";
undefined
var strB = "犬である";
undefined
var strC = strA + strB;
undefined
console.log(strC);
VM3460:1 我輩は犬である
undefined
console.log(strA === strB);
VM3533:1 false
undefined
var numA = 1;
undefined
if(numA === 1 ) { console.log("numAは１です");
                }
VM4507:1 numAは１です
undefined
if (numA === 2 ){
    console.log("numAは２です");
}
undefined
var numA = 3;
undefined
if (numA === 1){
    console.log("numAは１です");
}
undefined
else if (numA === 2 ){
VM4787:1 Uncaught SyntaxError: Unexpected token else
console.log("numAは２です);
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
