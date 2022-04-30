## 개요

---

Min Icon은 다양한 굵기와 스타일을 가진 아이콘 폰트입니다. 가변 폰트를 지원하여 원하는 두께의 아이콘으로 커스텀하여 사용할 수 있습니다.

- 총 124가지 아이콘
- 2가지 폰트, 2가지 스타일, 6개의 굵기 지원
- 가변폰트 지원

## 폰트 사용하기

---

css파일을 불러와 아이콘 폰트를 적용하여 사용합니다. 가변폰트를 사용할 경우 설정된 6가지 굵기 이외에 원하는 굵기로 변경하여 사용 가능합니다.

- **css파일 적용하기**
    
    원하는 종류의 폰트를 선택하여 붙여넣습니다.
    
    ```html
    <!-- Min Icon Round 사용하기 -->
    <link rel="stylesheet" href="https://poposnail61.github.io/css/min-icon-round.css">
    <link rel="stylesheet" href="https://poposnail61.github.io/css/icon.css">
    ```
    
    ```html
    <!-- Min Icon Round(가변폰트) 사용하기 -->
    <link rel="stylesheet" href="https://poposnail61.github.io/css/min-icon-round-vf.css">
    <link rel="stylesheet" href="https://poposnail61.github.io/css/icon.css">
    ```
    
    ```html
    <!-- Min Icon Square 사용하기 -->
    <link rel="stylesheet" href="https://poposnail61.github.io/css/min-icon-square.css">
    <link rel="stylesheet" href="https://poposnail61.github.io/css/icon.css">
    ```
    
    ```html
    <!-- Min Icon Square(가변폰트) 사용하기 -->
    <link rel="stylesheet" href="https://poposnail61.github.io/css/min-icon-square-vf.css">
    <link rel="stylesheet" href="https://poposnail61.github.io/css/icon.css">
    ```
    
- **icon 적용하기**
    
    ```css
    <i class="iFavorite"></i>
    ```
    
- **다른 스타일 적용하기**
    
    
    | 클래스명 | 설명 | 코드 |
    | --- | --- | --- |
    | .fill | 채워진 스타일의 아이콘 | <i class="iFavorite fill"></i> |
    | .spin | 돌가는 애니메이션 | <i class="iFavorite spin"></i> |
    | .iThin | 아주 얇은 아이콘 | <i class="iFavorite iThin"></i> |
    | .iLight | 얇은 아이콘 | <i class="iFavorite iLight"></i> |
    | .iRegular | 보통 아이콘 | <i class="iFavorite iRegular"></i> |
    | .iMedium | 중간 아이콘 | <i class="iFavorite iMedium"></i> |
    | .iBold | 굵은 아이콘 | <i class="iFavorite iBold"></i> |
    | .iBlack | 아주 긁은 아이콘 | <i class="iFavorite iBlack"></i> |
