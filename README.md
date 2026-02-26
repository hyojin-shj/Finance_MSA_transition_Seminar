# 📌 금융 IT 관점에서의 MSA 아키텍처 설계와 운영 전략

- 우리FISA 1차 기술세미나  
- 팀: 돈지켜조
| <img width="200" height="170" src="https://avatars.githubusercontent.com/u/181453012?v=4" /> | <img width="200" height="170" src="https://avatars.githubusercontent.com/u/123048615?v=4" /> | <img width="200" height="170" src="https://avatars.githubusercontent.com/u/114569746?v=4" /> | <img width="200" height="170" src="https://avatars.githubusercontent.com/u/199601496?v=4" /> |
|:---:|:---:|:---:|:---:|
| **우민하** | **김동환** | **최예원** | **심효진** |
| • **MSA 개요 정리** <br> • **모놀리식 vs MSA 비교 분석** <br> • 아키텍처 구조 기초 설계 | • **MSA 도입 유의사항 분석** <br> • 실패 사례 연구 <br> • 리스크 요인 정리 | • **금융권 MSA 도입 사례 분석** <br> • 코어뱅킹 아키텍처 구조 연구 <br> • 정합성 전략 조사 | • **우리은행 관점 MSA 파일럿 전략 제안** <br> • 통신(MVNO) MSA 설계 <br> • 점진적 확산 전략 수립 |
- 주제: 금융권 MSA 도입 전략 및 우리은행 적용 제안

  

<img width="1920" height="1080" alt="30" src="https://github.com/user-attachments/assets/e8e68b77-1831-4b71-a44c-ab679589feca" />

<img width="1920" height="1080" alt="32" src="https://github.com/user-attachments/assets/96a56eb1-16f1-4f74-aaf7-40a750592724" />

<img width="1920" height="1080" alt="33" src="https://github.com/user-attachments/assets/5d2152b2-da64-4f55-9c07-5fa4cb44d989" />



## 💡 Why


본 세미나는 단순히 MSA 개념을 설명하는 것이 아니라,  
**금융권 환경에서 MSA를 어떻게 현실적으로 도입할 것인가**에 대한 전략적 접근을 목표로 하였음.

- 강한 ACID 정합성
- 초저지연 OLTP 환경
- 대규모 레거시 시스템
- 절대 장애가 허용되지 않는 구조

> 금융권에서 MSA는 “가능한가?”가 아니라  “어떻게 도입해야 안전한가?”

---

## 🔍 What We Did

- 전통적 코어뱅킹 아키텍처 분석
- 국내 MSA 전환 사례(토스뱅크) 구조 연구
- 분산 트랜잭션 / 정합성 전략 분석
- 분산 모놀리식 위험 검토
- 우리은행 환경에 맞는 도입 시나리오 설계

---

## 🎯 Our Conclusion

코어를 한 번에 바꾸는 것은 현실적이지 않음.

제안사항: 채널계 파일럿 → 검증 체계 확보 → 점진적 확산
파일럿 대상으로 통신(MVNO) 모바일 사업을 선정.

고려사항: 정합성 리스크 및 계정계 결합도

---

## 📌 Feedback

- 
- 조직·운영·관제 역량이 함께 성숙해야 가능

[우리FISA - 돈지켜줘 금융MSA도입전략.pdf](https://github.com/user-attachments/files/25566990/FISA.-.MSA.pdf)
