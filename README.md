### 使用方法
```
<ul class="vd-ul navbar-wrapper">
    <a href="#qzjs"><li class="menuItem active">签证介绍</li></a>
    <a href="#sxcl"><li class="menuItem">所需材料</li></a>
    <a href="#mzsm"><li class="menuItem">免责声明</li></a>
    <a href="#ydxz"><li class="menuItem">预订须知</li></a>
    <a href="#wxts"><li class="menuItem">温馨提示</li></a>
    <a href="#wyzx"><li class="menuItem">我要咨询</li></a>
</ul>
```
```
$(document).ready( function() { 
    $('.navbar-wrapper').stickUp({ 
        parts: { 0:'qzjs', 1:'sxcl', 2: 'mzsm', 3: 'ydxz',4:'wxts',5:'wyzx'}, 
        itemClass: 'menuItem', 
        itemHover: 'active',
    })
})
```
```
巧妙利用padding-top和margin-top，一正一负来调整距离
```