# 제목(Header)

(h1~h6): #개수

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈

: 띄어쓰기2번 or <br />

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사<br/> 우리나라 만세

# 강조

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록

순서가 필요한 목록:

1. 내용적기

순서가 필요하지 않은 목록:

- 내용적기

들여쓰기:  
띄어쓰기4번 내용적기

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크

[대체텍스트](주소)  
[대체텍스트](주소 "설명")

[GOOGLE](https://www.google.com/)

[NAVER](https://www.naver.com/ "NAVER로 이동!")

# 이미지

![]() : 기본  
[![]]() : 이미지에 링크넣기

![STARBUCKS](https://www.starbucks.co.kr/common/img/common/logo.png)

[![STARBUCKS](https://www.starbucks.co.kr/common/img/common/logo.png)](https://www.starbucks.co.kr/index.do)

# 인용문

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문
>
> > 중첩된 인용문
> >
> > > 중중첩 인용문1
> > > 중중첩 인용문2
> > > 중중첩 인용문3

# 인라인 코드 강조

백틱

css에서 `backgroud` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록 코드 강조

```언어명
내용~~~
```

```html
<a href="#">구글</a>
```

```css
a {
  position: absolute;
}
```

```javascript
function func() {
  const a = "milk";
  return a;
}
```

```bash (<-git의 터미널)
$ git commit -m 'Study Markdown'
```

```plaintext (<-일반text)
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표

position 속성

| 값       |   의미    | 기본값 |
| -------- | :-------: | -----: |
| static   | 기준 없음 |      O |
| relative | 요소 자신 |      X |
| static   | 기준 없음 |      O |
| relative | 요소 자신 |      X |

# 원시 HTML

:그냥 html태그로 해버린다
markdown언어로 하기어려운것을 html로 작성해버린다.

동해물과 <u>백두산</u>이 마르고 닳도록<br/>하느님이 보우하사 우리나라 만세

\*밑줄
<u></u> or
<span style="text-decoration: underline;"></span>
해도된다

새창에서 열고싶을때
<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

이미지 크기할때
<img width="70" src="https://www.starbucks.co.kr/common/img/common/logo.png" alt="STARBUCKS">

# 수평선

---

---

---
