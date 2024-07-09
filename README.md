# 환경체

[배포처 바로가기](https://gongu.copyright.or.kr/gongu/wrt/wrt/view.do?wrtSn=13288471&menuNo=200023)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Environment`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Environment/Environment.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Environment/Environment.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Environment';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Environment/Environment.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Environment/Environment.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Environment/Environment.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Environment/Environment.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Environment/subsets/Environment-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Environment/subsets/Environment-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "Environment", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
환경체의 저작권 및 지적재산권은 한국환경공단에 있습니다. 
환경체는 누구나 무료로 다운로드 받아 사용할 수 있습니다. 환경체를 유료로 양도 및 판매하는 등의 상업적 행위와 음란물, 반사회적 제작물 등 부정적 이미지의 제작물에는 사용할 수 없습니다. 
영상매체, 인쇄매체, 웹, 모바일 등 다양한 매체에 사용이 가능하며 특별한 허가 절차 없이 사용할 수 있습니다.
```
