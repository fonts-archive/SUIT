# 수트

[배포처 바로가기](https://sunn.us/suit/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `SUIT`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'SUIT';
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Thin.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Thin.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Thin.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Thin.ttf') format('truetype');
}
@font-face {
  font-family: 'SUIT';
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-ExtraLight.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-ExtraLight.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-ExtraLight.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-ExtraLight.ttf') format('truetype');
}
@font-face {
  font-family: 'SUIT';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Light.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Light.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Light.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'SUIT';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Regular.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Regular.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Regular.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Regular.ttf') format('truetype');
}
@font-face {
  font-family: 'SUIT';
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Medium.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Medium.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Medium.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Medium.ttf') format('truetype');
}
@font-face {
  font-family: 'SUIT';
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-SemiBold.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-SemiBold.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-SemiBold.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-SemiBold.ttf') format('truetype');
}
@font-face {
  font-family: 'SUIT';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Bold.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Bold.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Bold.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Bold.ttf') format('truetype');
}
@font-face {
  font-family: 'SUIT';
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-ExtraBold.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-ExtraBold.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-ExtraBold.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-ExtraBold.ttf') format('truetype');
}
@font-face {
  font-family: 'SUIT';
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Heavy.woff2') format('woff2'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Heavy.woff') format('woff'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Heavy.otf') format('opentype'),
    url('https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/SUIT-Heavy.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/subsets/SUIT-dynamic-subset.css"
  type="text/css"
/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SUIT/subsets/SUIT-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "SUIT", -apple-system, BlinkMacSystemFont, "Segoe UI",
  Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
SUIT―수트는 오픈소스입니다. SIL Open Font License에 따라 개인 또는 기업이 영리적, 비영리적 목적으로 자유롭게 사용할 수 있습니다. 
단, SUIT를 단독 판매하면 안 됩니다. 한글 타입페이스는 본고딕을 기반으로 합니다. 
SUIT에 대한 제안 및 문의는 이메일로 보내주세요.
```
