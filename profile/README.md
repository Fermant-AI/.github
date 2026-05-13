# 🥬 Ferment-AI — 수출김치 숙성도 모니터링 시스템
**Ferment-AI**는 K-푸드 수출 기업을 위한 실시간 발효 예측 앱입니다. <br/>
수출 유통 전 과정에서 김치 숙성도를 시각화·예측하여, 공장 사장님께 보이지 않던 리스크를 데이터로 돌려드립니다.

🏆 **Red Bull Basement 2026 한국 국내 결선 진출(Top-8)**

<img width="1200" height="600" alt="image" src="https://github.com/user-attachments/assets/8147ccf5-c7d6-4c32-ac0e-994a5d2d3ba9" />

---

## 🌏 프로토타입 바로가기

👉 [**앱 체험하기 →**](https://kimchi-ripeness-monitor--wingter.replit.app/)

---

## 🧠 문제 정의

김치는 살아있는 식품입니다. 배 위에서도, 창고에서도 발효는 멈추지 않습니다.

한 달이 넘는 국제 유통 과정에서 예측 불가능한 과숙성이 발생하고, 지금까지는 이를 실시간으로 확인할 방법이 없었습니다.

- 김치의 **37%**가 소비자 기대 이하의 맛으로 도착
- 냉장 컨테이너를 5°C로 설정해도, 깊숙이 적재된 김치엔 냉기가 늦게 도달 → **위치별 숙성 편차** 발생
- 공장 문을 나서는 순간, 아무도 볼 수 없는 **블랙박스** 구간 시작
- 결과: 품질 불균일, 리콜 비용, 브랜드 신뢰 하락, 식품 폐기

---

## 💡 솔루션

Ferment-AI는 유통 블랙박스를 데이터로 시각화하여 사장님께 **결정권**을 돌려드립니다.

### 주요 기능 (프로토타입)

| 기능 | 설명 |
|---|---|
| 📊 **출하 현황 대시보드** | 현재 출하 중인 모든 컨테이너의 숙성 상태를 한눈에 |
| 📦 **컨테이너별 숙성 그래프** | 운송 단계마다 숙성도가 어떻게 변해가는지 시각화 |
| 📈 **숙성도(pH) 예측 엔진** | 적재 위치·온도·밀도·기간 등 변수 조합으로 pH 예측 |
| 🔁 **발효 피드백** | 어느 구간에서 숙성이 급증했는지 파악 → 물류 경로·출하 시점 최적화 |
| 👁️ **품질 시각화** | 감(感) 대신 객관적 수치로 내 김치가 어떤 상태로 도착했는지 확인 |

### 예측 로직

1. **제조 변수**: 배추 염도, 양념 비율, 재료 구성
2. **운송 변수**: 컨테이너 온도, 김치 품온(적재 위치별), 운송 기간, 보관 환경
3. **AI 보정 레이어**: 이론 공식이 놓치는 현장의 미세한 오차를 AI가 학습하여 최종 숙성도 보정

> 핵심 인사이트: 5°C로 설정된 컨테이너가 모든 김치에 5°C를 전달하지 않습니다. 위치가 다르면 숙성이 다릅니다. 저희는 그것을 모델링합니다.

---

## 🗺️ 비즈니스 모델 & 임팩트

- **SaaS**: 수출 기업 대상 선적별 숙성 모니터링 구독 서비스
- **다이나믹 유통 전략**: 과숙성이 예측된 김치를 폐기 대신 찌개용·요리용으로 리다이렉트 → **폐기물을 수익으로**
- **미래 확장**: 소비자 선호 숙성도 매칭 서비스 ("나는 잘 익은 김치가 좋아")
- 연간 신선식품 폐기율 **14%** 감축에 기여
- 고가 장비 없이 **71%의 영세 기업**도 품질 일관성 확보 가능

---

## 🏆 대회 여정

### Red Bull Basement 2026 · 한국

| 단계 | 형식 | 내용 |
|---|---|---|
| 1차 예선 | 1분 피치 | "블랙박스" 문제와 실시간 숙성 예측 솔루션 소개 |
| **국내 결선** | 2분 피치 + 데모 갤러리 | 작동하는 프로토타입 시연, 발효 시각화 및 비즈니스 모델 발표 |

📸 [**레드불 공식 인스타그램 게시물 (2026 Redbull Basement Korea 결선 발표현장) →**](https://www.instagram.com/p/DYOdzePjxm2/?igsh=dTVkYzZ5eWh4OWFl)

<details>
<summary>📝 1차 예선 피치 스크립트 보기</summary>

> Hi, Live from Kimchi Town!!! I'm Yoojin and studying food science. I'm Arim and studying Computer Science.
>
> My Food Science professor has a problem in Kimchi export. Why? Kimchi is fermented. So it's sensitive to environment. During long export journey, fermentation accelerates out of control, causing over-ripening and costly recalls.
>
> It's a huge market pain. 37% of consumers complain about inconsistent ripeness.
>
> We will solve it with Ferment-AI. We predict ripeness in real-time during transit. 'Grade A' stays premium, while 'Grade B' is redirected for cooking use like stews. Our Dynamic Distribution System turns waste into profit.
>
> By reducing the 14% global food waste, we deliver the true premium K-Food. **Let's redefine fermentation!**

</details>

<details>
<summary>📝 국내 결선 2분 피치 스크립트 보기</summary>

> 유진: 안녕하세요, 발효 과학과 데이터로 K-푸드의 신뢰를 설계하는 팀 Ferment-AI입니다. 여러분, 분명 맛있는 김치를 샀는데, 정작 먹으려니 너무 시어서 실망했던 기억, 있으신가요? 실제로 한 설문조사에 따르면, 김치의 37%는 소비자에게 '기대한 맛'으로 도착하지 못합니다.
>
> 아림: 저희가 찾아간 김치 공장 사장님이 말씀하셨습니다. "내 김치는 최고인데, 배 타고 나가면 어떻게 변할지 모르는게 불안해." 김치는 배 위에서도, 창고에서도 발효가 멈추지 않죠. 그런데 지금까지 유통 중 발효 속도를 실시간으로 볼 수 있는 방법은 없었습니다. 정성껏 만든 김치가 공장 문을 나서는 순간, 아무도 볼 수 없는 블랙박스에 갇히는 겁니다.
> 유진: 그래서 저희는 이 블랙박스 구간을 시각화하여, 유통손실리스크를 실시간 숙성도 예측으로 해결하려 합니다.
>
> 아림: 첫째, '발효 피드백'입니다. 어느 구간에서 숙성이 급증했는지 정확히 짚어주어, 물류 경로를 개선하고 출하 시점을 최적화할 수 있습니다.
>
> 유진: 둘째, '품질의 시각화'입니다. 막연한 추측 대신 객관적인 수치로 품질을 확인하여 개선점과 확신을 얻을 수 있습니다.
> 아림: 나아가 소비자 선호도에 맞는 숙성도를 매칭해주는 '맞춤형 판매전략'으로 확장할 수 있습니다. 과숙성이 예측된 김치는 더이상 폐기하지 않고 수익으로 바꿉니다.
>
> 유진: 매년 버려지는 신선식품 폐기율 14%를 낮추고, 약 71%의 영세 기업들이 고가의 장비 없이 전세계 어디서든 품질일관성을 갖추게 할 혁신적인 비즈니스 인프라입니다.
> 아림: 데이터로 발효의 미래를 읽고, 사장님의 자부심이 전 세계 식탁에 배달되도록 하겠습니다.
>
> 함께: **Let's redefine fermentation!**

</details>

---

## 👩‍🔬 팀

<table align="center">
 <tr align="center">
     <td><B>장유진<B></td>
     <td><B>이아림<B></td>
 </tr>
 <tr align="center">
     <td>
         <a href="https://github.com/arieum">
         <img src="https://github.com/arieum.png" style="width: 100px">
         </a>
         <br>
         <a href="https://github.com/arieum"><B>프로덕트 / 식품공학</B></a>
     </td>
     <td>
         <a href="https://github.com/Winterrr-24">
         <img src="https://github.com/Winterrr-24.png" style="width: 100px">
         </a>
         <br>
         <a href="https://github.com/Winterrr-24"><B>개발 / 컴퓨터공학</B></a>
     </td>
 </tr>
</table>



---

## 🚀 로드맵

- [ ] 김치 수출 기업 1~2곳과 파일럿 데이터 수집 파트너십
- [ ] 컨테이너 내 IoT 온도 센서 연동
- [ ] 실제 발효 궤적 데이터로 ML 모델 학습
- [ ] 중소 김치 수출 기업 대상 B2B SaaS MVP 출시
- [ ] 된장·고추장·막걸리 등 K-푸드 전반으로 확장

---

## 📬 연락처

협업, 투자, 또는 그냥 김치 과학 얘기가 하고 싶다면 GitHub Issues로 연락주세요.

---

> *"Let's redefine fermentation."* 🌶️
