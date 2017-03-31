# js-demo
 js数据链
 js内存
 真假数组
 
 
 var a = 100;
 
function func(){
    console.log(a);
    var a=200;
    console.log(a);
}
 
func();


var indexbox = {
    "index1": {"size": 1, "num": [0, 0]},
};
var cachesum = indexbox["index1"].num ;
// cachesum.length= 6;
console.log(cachesum);
console.log(indexbox["index1"].length);

var indexbox = {
    "index1": {"size": 1, "num": [0, 0]},
};
var cachesum = indexbox["index1"].num ;
// cachesum[1]= 6;
console.log(cachesum);
console.log(indexbox["index1"]);

js异步进程控制开辟一个新的空间监视两者的关系 可以是promis或者正常对象视具体情况而定
关键在于数据模型的建立是
a出发回来之前b是否出发
b未出发则照常，
b已出发则
a将要执行的动作放入之前开辟的空间 等待b执行完的 抛回状态码+绑定的事件
