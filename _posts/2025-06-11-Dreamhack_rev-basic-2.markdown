---
layout: post
title:  DreamHack문제-rev-basic-2
date:   2025-06-11
category: code
image: assets/img/blog/revcode.png
author: Ryan Adlard
tags: code
---

# Dream Hack 문제
### rev-basic-2
Dream Hack 문제중 rev-basic-2 문제 풀이다.
ida를 이용하여 코드를 봤을 경우, if문이 존재하고, if문을 통과 했을 경우 correct가 나온다.
이를 통해 무엇을 입력해야 correct가 나오는지 알 수 있다.
<br>
<img src="assets/img/blog/revcode.png" alt="Heartbeat Diagram" style="max-width: 100%; border-radius: 12px;" />
<br>
해당 문제 같은 경우 sub_140001000함수에 통과해야 true가 나오는 걸 확인 할 수 있다.
<br>
<img src="assets/img/blog/revcode2.png" alt="Heartbeat Diagram" style="max-width: 100%; border-radius: 12px;" />
<br>
위의 사진은 sub_140001000함수의 사진이고, ac의 문자열과 같아야 통과할 수 있는 것을 확인 가능하다.
이를 통해 ac의 문자열을 타고 들어가면 아래 사진처럼 해당 문자열이 뭔지 알 수 있게된다.
<br>
<img src="assets/img/blog/revcode3.png" alt="Heartbeat Diagram" style="max-width: 100%; border-radius: 12px;" />
<br>
리버싱의 기초적인 문제인 만큼 제일 쉬운 난이도의 문제다.
* ida로 코드 확인
* if문을 타고 들어가서 조건 확인
* 조건의 문자열 확인 후 해당 문자열 작성
