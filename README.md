# JSLite-touch

### Tap的使用方法

```
$("#ontouch").on("tap",function(){
	alert("我是 .on(tap) 方式");
	$(this).css({width:"200px",height:"100px",border:"1px red solid"});
})
$("#mytap").tap(function(){
	alert("我是 .tap() 方式");
	$(this).css({width:"300px",height:"30px",border:"1px blue solid"});
})
