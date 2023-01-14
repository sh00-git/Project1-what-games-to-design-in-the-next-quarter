## Project1 : 다음 분기에 어떤 게임을 설계할까
- 개발기간
    - 2022.06.22 ~ 2022.06.27
- 사용 언어 및 라이브러리
    - `python`, `pandas`, `matplot`, `seaborn`

## 💡 Topic

- 데이터 분석과 인사이트 도출 연습을 위한 프로젝트
- AI 부트캠프 Section1 Project

## ❓ 문제정의

게임 데이터를 통해 지역별 선호하는 게임 장르와 연도별 게임 트랜드, 출고량이 높은 게임을 파악하기 위한 데이터 분석 프로젝트이다.

## 🔍 프로젝트 진행과정

데이터 확인 → 데이터 분석 → 인사이트 도출

## 📚 데이터 셋

- 게임 이름, 플랫폼, 연도, 장르, 제작사, 북미, 유럽, 일본, 기타 지역에서의 출고량을 나타내는 9개의 columns와 16598개의 row로 구성
- 출고량은 백만단위로 되어 있음.

## ✍🏻 프로젝트 수행 과정 및 결과

1. 지역에 따라서 선호하는 게임 장르가 다를까?
    
    → 장르별로 각 나라의 출고량의 합을 보면 북미, 유럽, 기타 지역은 Action이 높고 일본지역은 Rold-Playing이 높은 것을 볼 수 있다.
    

<img src="https://user-images.githubusercontent.com/76083173/212464605-1cd1aac7-28a2-426e-9f4c-7cf41537f5fb.png" height="400"/>

<img src="https://user-images.githubusercontent.com/76083173/212464915-ae33be48-bd25-473b-b813-eabd086590d7.png" height="400"/>

2. 연도별 게임의 트렌드가 있을까?

→ 2003년부터 2016년까지는 Action장르가 트렌드였다고 볼 수 있고, 1996년부터 2002년에는 Sports장르가 트렌드였던 것으로 보인다.

<img src="https://user-images.githubusercontent.com/76083173/212464988-aae3d6cd-b355-4ed2-9806-0ca2b094ba14.png" height="400"/>

3. 출고량이 높은 게임에 대한 분석
- 출고량 Top 100 플랫폼
<img src="https://user-images.githubusercontent.com/76083173/212465070-d986ddd1-4bea-4242-87f8-19fa97c810ed.png" height="400"/>


- 출고량 Top 100 장르
<img src="https://user-images.githubusercontent.com/76083173/212465127-fa46255c-f9f2-4b5e-be0d-844e1fea6261.png" height="400"/>

- 출고량 Top 100 제작회사
    - 플레이스테이션 플랫폼의 출고량이 상위에 있음을 알 수 있고, Action 장르, 제작회사는 Nintendo가 출고량이 가장 높은 것을 확인할 수 있다.
<img src="https://user-images.githubusercontent.com/76083173/212465155-1b2e8fd9-8460-4a56-a209-51fea791b626.png" height="540"/>



**다음 분기에 어떤 게임을 설계해야 할까?**

Genre: Action

- 일본 지역을 제외한 북미, 유럽, 기타 지역에서 Acition 장르를 선호.
- 2000년대 이후 Acition 장르의 인기가 높아지고 있음.
- 출고량이 높은 데이터를 보아도 Action이 가장 많은 것을 알 수 있음.

Platform: PS 시리즈

- 출고량이 높은 데이터를 보았을 때 Platform에서 PS 시리즈가 가장 많은 판매량을 기록.

## ✨ Learned

- 데이터 `EDA` 및 `전처리` 과정을 연습해 볼 수 있었음.
- Matplot과 seaborn으로 데이터를 `시각화`하여 분석하는 과정을 연습해 볼 수 있었음.
- 데이터를 분석하여 `인사이트`를 도출하는 과정을 경험해 볼 수 있었음.
