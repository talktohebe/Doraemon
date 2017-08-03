## Doraemon——用CSS画的哆啦A梦
- 偶然看到有一篇文章用纯css画小黄人的，心痒，于是画了一个哆啦A梦
- 效果
![](http://r.photo.store.qq.com/psb?/V11GttOD0YKhmx/xdhDh4pCFmW1QK9791ijNLpyF4PWvRY4RH6M2CY12pk!/r/dB4BAAAAAAAA)  
- html结构
```
<body>
<div class="wrapper">
    <!--head begin-->
    <section class="head">
        <div class="face">
            <div class="beard-left">
                <span class="beard-lOne"></span>
                <span class="beard-lTwo"></span>
                <span class="beard-lThree"></span>
            </div>
            <div class="beard-right">
                <span class="beard-rOne"></span>
                <span class="beard-rTwo"></span>
                <span class="beard-rThree"></span>
            </div>
            <span class="vertical-nose"></span>
            <div class="mouse">
                <span class="mouseLine1"></span>
                <span class="mouseLine2"></span>
            </div>
        </div>
        <div class="eye-left">
            <div class="eye-small-left"></div>
        </div>
        <div class="eye-right">
            <div class="eye-small-right"></div>
        </div>
        <div class="nose">
            <span class="nose-circle"></span>
        </div>

    </section>
    <!--head end-->

    <!--body begin-->
    <section class="body">
        <div class="hand-left">
            <div class="arm-left"></div>
            <div class="round-hand-left"></div>
        </div>
        <div class="hand-right">
            <div class="arm-right"></div>
            <div class="round-hand-right"></div>
        </div>
        <div class="trunk">
            <div class="belly">
                <div class="pocket"></div>
            </div>
        </div>
        <div class="ribbon"></div>
        <div class="shade"></div>
        <div class="foot-left"></div>
        <div class="foot-right"></div>
        <div class="bell">
            <div class="bell-line"></div>
            <div class="bell-sCircle"></div>
            <span class="bell-vertical"></span>
        </div>

    </section>
    <!--body end-->

</div>
</body>
```
