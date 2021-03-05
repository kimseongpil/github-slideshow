# Your GitHub Learning Lab Repository for Introducing GitHub

Welcome to **your** repository for your GitHub Learning Lab course. This repository will be used during the different activities that I will be guiding you through. See a word you don't understand? We've included an emoji 📖 next to some key terms. Click on it to see its definition.

Oh! I haven't introduced myself...

I'm the GitHub Learning Lab bot and I'm here to help guide you in your journey to learn and master the various topics covered in this course. I will be using Issue and Pull Request comments to communicate with you. In fact, I already added an issue for you to check out.

![issue tab](https://lab.github.com/public/images/issue_tab.png)

I'll meet you over there, can't wait to get started!

This course is using the :sparkles: open source project [reveal.js](https://github.com/hakimel/reveal.js/). In some cases we’ve made changes to the history so it would behave during class, so head to the original project repo to learn more about the cool people behind this project.

<a id="chapter-1"></a>
# Title 1

# Below is MarkDown TEST

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5


## 간단한 제목 크기
큰제목
===

작은제목
---

## 인용문 들여쓰기
>This is block quote.
>I Can highlight lines
>> And also do on multiple levels!
>>> One more depth.<br>
>>> same level depth.

## 코드블럭
`this is code block one line'

```somecomment
    line1
    line2
    line3
```   

## 코드블럭 개발언어 스타일
```C
int val = 10;
printf(%S, "Hello, World!");
```

```html:test.html

<div>
 <p>Hello, Git!</p>
</div>
```

## 각주(footnote)

마크다운의 각주 링크인데 동작하지 않습니다.[^footnote1].

그래서 대안으로 이코드를 사용합니다..<sup>[1](#myfootnote1)</sup>

## TEXT 스타일
*강조-Italic*

**강조-Bold**

***강조-Italic, Bold중첩***

~~취소선~~

__밑줄(안되네)__



## 수평선(단락구분에 많이 사용)
***
---
___

## 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    - 순서가 필요없는 목록
    - 순서가 필요업는 목록
1. 순서가 필요한 목록
    - 순서가 필요한 목록
    - 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
    - 목록1
    - 목록2
    - 목록3


## 링크

인라인 : [DAUM](http://www.daum.net "링크설명입니다. DAUM")

참조 : 검색엔진은 [Google][1] 이 있다.<br>
클릭하세요.
[1]:http://google.com/ "구글로 이동합니다."

URL링크 : <http://www.google.com>

내부링크 : [목차로이동](#title-1)

앵커</br>
\*[1장](#chapter-1)


## 테이블

| Header One | Header Two | Header Three | Header Four |
| ---------- | :--------- | :----------: | ----------: |
| Default    | Left       | Center       | Right       |

| Column 1 | Column 2 | Column 3 | Column 4 |
| -------- | :------: | -------- | -------- |
| No span  | Span across three columns    |||


## 이미지
![Minion](http://octodex.github.com/images/minion.png "tool tip title")

<!-- 주석처리 
## 체크박스
- ( ) 운동하기
- (x) 강의듣기
-->

***
[^footnote1]: MarkDown은 경량 마크업 언어입니다. 확장자는 md.

<a name="myfootnote1">1</a>: 왜일까요??
