---
layout: post
title: PQ Monitoring
hide_title: true
img: "assets/img/portfolio/SCADA.png"
date: April, 08 2014
tags: [Projects]
---



# IoT-Based Smart Grid Power Quality Monitoring

![image]({{ page.img | relative_url }})
그림 1.분산형 SCADA 시스템 분산형 SCADA 시스템과 SCADA PQM 핵심기술


본 과제에서는 신뢰성/안정성 보장되는 미래형 SG 구축을 위해 다음의 3 가지 SCADA PQM 핵심기술 확보를 연구 목표로 삼고 있다.

WPC 기반의 PQ 신호 Denoising 기법 및 PQE (power quality event) 검출 (Detection)
PQ 빅데이터를 활용한 DNN + DM 기반의 PQE 분류 (Classification) 알고리즘 연구
SCADA PQI (power quality index: 전력품질지수) 정보 전송 프로토콜 설계
지구 온난화 (기상이변), 환경오염 (방사선 폐기물) 등의 당면문제를 고려할 때 기존 전력 그리드의 저탄소 그린(신재생)에너지 기반의 SG (smart grid)로의 대체가 시급하다. SG는 기존의 중앙 집중형 에너지 공급체계가 아닌 태양전지, 풍력, 조력 등의 각종 신재생에너지원 기반의 분산형 에너지 공급체계이며 누구든지 자유롭게 에너지 거래(발전/저장/판매)에 참여하는 미래 전력망으로 DR, BEMS, 스마트 시티, PHEV 등의 각종 고급 지능형 에너지 서비스가 가능하여 진다.  이러한 고급 에너지 서비스를 제공하는 신뢰성/안정성 보장되는 SG 구축을 위해서는 효과적인 전력품질 (PQ: Power Quality) 감시/관리/모니터링이 가능한 분산형 전력품질모니터링 (PQM: Power Quality Monitoring) 기능을 갖춘 SCADA SCADA는 일반적으로 각종 인프라, 산업시설, 설비의 각종 원격 감시, 제어 및 모니터링 (제조 공정, 에너지, 정수처리, 건물내 히터/에어콘 등) 시스템을 가리키지만, 여기서는 SG PQ를 원격 감시하는 PQM 시스템을 가리킨다.
시스템의 개발이 전제된다고 볼 수 있다 [1].
특별히 최근 전기자동차, 에너지 저장장치, 인버터기반의 에너지원 등 각종 다양한 노드의 증가로 인해 SG 망내로 인입되는 PQ 데이터 부하가 급속히 증가하고 있어 SG의 신뢰성 저하가 극히 우려되고 있다. 가까운 장래에 전기자동차 시대와 신재생 에너지원의 증가 추세를 감안할 경우, 네트워크 운용자에게 있어 가장 시급한 당면과제는 SG의 신뢰성/안정성을 보장하는 PQM 시스템의 구축임을 알 수 있다. 최근 (2016년 10월) 이러한 우려를 반영하여, IEEE PES에서 주관한 유수 SG 국제학술대회인 ISGT [2]에서는 PQ 빅데이터 분석 기반 SG PQM 개선방안이 별도의 공개 세션으로 만들어져 활발한 토의가 이루어졌다.

최종연구목표
본 과제의 최종연구목표는 전력계통 지능화 기능을 갖는 SG의 신뢰성/안정성을 보장하는 분산형 SCADA (Supervisory Control and Data Acquisition; SCADA는 일반적으로 각종 인프라, 산업시설, 설비의 각종 원격 감시, 제어 및 모니터링 (제조 공정, 에너지, 정수처리, 건물내 히터/에어콘 등) 시스템을 가리키지만, 여기서는 SG PQ를 원격 감시하는 PQM 시스템을 가리킨다.) PQM 시스템의 핵심기술 확보이다 ([그림 1] 참조).
