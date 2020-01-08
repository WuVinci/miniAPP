# miniAPP
myMiniAPP
学习笔记
1 arguments 为function的内置对象，所有方法都有一个arguments。用来接受调用方法时传递过来的实参
function fun () {
  console.log(arguments)
}
fun(1,2,3);
为数组形式存储，有.length()方法，有下标，没有其他数组方法
2 函数两种声明方式
function fun(){}//命名函数
let fun = function(){}//匿名函数
3 js会将var变量和function方法提升，预解析，先解析再执行
变量先声明
3 对象
let dog = {
  name: 'kitty',
  age: 15,
  wof: function(){
    console.log('dog wof')
  }
}
1)创建对象
let cat={
  name:cat,
  age:1,
  miao:function(){}
}
2)构造函数创建对象//首字母大写
function 构造函数(){
  this. 属性 = 值;
  this.方法 = function(){}
  
} 
