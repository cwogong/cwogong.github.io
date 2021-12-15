---
layout: post
title: 마크다운이란? (About Markdown)
comments: true
---

## 1. README.md 에서 md는??


다들 Github 를 사용하면서 한번쯤은 README.md 를 만들어 본 경험이 있을 것이다. 근데 보통 파일 명의 뒤에 .md 는 파일의 확장자 명인데, md 는 어떤 확장자인지 궁금해했었다. 그래서 찾아본 결과 md 는 **Markdown** 의 줄임말이라는 것을 알았고, **Markdown** 이 무엇인지 이번 유레카 프로젝트 강의를 들으면서 정확히 알게 되었다.




## 2. Markdown 이란?


**Markdown** 은 텍스트 기반의 마크업 언어로 2004년 존그루버에 의해 만들어졌으며 쉽게 쓰고 읽을 수 있으며, **HTML** 로 변환이 가능하다. 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있다. 지금 내가 블로그를 쓰는 것도 **Markdown** 을 이용하여 쓰는 것이다. **Markdown** 이 최근 각광받기 시작한 이유는 **Github** (https://github.com) 덕분이다. **Github** 의 저장소 Repository에 관한 정보를 기록하는 README.md는 **Github** 을 사용하는 사람이라면 누구나 가장 먼저 접하게 되는 **Markdown** 문서였다. **Markdown** 을 통해서 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고 가독성을 높일 수 있다는 강점이 부각되면서 점점 여러 곳으로 퍼져가게 된다.


## 3. Markdown 의 장단점


### Markdown 의 장점
```
1. 간단하게 작성 가능하다.
2. 별도의 도구 없이 특수기호와 문자만으로 작성 가능하다.
3. 다양한 형태로의 변환이 가능하다.
4. 텍스트(Text)로 저장되기 때문에 용량이 적어 보관이 용이하다.
5. 텍스트 파일이기 때문에 버전관리 시스템을 이용하면 변경 이력을 관리할 수 있다.
6. 지원하는 프로그램과 플랫폼이 다양하다.
```

### Markdown 의 단점
```
1. 표준이 없다.
2. 표준이 없기 때문에 도구에 따라서 변환방식이나 생성물이 다르다. 
3. 모든 HTML Markup 을 대신하지 못한다.
```


## 4. Markdown 의 문법 

### 글머리: 1~6 까지 지원
```
# This is Header1
## This is Header2
### This is Header3
#### This is Header4
##### This is Header5
###### This is Header6
```
# This is Header1
## This is Header2
### This is Header3
#### This is Header4
##### This is Header5
###### This is Header6

### 이탤릭체: 기울임체(italic) 작성
```
*This is Italic*
```
*This is Italic*
```
_This is Italic_
```
_This is Italic_

### 강조체: 굵은 글씨 작성
``` 
**This is bold**
```
**This is bold**
``` 
__This is bold__
```
__This is bold__

### 코드 작성
```
python 에서 출력을 할 때는 `print()`를 이용합시다.
```
python 에서 출력을 할 때는 `print()`를 이용합시다.

### 코드 블록

```
```~~~``` 을 이용하여 작성
```

```python
def sum(a, b):
  return a + b
```
