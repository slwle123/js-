# js-图片热点
解决传统图片热点，在图片大小改变后热点定位失效的问题

应用场景：
不想用原型图工具生成页面（太难看，只能看功能布局，不能看真实ui）；
使用<map>标签发现特别是app项目ui，发现在不同屏幕手机上热点位置会改变，导致向用户展示的效果大打折扣

使用实例：
var mapControler1 = new mapControlFn("map1",{//map1为热点的名字，多个热点不能重名
                href:"02.html",//热点跳转的地址
                scaleW:0.08,//热点相对与内容图片宽的缩放比例
                scaleH:0.04,//热点相对与内容图片高的缩放比例
                left:"2%",//热点相对于屏幕右上角X轴位置
                top:"4.5%"//热点相对于屏幕右上角Y轴位置
            });
