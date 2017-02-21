---
layout: post
title: Timeline linked with a graph
desc: Scroll interaction이 서로 연결되어 있는 그래프와 리스트
proj-url: https://framer.cloud/RjBTp
proj-num: 04
---

  
  
좌-우 스크롤의 그래프와 상-하 스크롤의 타임라인형 리스트가 있는 History 화면에서,  
그래프를 스크롤하거나, 리스트를 스크롤 할 때 서로 싱크되어 스크롤이 되는 구조.  
그래프와 리스트에서 현재 선택된 날짜/데이터를 강조해주는 Selector를 양측 공용으로 활용해보는 방향으로 구현해 봄. 
  
리스트를 스크롤할 때 상단의 그래프가 따라 움직이는 것은 자연스러운 듯 하나,  
반대로 그래프를 스크롤할 때 하단의 리스트가 따라 움직이는 것은 살짝 불편한 느낌도 있는 듯 하다.  
(스크롤 할 때 손으로 가려지는 하단 영역이 움직이는 것도 한 몫 하는 듯)  
두 scroll content의 width, height가 같지 않고, 화면 내에 보이는 개수도 달라서  
scroll.speed와 draggable.momentumOptions 조절을 통해 scroll content의 적절한 무게감을 찾아 주는 것도 중요한 듯.  
  

