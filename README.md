# 개인 맞춤형 부동산 추천 서비스 #

### 한성대학교 컴퓨터 공학부 2021년도 캡스톤디자인 12조 살고싶다

1. **프로젝트 정의** 

   공공데이터를 활용한 사용자 맞춤형 부동산 서비스

2. **프로젝트 목표**

   웹 서비스 

   - 공공 데이터 수집을 기반으로 Spring 프레임워크를 이용한 웹 서비스를 구현 

   부동산 추천 

   - 네이버 맵 API에 사용자가 직접 설정한 중요시설(생활 인프라)옵션 별로 가중치를 주는 알고리즘으로, 본인이 설정한 옵션에 더 적합한 매물을 점수로 환산하여 추천해주는 방식 • 20~30대 1인가구를 주 타겟층으로 원룸 중심의 부동산 추천 서비스

3. **프로젝트 설명**

   - 기존 부동산에서 사용자가 매물을 탐색하고자 할 때 제공하는 기본 필터(거래 유형, 매물 유형,  가격 정보 등) 설정과는 별개로 사용자가 자신의 주거지 근처에 있으면 하는 인프라나 치안 등의 환경 요소를 선택할 수 있도록 한다. 사용자에 의해 선택된 각 요소들은 기본 필터 설정과 함께 사용자에게 더 적합한 매물을 추천해주는 근거가 되며, 해당하는 요소들과 거리상으로 가까운 관계가 있는 매물들이 지도에 표시된다. 이렇게 표시된 매물 중 사용자가 선택한 옵션의 가장 많은 요소들과 관계가 있는 매물에 가장 높은 점수가 부여되고 점수대 별로 매물을 추천하는 기능을 지도 API 상에 구현한다. 사용자가 선택한 옵션들 중에서 더 필요하다고 느끼는 옵션에 대해 중요도를 선택하게 하고, 해당 옵션에 가중치를 부여해 점수를 나타냄으로써 각 사용자에게 더 적합한 개인형 맞춤 부동산 서비스를 제공한다

4. **프로젝트 구조**

![image-20210611210613249](https://user-images.githubusercontent.com/71720930/121789363-5145bd00-cc10-11eb-8858-171b8eef688e.png)
   

5. **사용예**

![image-20210611210840670](https://user-images.githubusercontent.com/71720930/121789364-530f8080-cc10-11eb-8730-79ec2a0ed4cb.png)
![image-20210611210856262](https://user-images.githubusercontent.com/71720930/121789367-5440ad80-cc10-11eb-8e5b-7f3035d734e6.png)
![image-20210611210908674](https://user-images.githubusercontent.com/71720930/121789368-5571da80-cc10-11eb-81bc-56cbc9cddaf2.png)
![image-20210611210922923](https://user-images.githubusercontent.com/71720930/121789370-56a30780-cc10-11eb-8fab-d45cbc935e50.png)
![image-20210611211004748](https://user-images.githubusercontent.com/71720930/121789373-57d43480-cc10-11eb-84f4-cf8c53900989.png)

6. **동영상 프레젠테이션**

[![프레젠테이션](https://img.youtube.com/vi/f3Ml7c4RU4E/0.jpg)](https://youtu.be/f3Ml7c4RU4E)
