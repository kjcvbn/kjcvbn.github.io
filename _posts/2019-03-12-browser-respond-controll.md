---
title: Browser - 스팩 및 분기점 컨트롤 모듈
layout: post
tag: [respond, browser, library]
---

반응형 웹사이트 프로젝트 진행시 가장 기본이 되는 브라우저 스팩 체크 및 분기점 컨트롤 모듈입니다.

반응형 구간을 스크립트단에서 제어할때 주로 사용 되었으며 단순 레이아웃 변환 페이지가아닌 분기별 기능변환이 많을때 사용합니다.

브라우저 스팩에 따른 사용 가능 속성관련 Class와 분기점의 기준을 잡는 Class를 Html태그에 삽입하여 활용성을 높였으며 분기 변환시 CallBack Function을 등록하여 필요한 기능구현을 진행합니다.

자세한 사항 및 소스는 Gitbub페이지에서 확인하시면 됩니다.

<i class="fab fa-github"></i> [https://github.com/kjcvbn/browser](https://github.com/kjcvbn/browser)

### - Browser Support

|<i class="fab fa-chrome"></i>|<i class="fab fa-firefox"></i>|<i class="fab fa-internet-explorer"></i>|<i class="fab fa-opera"></i>|<i class="fab fa-safari"></i>|
|:------:|:------:|:------:|:------:|:------:|
|yes|yes|8+|yes|yes|
|======
{: .support-browser}