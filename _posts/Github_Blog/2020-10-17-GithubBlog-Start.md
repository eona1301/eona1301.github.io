---
title: "[Github Blog] Jekyll 시작하기"
categories:
  - Github_Blog
tags:
  - minimal mistakes
  - jkeyll
  - blog
toc: true
---

📌 **작성자 개발 환경** <br>
**OS** : Windows 10<br>
**Tool** : Git Bash
{: .notice--primary}

# Github Blog 시작 목표

Github는 Programming Code를 올리고 공개하며 확인할 수 있습니다.<br>
<sup><i>(사실 Github 자체에 코드를 자유롭게 올리고, 익숙해지는 것도 꽤나 오래 걸렸죠😅)</i></sup><br>
각 Repositories마다 REAM.MD가 있어, 각각에 대한 설명을 적을 수 있습니다.<br>
<br>
하지만 이론적인 부분과 오류사항 등에 대해 자세히 기재하기에는 어려웠습니다.<br>
또, 좋은 코드는 단순히 프로그래밍 코드에서만 나오지 않기 때문에, 이를 기재하기 위해 Github blog를 설계하게 되었습니다.<br>
<br>
<br>

# 기본 환경 세팅

## Ruby 세팅

[Ruby for Windows](https://rubyinstaller.org/downloads/) 링크에 접속하여, 아래 화면과 같은 목록을 확인합니다.

![Ruby_Download](/image/posts/Github_Blog/ruby_download.png)

여기서 가장 중요한 것은 **Jekyll은 32bit**이기에, 설치시 (x64)가 아닌 **(x86)**으로 진행해야합니다.<br>
이는 초기 설정시 제일 빈번하게 발생하는 세팅 오류이기 때문에, 꼭 신경써서 설치해주셔야 합니다.

## Jekyll 세팅
