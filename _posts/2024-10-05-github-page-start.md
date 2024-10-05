---
title: 블로그 만들기 - github pages
date: 2024-10-05 14:38:00 +0900
lastmod: 2024-10-05 14:38:00 +0900
categories: [Github, blog]
tags: [GitHub, GitHub Pages, 블로그, blog, github.io]
---


# 블로그(blog) 개설
이 글에서는 블로그 만드는 과정을 소개하고자 합니다.  
**Github를 이용하여 블로그**를 만드실 분은 참고하시면 좋습니다.

<hr>  

# 1. 블로그 플랫폼 선택
블로그 플랫폼으로는 tistory, naver, vlog 등이 있습니다.  
플랫폼마다 특징, 진입장벽, 또는 제한 사항을 확인하시어 자신에게 맞는 플랫폼을 찾으시는 게 좋습니다.  
  
저는 **개발 블로그 운영** 목적이었기에, repository로도 활용하며 프로젝트를 공유하기에 좋은 플랫폼인 **github**를 이용하였습니다.  

개발 경험이 없거나 Code에 익숙하지 않으신 분은 어려우실 수 있으니, 타 플랫폼 이용을 추천드립니다.  

> **Github❓**
    - GitHub는 다른 사람과 함께 코드를 작성하고 저장하며 공유할 수 있는 클라우드 기반 플랫폼입니다.  
    - 🔗 [Github](https://docs.github.com/ko/get-started/start-your-journey/about-github-and-git)

<hr>  

# 2. 블로그 생성
- 블로그는 Github에서 제공해주는 **Gtihub Pages**를 이용하여 생성하였습니다.
> **GitHub Pages**❓ 
    - GitHub Pages는 GitHub를 통해 호스트되고 게시되는 퍼블릭 웹 페이지입니다.
    - 하기 문서 링크는 한글로 명료하게 안내해주어 편합니다.
    - 🔗 [Gihub Docs - GitHub Pages](https://docs.github.com/en/pages/quickstart)


## GitHub Pages - 빠른 시작
<em style="color:grey">※ 이미지 출처 : github 문서</em>  

- **생성 방법** : github에 특정 이름으로 Repository를 생성하면 자동으로 github에서 페이지를 생성해줍니다.
- **Repository 생성** : Jekyll 테마 선택기를 사용하여 미리 만들어진 테마를 로드하기 위해, Repository 이름을 **<block style="color:red">[username]</block>.github.io**로 생성해야 합니다. 또한 **<block style="color:red">[username]</block>.github.io**이 home url로 설정되니 <b style="color:red">소문자</b>로 생성하시길 바랍니다.  
- 예시 : **<block style="color:red">venacode</block>.github.io**
![github-page-quick-start](/assets/posts/2024-10-05-github-page-start/github-quick-start.png)

<hr>  

# 3. 사용자 정의 설정
- 파일목록에서 **_config.yml**이 생성되었다면 해당 파일을 수정하셔도 되며,
- 만약 빈프로젝트로 생성 등으로 인해 없다면, 최상단 경로(/)에 **_config.yml** 파일을 생성하여 적용하시면 됩니다.
![github-page-quick-start](/assets/posts/2024-10-05-github-page-start/github-quick-start-config.png)

<hr>  

# 4. 테마(theme) 바꾸기
- 기본 제공 형태로 사용하셔도 되지만, 자신만의 스타일을 적용하기 위해 테마나 커스텀 가능합니다.
- 제 블로그는 UX 및 코드 관리를 위해, [jekyll-theme-chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)를 적용하였습니다.
- 테마 적용은 다음 글에 이어서 작성하도록 하겠습니다.

