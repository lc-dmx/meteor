*[演示1](http://8.lcdmx.applinzi.com/)
*[演示2](http://9.lcdmx.applinzi.com/)
主要借助于css实现效果

@keyframes、animation及after伪元素的使用
```
.red{background:#FF3030;position: relative;top:130px;left:300px; 

animation:rainbows 1.15s infinite linear;animation-delay:0.15s;
 }

 .red:after{width:200px;height:200px; content:"";
 border-left: 1px solid #FF3030; display: block; 
 transform:rotate(45deg); 
 position: relative; top:-98px;left:42px;}
 
 
 .orange{background:#CD6600;position: relative;top:230px;left:400px; animation:rainbows 1.45s infinite linear;animation-delay:0.35s;}
.orange:after{width:200px;height:200px; content:"";border-left: 1px solid #CD6600; display: block; transform:rotate(45deg); position: relative; top:-98px;left:42px;}

.yellow{background:#FFD700;position: relative;top:200px;left:600px; 
animation: rainbows 1200ms infinite linear;animation-delay:0.55s;}
.yellow:after{width:200px;height:200px; content:"";border-left: 1px solid #FFD700; display: block; transform:rotate(45deg); position: relative; top:-98px;left:42px;}

.green{background:#7FFF00;position: relative;top:135px;left:800px; 
animation: rainbows 1.5s infinite linear;animation-delay:0.75s;}
.green:after{width:200px;height:200px; content:"";border-left: 1px solid #7FFF00; display: block; transform:rotate(45deg); position: relative; top:-98px;left:42px;}

.cyan{background:#6CA6CD;position: relative;top:130px;left:960px; 
animation: rainbows 1.25s infinite linear;animation-delay:0.95s;}
.cyan:after{width:200px;height:200px; content:"";border-left: 1px solid #6CA6CD; display: block; transform:rotate(45deg); position: relative; top:-98px;left:42px;}

.blue{background:#4169E1;position: relative;top:140px;left:1100px; 
animation: rainbows 0.75s infinite linear;animation-delay:1.15s;}
.blue:after{width:200px;height:200px; content:"";border-left: 1px solid #4169E1; display: block; transform:rotate(45deg); position: relative; top:-98px;left:42px;}

.purple{background:#9932CC;position: relative;top:130px;left:1200px; 
animation: rainbows 1.5s infinite linear;animation-delay:1.85s;}
.purple:after{width:200px;height:200px; content:"";border-left: 1px solid #9932CC; display: block; transform:rotate(45deg); position: relative; top:-98px;left:42px;}
@keyframes rainbows{
0%{opacity: 0;transform:scale(0) translate(0,0);}
50%{opacity:1;transform:scale(1)  translate(-200px,200px);}
100%{opacity:0;transform:scale(1) translate(-500px,500px);}
}
```
