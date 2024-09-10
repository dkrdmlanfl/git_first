# git 사용법 

```angular2html
md는 마크다운임을 알려주는 확장명이다.
대소문자 잘 구분하여 파일명 작성할 것
```

1. 로컬 저장소를 생성한다.
2. 코드를 작성한다.
3. 변경내역에 대해 커밋(버전)을 생성한다.
   1. 변경사항을 git이 감지한다. (.gitignore에 등록된 파일/디렉토리는 제외)
   2. 커밋으로 남길 변경사항을 스테이징 영역에 추가한다.
   3. 커밋 메시지와 함께 커밋을 생성한다.

```angular2html
윈도우키 + . = 윈도우 이모티콘 생성
```
## 🥐 인생 첫 커밋을 만들었다! 나는 GIT을 사용하는 개발자다!❤️

wowowowwowowowowwowowowowowowowowow!!!!!

### 추워잉. 배고파잉. 졸려잉.

## 추가 커밋용 추가 글. 추가추가 슈가슈가룬 초코초코룬

![네눈박이](data:image/jpeg;base64,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)
![백구](https://cdn.pixabay.com/photo/2020/04/28/08/51/korean-jindo-dog-5103470_1280.jpg)

### 진돗개 귀여워잉
