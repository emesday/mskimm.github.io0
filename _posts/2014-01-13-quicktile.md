---
layout: post
title: "QuickTile, a Winsplit-Revolution alternative for X11 (incl. Ubuntu)"
date:   2014-01-13 00:00:00
categories: development
---

겨우 Unity에 적응하고 있었는데, 13.10으로 upgrade하면서 nabi의 글자판을 세벌식으로 도저히 바꿀 수 없게되었다. 
결국, Xfce로 갈아타고 세벌식으로 바꾸는 것은 성공했지만 Compiz의 다양한 설정을 사용할 수 없게 되었다. 
그 중 가장 아쉬운 것이 winsplit revolution과 같은 역할을 하는 Compiz-Grid 기능 인데, 
구글링 결과 좋은 프로그램을 찾게되었다.

 - 이름: QuickTile
 - URL: http://ssokolow.com/quicktile/ 
 - 설치 방법
    - 의존성:
```
sudo apt-get install python python-gtk2 python-xlib python-dbus python-wnck
```
    - 프로그램:
```
git clone git://github.com/ssokolow/quicktile
cd quicktile; sudo python setup.py install
```
    - 기존 ctrl+alt 단축키 제거
       - 설정관리자 -> 창관리자 -> 키보드 -> 모든 <Alt><Control>KP_[1-9] 제거
    - 재부팅


> blogger.com에서 이동 - 2014/07/14
