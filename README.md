# swiperCube
swiper立体轮播

## 效果
![image](https://github.com/xiaojiandong/swiperCube/blob/master/img/view.jpg)

## js代码
```js
var swiper = new Swiper('.swiper-container', {
        pagination: '.swiper-pagination',
        effect: 'coverflow',
        grabCursor: true,
        centeredSlides: true,
        slidesPerView: 'auto',
        speed: 700, //动画持续时间
        autoplayDisableOnInteraction:false, //用户操作之后（swipes,arrow以及pagination 点击）autoplay不会被禁掉，用户操作之后每次都会重新启动autoplay
        autoplay: 2500 ,
        coverflow: {
            rotate: 50, // 旋转角度 150
            stretch: 0,
            depth: 100, // 400
            modifier: 1,
            slideShadows : true
        }
    });
```
