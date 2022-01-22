## 브랜드 웹페이지

### 🖥환경
- HTML
- CSS
- Bootstrap

### 🖼썸네일
![03-full](https://user-images.githubusercontent.com/83056872/128043207-aadc3142-ba39-4295-9302-5d0319a53b75.jpg)

### ✍중요

**유튜브 영상을 이용하여 배경이 동영상인 웹페이지**
```html
<div class="video-background">
    <div class="video-foreground">
        <iframe src="https://www.youtube.com/embed/opFnZXt3KqQ?controls=0&showinfo=0&rel=0&autoplay=1&loop=1&playlist=opFnZXt3KqQ&mute=1" frameborder="0" allowfullscreen></iframe>
    </div>
</div>
```

**미디어쿼리를 사용하여 창의 크기에 따라 배경의 크기도 변화**
```css
/* min-aspect-ratio - 기기에 따른 폭과 너비 비율 지정*/
@media (min-aspect-ratio: 16/9) {
    .video-foreground { height: 300%; top: -100%; }
    }
@media (max-aspect-ratio: 16/9) {
.video-foreground { width: 300%; left: -100%; }
}
```
### 🏷URL
http://leap22.dothome.co.kr/brand/
