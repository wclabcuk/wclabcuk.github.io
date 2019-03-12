---
layout: post
title: CDMA(Code Division Multiple Access)
hide_title: true
img: "assets/img/portfolio/cdma.gif"
date: April, 08 2014
tags: [Lorem]
---



# CDMA(Code Division Multiple Access)

![image]({{ page.img | relative_url }})

CDMA은 제한된 주파수 자원을 다중 사용자에게 분할하는 방법으로 특정한 코드(Code)를 사용하는 것을 지칭한다. 분할의 방법이 시간(Time)이라면 TDMA가 될 것이고, 주파수(Frequency)라면 FDMA를 말하게 된다. CDMA는 한국에서 제일 먼저 상용화한 기술이다.
그 기본적인 방식은 대역확산(spread spectrum)을 이용한 것으로, CDMA는 대역확산방식이 가지는 장점을 그대로 이어받고 있다.
CDMA에서 사용하는 코드는 상호상관(Cross-Correlation)이 없는 (실제로는 거의 없는) 일종의 랜덤 시퀀스이다. 이는 다시 말해서 서로 코드가 맞지 않으면 다른 코드로 보내진 데이타는 전혀 혹은 거의 해독할 수 없다는 것이고, 이를 통해서 같은 주파수 대역에서 동시에 여러명이 통신을 할 수 있는 것이다.

CDMA의 특징으로는

개인간의 간섭/보안에 강하다.
셀(cell, 무선 통신에서의 기지국-단말기 간의 통신 단위) 설계가 쉽다.
소프트 핸드오버(cell이 바뀔 때 통신이 계속 되는 것)가 가능하다.
단말기 소비전력이 적은 편이다
레이크 수신기(지연이 있는 신호를 구분할 수 있는 수신기)를 사용할 수 있다.
단말기와 기지국 간에 시간이 정확하게 동기화 되어 있어야 한다.

실제적으로는 몇 개의 채널(파일럿, 동기, 통화 등등)로 구분되어 있어서, 파일럿 채널을 통해 단말기와 기지국 사이에 기본적인 확인을 하고 동기 채널에서 코드 동기화를 하여 통화채널로 음성데이터를 보내는 구조를 가지고 있다