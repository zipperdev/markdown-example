# 제목(Header, h)

# 제목 1(h1)
## 제목 2(h2)
### 제목 3(h3)
#### 제목 4(h4)
##### 제목 5(h5)
###### 제목 6(h6)

# 문장(Paragraph, p)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

그냥 적기(?)

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세  

#### 띄워쓰기 2번, <br + />

# 강조(Emphasis)

_이탈릭_ - 또는 -*이탈릭*  
**두껍게**  
**_이탈릭 + 두껍게_**
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
2. 2
3. 3
   1. 이렇게 목록 안에 목록 넣기 가능!
4. 1번이라도 그다음 번호로 처리!

- 순서가 필요하지 않은 목록
- 2
- 3
- 4
- 숫자 대신 점이 있다!
    - 똑같이 목록 안에 넣기 가능!

# 링크(Links)

<a href="https://zipperdev.com">Zipper_</a>

[Google](https://google.com)

[Naver](https://naver.com "네이버로 이동!")

# 이미지(Images)

![대체 텍스트](https://heropy.blog/css/images/logo.png)

[![대체 텍스트](https://heropy.blog/css/images/logo.png)](https://naver.com)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장
> (네이버 국어사전)

> Yesterday is a history, future is mystery. And today is a gift. That's why we call present.

> 인용문안에
>> 다른
>>> 인용문을 넣을 수 있다!

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

백틱을 이용해서 `강조`한다

# 블록(block) 코드 강조

```html
<a href="https://www.google.com">Google</a>
```

백틱 3개를 이용해서
```js 
function func() {
    var a ="AAA";
    return a;
}
```
코드를 강조하여 적을 수 있다!

```bash
$ git commit -m "Study Markdown"
```

```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
:--|:--:|--:
static | 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

콜론 기호로 정렬 기준을 정한다!

# 윈시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세

___

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)
---

***

___


~~~ 

