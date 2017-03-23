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
