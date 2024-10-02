# Template for Capstone
이 레파지토리는 학생들이 캡스톤 프로젝트 결과물을 위한 레파지토리 생성시에 참고할 내용들을 담고 있습니다.
1. 레파지토리 생성
2. 레파지토리 구성
3. README.md 가이드라인
4. README.md 작성팁

***

## 1. 레파지토리 생성 

* https://classroom.github.com/a/L5A1FzLa
* 위 Github Classroom 링크에 접속해 본인 조의 github 레파지토리를 생성하세요.
![repo생성이미지](https://github.com/pnucse-capstone/Capstone-Template-2023/assets/113662020/13e5cc55-0182-4485-b872-bd57eba3fb9b)
* 레파지토리 생성 시 team 이름은 "{연도}-{학기}-{조번호}" 형식으로 생성하세요.
* 예를 들어, 2024년도 1학기(전기) 3조의 team 이름은 "2024-1-03" 입니다.
* 이 경우 "capstone-2024-1-04" 이라는 이름으로 레파지토리가 생성됩니다.

***

## 2. 레파지토리 구성
* 레파지토리 내에 README.md 파일 생성하고 아래의 가이드라인과 작성팁을 참고하여 README.md 파일을 작성하세요. (이 레파지토리의 SAMPLE_README.md 참조)
* 레파지토리 내에 docs 디렉토리를 생성하고 docs 디렉토리 내에는 과제 수행 하면서 작성한 각종 보고서, 발표자료를 올려둡니다. (이 레파지토리의 docs 디렉토리 참조)
* 그 밖에 레파지토리의 폴더 구성은 과제 결과물에 따라 자유롭게 구성하되 가급적 코드의 목적이나 기능에 따라 디렉토리를 나누어 구성하세요.

***

## 3. README.md 가이드라인 

* README 파일 작성시에 아래의 5가지 항목의 내용은 필수적으로 포함해야 합니다.
* 아래의 5가지 항목이외에 프로젝트의 이해를 돕기 위한 내용을 추가해도 됩니다.
* SAMPLE_README.md 이 단순한 형태의 예제이니 참고하세요.

### 1. 프로젝트 소개

프로젝트 명, 목적, 개요 등 프로젝트에 대한 간단한 소개글을 작성하세요.

### 2. 팀 소개

프로젝트에 참여한 팀원들의 이름, 이메일, 역할를 포함해 팀원들을 소개하세요.

### 3. 구성도

프로젝트 결과물의 개괄적인 동작을 파악할 수 있는 이미지와 글을 작성하세요.

### 4. 소개 및 시연 영상

프로젝트 소개나 시연 영상을 넣으세요.

### 5. 사용법

프로젝트 결과을 사용 위해 필요한 소프트웨어 요구사항 및 설치법, 그리고 간단한 사용법을 작성하세요.

***

## 4. README.md 작성팁 
* 마크다운 언어를 이용해 README.md 파일을 작성할 때 참고할 수 있는 마크다운 언어 문법을 공유합니다.  
* 다양한 예제와 보다 자세한 문법은 [이 문서](https://www.markdownguide.org/basic-syntax/)를 참고하세요.

### 4.1. 텍스트 추가
```markdown
본문입니다.

# This is a Header 1
## This is a Header 2
### This is a Header 3
#### This is a Header 4
##### This is a Header 5
###### This is a Header 6

**bold**
_italic_
`code`

1. Ordered
2. List

* Unordered 
* List

<!--주석-->

[link text](URL)
```

### 4.2. 이미지 추가

```markdown
<!--![이미지 이름](이미지 URL 링크)-->
![정보융합공학과 이미지](https://user-images.githubusercontent.com/100384365/192478661-5dc79a18-b076-48ef-b842-bcf65b0d8d44.jpg)
```

![정보융합공학과 이미지](https://user-images.githubusercontent.com/100384365/192478661-5dc79a18-b076-48ef-b842-bcf65b0d8d44.jpg)

이 때, 이미지 URL은 아래와 같이 github issue를 통해 image file만을 github server에 업로드하고 URL을 얻을 수 있습니다. (URL만 copy하고 issue 제출 X)

![이미지 URL 얻기1](https://user-images.githubusercontent.com/113662020/193720098-9f19831b-7107-4a91-9821-a977ff82e8de.png)
![이미지 URL 얻기2](https://user-images.githubusercontent.com/113662020/193720141-8b813247-b77b-4590-83cc-f87a4e63296b.png)

### 4.3. 유튜브 영상 추가
```markdown
<!--[![영상 이름](유튜브 영상 썸네일 URL)](유투브 영상 URL)-->
[![부산대학교 정보컴퓨터공학부 소개](http://img.youtube.com/vi/zh_gQ_lmLqE/0.jpg)](https://www.youtube.com/watch?v=zh_gQ_lmLqE)    
```
[![부산대학교 정보컴퓨터공학부 소개](http://img.youtube.com/vi/zh_gQ_lmLqE/0.jpg)](https://www.youtube.com/watch?v=zh_gQ_lmLqE)    

이때 유투브 영상 썸네일 URL은 유투브 영상 URL로부터 다음과 같이 얻을 수 있습니다.

Youtube URL: https://www.youtube.com/watch?v={동영상 ID}

Youtube Thumbnail URL: http://img.youtube.com/vi/{동영상 ID}/0.jpg 

예를 들어, https://www.youtube.com/watch?v=zh_gQ_lmLqE 라고 하면 썸네일의 주소는 http://img.youtube.com/vi/zh_gQ_lmLqE/0.jpg 이다.






