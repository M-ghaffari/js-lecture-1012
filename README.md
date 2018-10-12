# テクノロジー（藤原） 10/12課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```
for (i=0;i<5;i++){
console.log(i)}
VM104:2 0
VM104:2 1
VM104:2 2
VM104:2 3
VM104:2 4
undefined
for (i=0;i<5;i++){
console.log(i);}
VM107:2 0
VM107:2 1
VM107:2 2
VM107:2 3
VM107:2 4
undefined
i
5
for (let 1=0;i<5;i++){
console.log(i);}
VM132:1 Uncaught SyntaxError: Unexpected number
for (let i=0;i<5;i++){
console.log(i);}
VM136:2 0
VM136:2 1
VM136:2 2
VM136:2 3
VM136:2 4
undefined
for (let r=0;i<5;i++){
console.log(i);}
undefined
for (let r=0;i<5;releaseEvents++){
console.log(i);}
undefined
for (let r=0;i<5;r++){
console.log(i);}
undefined
for (let r=0;r<5;r++){
console.log(r);}
VM205:2 0
VM205:2 1
VM205:2 2
VM205:2 3
VM205:2 4
undefined
r
VM225:1 Uncaught ReferenceError: r is not defined
    at <anonymous>:1:1
(anonymous) @ VM225:1
for (let ){

VM245:1 Uncaught SyntaxError: Unexpected token )
let a = ["お","う","い"];

undefined
let a = ["お","う","い"];for

VM358:1 Uncaught SyntaxError: Unexpected end of input
let a = ["お","う","い"];for{

VM361:1 Uncaught SyntaxError: Unexpected token {
let a = ["お","う","い"];for{}

VM366:1 Uncaught SyntaxError: Unexpected token {
let a = ["お","う","い"];FormData

VM375:1 Uncaught SyntaxError: Identifier 'a' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM375:1
let a = ["お","う","い"];

VM449:1 Uncaught SyntaxError: Identifier 'a' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM449:1
let a = ["お","う","い"];for (let x of a){

VM482:1 Uncaught SyntaxError: Unexpected end of input
let a = ["お","う","い"];for (let x of a){console.log(x);}

VM562:1 Uncaught SyntaxError: Identifier 'a' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM562:1
let w = ["お","う","い"];for (let x of a){console.log(x);}

VM574:1 お
VM574:1 う
VM574:1 い
undefined
let w = ["お","う","い"];for (let x of a){console.log(x);}

VM584:1 Uncaught SyntaxError: Identifier 'w' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM584:1
let w = ["お","う","い"];for (let x of a){console.log(x);}{

VM587:1 Uncaught SyntaxError: Unexpected end of input
let w = ["お","う","い"];for (let x of a){console.log(x);}

VM592:1 Uncaught SyntaxError: Identifier 'w' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM592:1
let j = ["お","う","い"];for (let x of a){console.log(x);

VM597:1 Uncaught SyntaxError: Unexpected end of input
let j = ["お","う","い"];for (let x of a){console.log(x);}

VM602:1 お
VM602:1 う
VM602:1 い
undefined
let j = ["お","う","い"];for (let x of a){console.log(x);}

VM607:1 Uncaught SyntaxError: Identifier 'j' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM607:1
let d = ["お","う","い"];for (let x of d){console.log(d);}

VM644:1 (3) ["お", "う", "い"]
VM644:1 (3) ["お", "う", "い"]
VM644:1 (3) ["お", "う", "い"]
undefined
let d = ["お","う","い"];for (let x of d){console.log(x);}

VM694:1 Uncaught SyntaxError: Identifier 'd' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM694:1
x
VM710:1 Uncaught ReferenceError: x is not defined
    at <anonymous>:1:1
(anonymous) @ VM710:1
let s =["りんご","レモン","みかん",]
undefined
let s =["りんご","レモン","みかん",]
VM762:1 Uncaught SyntaxError: Identifier 's' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM762:1
s
(3) ["りんご", "レモン", "みかん"]
for(let x of s){
console.log(x)};
VM841:2 りんご
VM841:2 レモン
VM841:2 みかん
undefined
for(let x of s){
console.log(s)};
VM857:2 (3) ["りんご", "レモン", "みかん"]
VM857:2 (3) ["りんご", "レモン", "みかん"]
VM857:2 (3) ["りんご", "レモン", "みかん"]
undefined
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
