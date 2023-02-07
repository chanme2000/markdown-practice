# 제목(Header)
# Heaer 1
## Heaer 2
### Heaer 3
#### Heaer 4
##### Heaer 5
###### Heaer 6

# 문장(Paragrph)
## 줄바꿈(공백2개, 태그 사용)
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세<br />
무궁화 삼천리 화려 강산<br />
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)
_이텔릭_<br />
**두껍게**  
**_기울임과 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)
## 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
## 목록 하위 구조 추가(들여쓰기 두번)
1. 순서가 필요한 목록
    1. 안쪽 하위 구조 목록
    1. 안쪽 하위 구조 목록
1. 순서가 필요한 목록

## 순서가 없는 목록
- 순서가 없는 목록
- 순서가 없는 목록
- 순서가 없는 목록
    - 안쪽 하위 구조 목록
    - 안쪽 하위 구조 목록
- 순서가 없는 목록

# 링크(Link)
<a href="http://google.com">GOOGLE</a>

[GOOGLE](http://google.com)

<a href="http://naver.com" title="naver로 이동!">NAVER</a>

[NAVER](ttp://naver.com "naver로 이동!")

<a href="http://naver.com" title="naver로 이동!" target="_blank">NAVER</a>

# 이미지(Image)
[한화이글스](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRA3OB9GGPNCf5QURENHOZGSx9xPvHyHpikF1mx1b6Ls9m6xymfh38-sw4aNIFp34CiP_k&usqp=CAU)  

![한화이글스](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRA3OB9GGPNCf5QURENHOZGSx9xPvHyHpikF1mx1b6Ls9m6xymfh38-sw4aNIFp34CiP_k&usqp=CAU)

[![한화이글스](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRA3OB9GGPNCf5QURENHOZGSx9xPvHyHpikF1mx1b6Ls9m6xymfh38-sw4aNIFp34CiP_k&usqp=CAU)](https://www.hanwhaeagles.co.kr/index.do)

#인용문(BlockQuote)
> 모든 일은 참되고 실속이 있도록 <br />애써 실행하라.(무실역행) - 안창호  
> [위키인용집](https://ko.wikiquote.org/wiki/%EB%AA%85%EC%96%B8)

## 인용문 중첩
> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중첩된 인용문 1
>>> 중첩된 인용문 1

# 인라인 코드 강조
css에서 `background`혹은 background-image 속성으로 배경 이미지를 삽입할 수 있습니다.

# 블록코드 강조
```html
<a href="http://naver.com" title="naver로 이동!" target="_blank">NAVER</a>
```
```css
a { background-color : #000 }
```
```javascript
function first() {
  console.log('Hello World);
}
```
```bash
$ git commit -m "Study Markdown"
```
```plaintext
기본적인 텍스트를 화면에 보여주기위해 사용되는 요소
```

# 표(Table)
## 표지션 속성을 표로 작성
값 | 의미 | 기본값
--|:--:|--:
static | 기본-없음 | O
relative | 요소-자신 | X
absolute | 위치 및 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)
## 두번 뛰워쓰기는 일부 사이트에서 동작하지 않을 수 있음

동해물과 <span style="text-decoration:underline">백두산</span>이 마르고 닳도록  
하느님이 보우하사 우리나라 만세<br />
무궁화 삼천리 화려 강산<br />
대한 사람 대한으로 길이 보전하세

___

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRA3OB9GGPNCf5QURENHOZGSx9xPvHyHpikF1mx1b6Ls9m6xymfh38-sw4aNIFp34CiP_k&usqp=CAU)" alt="한화이글스">

# 수평선(Horizontal Rule)
---
___
***