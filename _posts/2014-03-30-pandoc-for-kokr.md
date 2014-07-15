---
layout: post
title: "Ubuntu 환경에서 pandoc으로 한글 pdf 생성"
date:   2014-03-30 00:00:00
categories: development
---

1. kotex 설치

```
sudo apt-get install ko.tex*
```
2. header.tex 생성 후 아래 내용 입력

```
\usepackage{kotex}
```
3. 변환

```
pandoc foo.md -o bar.pdf --include-in-header=header.tex
```

만약 `--include-in-header`가 없다면 아래와 같은 오류 메세지를 확인할 수 있다.

```
pandoc: Error producing PDF from TeX source.
! Package inputenc Error: Unicode char \u8:한 not set up for use with LaTeX.

See the inputenc package documentation for explanation.
Type  H <return>  for immediate help.
 ...                                              
                                                  
l.48 
```

> blogger.com에서 이동 - 2014/07/14
