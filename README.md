# My blog buid 과정 소개
20213103 황찬우

## 1. Local-Remote Repository 연동


**cwogong.github.io** 라는 Repository 생성 


Remote Repository 의 주소를 복사하여 


`git clone <path>`로 Local Repository에 복사


## 2. jekyll 설치

```
gem install bundler Jekyll
Jekyll new . --force
```


위의 과정을 통해 Jekyll 설치를 완료


`bundle exec jekyll serve` 를 통해 Jekyll server 실행



## 3. Markdown 연습 ( *_posts* 디렉토리 사용)


**_posts** 디렉토리에 **2021-12-15-MyFirstMarkdown.md** 파일을 생성


Python에서 `print()` 문을 사용하는 방법을 다양한 Markdown 문법을 사용하여 설명



## 4. theme 적용


**Tale** 이라는 theme 적용


**_posts** 디렉토리를 제외한 모든 파일들을 **cwogong.github.io** 의 디렉토리에 덮어씀


원하는 대로 페이지 수정 후 Remote Repository 에 연동하여 Remote 로도 잘 볼 수 있도록 함


## 5. comment 기능 추가


**Disqus** 를 이용하여 댓글 기능 추가


**_layout** 디렉토리 내의 **post.html** 파일을 수정 후


**_posts** 디렉토리 내의 파일들에 **comment: true** 를 입력해주면 완료!



