选择器：

id选择器 $("#id属性的值")
标签选择器 $("标签的名字")
类选择器 $(".类样式的名字")
交集选择器 $("标签.类样式的名字")
并集选择器 $("选择器，选择器，选择器。。。。")
索引选择器 $("选择器:eq(索引的值)")
奇数筛选器 $("选择器：odd")
偶数筛选器 $("选择器：even")
筛选器     $("选择器：lt(索引)")
			$("选择器：gt(索引)")
其他选择器 $("选择器：last")
			$("选择器：first")

获取当前元素的其他方法
当前元素.next()----下一个兄弟元素
当前元素.nextAll()----后面所有兄弟元素
当前元素.prev()----前一个兄弟元素
当前元素.prevAll()----前面所有兄弟元素
当前元素.siblings()----所有兄弟元素（没有自己）
当前元素.parent()----父级元素
当前元素.children()----所有子级元素
当前元素.find("选择器")----从当前元素中找某个或者某些元素

方法：
.val()----操作表单元素的value属性，可以获取也可以设置
.text()
.html()
.css()
.addClass()
.removeClass()
.hasClass()
.index()

两个参数，参数1：时间参数2：回调函数
时间1000ms-1s
slow--- normal fast
.show()
.hide()
.stop(clearQueue,jumpToEnd)
.animate()
.slideUp()---滑入
.slideDown()
.slideToggle()
.fadeIn()
.fadeOut()
.fadeToggle()
.fadeTo(时间，透明度)


元素创建：
$("html的代码")
元素的添加
父级元素.append(子级元素)
子级元素.appendTo(父级元素)

clone()
父级元素.append($("父级元素1>子级元素"))----相当于剪切