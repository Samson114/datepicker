来源：http://www.my97.net/dp/demo/index.html

1. 简介目前的版本是:4.8

2. 注意事项•My97DatePicker目录是一个整体,不可破坏里面的目录结构,也不可对里面的文件改名,可以改目录名
•My97DatePicker.htm是必须文件,不可删除(4.8以后不存在此文件)
•各目录及文件的用途: 
WdatePicker.js 配置文件,在调用的地方仅需使用该文件,可多个共存,以xx_WdatePicker.js方式命名
config.js 语言和皮肤配置文件,无需引入(4.8以后合并入WdatePicker.js)
calendar.js 日期库主文件,无需引入
My97DatePicker.htm 临时页面文件,不可删除(4.8以后不存在此文件)
目录lang 存放语言文件,你可以根据需要清理或添加语言文件
目录skin 存放皮肤的相关文件,你可以根据需要清理或添加皮肤文件包
•当WdatePicker.js里的属性:$wdate=true时,在input里加上class="Wdate"就会在选择框右边出现日期图标,如果您不喜欢这个样式,可以把class="Wdate"去掉,另外也可以通过修改skin目录下的WdatePicker.css文件来修改样式
3. 支持的浏览器IE 6.0+ , Firefox 2.0+ , Chrome, Opera 9.5+ , Safari 3.0+


  

注意:IE 8.0是完美支持的,如果你在IE8上使用遇到问题,请与我取得联系,务必附上能再现你的问题的纯HTML代码包

