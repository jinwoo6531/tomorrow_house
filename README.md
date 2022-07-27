1. 기본설정

2. 폰트설정

3. Sass 변수명

- 숫자로 시작 X
- All 소문자 or All 대문자
- 예를들어(소문자일 경우 하이픈, 대문자일경우 언더바)
  $cat-1: 1;
  $CAT_1: 1;

4. Mixin

- @mixin test() {}
- 함수처럼 사용가능

#내일의 집

### 1. GNB

- 로그인을 하지 않은 경우

```html
<div class="button-group">
  <button
    class="gnb-icon-button is-search lg-hidden"
    type="button"
    aria-label="검색창 열기 버튼"
  >
    <i class="ic-search"></i>
  </button>
  <a
    class="gnb-icon-button is-cart"
    href="/"
    aria-label="장바구니 페이지로 이동"
    ><i class="ic-cart"></i
  ></a>
</div>
```
