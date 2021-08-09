![sadsadsda](https://user-images.githubusercontent.com/52379503/128649031-fc7b45db-cc3d-4264-b70a-1f0306f5c6c7.PNG)


# 1. 작품개요

 COVID-19 사태 이후, 집에서 직접 요리해먹는 ‘홈쿡 트렌드’가 확산됨에 따라 요리에 관심을 가지는 사람이 증가하게 되었다. 또한 이 때문에 집에 식품들을 사서 보관하는 사람들도 많이 늘게 되었고, 그로인해 보관되어있는 식품을 간편하게 관리할 수 있는 어플리케이션을 만든다면, 많은 소비자의 Needs를 충족할 수 있다고 생각하였다. 따라서 사용자가 보유하고 있는 식품을 관리하는데 도움을 주는 어플리케이션을 개발하여 제공하기로 하였다. 최근 증가한 ‘홈쿡커’를 비롯한 요리를 하는 사람들이 집 안의 식품을 좀 더 다양하고 효율적으로 사용할 수 있는 방법을 제공하는 것이 우리가 개발한 푸드 사이렌(FoodSiren)의 목적이다.
 
 
 # 2. 특징

- 상품 뒷면의 바코드를 읽어 관리 목록에 등록하는 상품 등록 기능
- 집 안의 있는 식품을 한 눈에 확인할 수 있는 상품 관리기능
- 상품의 남은 유통기한을 자동으로 체크하여 알려주는 알림 기능
- 식품을 이용하여 만들 수 있는 다양한 요리의 레시피 정보 제공


# 3. 주요 기술 소개

#3-1. 앱 시작
![1](https://user-images.githubusercontent.com/52379503/128649754-22dcb476-260b-419e-86c5-07e5d4c4257d.png)
-> 앱을 처음 실행할 경우 앱이 제공하는 핵심 기능에 대해 한 눈에 보여주는 인트로 제공

#3-2. 식품 등록
![2](https://user-images.githubusercontent.com/52379503/128649759-39971ff1-7c4f-49f1-8016-f61633aac612.png)
-> 바코드 스캔을 통한 식품 등록 시, 식품의 이름과 사진을 자동으로 등록

![3](https://user-images.githubusercontent.com/52379503/128649762-c7b501ce-f17d-47fa-823d-2448d3a7a436.png)
-> 신선식품 간편 등록 기능을 통한 식품 등록 시, 신선식품별로 유통기한을 추천

![4](https://user-images.githubusercontent.com/52379503/128649763-af726c9c-5ec8-4066-9b9a-53b892be25dd.png)
-> 추가하고자 하는 식품의 사진을 직접 촬영하여 등록 가능

![5](https://user-images.githubusercontent.com/52379503/128649764-6fb2f66c-6351-4712-a081-8b00d483facd.png)
-> 추가하고자 하는 식품의 보관 장소를 직접 추가할 수 있음

#3-3. 식품 관리
![6](https://user-images.githubusercontent.com/52379503/128649766-0eda8420-fe54-4eac-ba55-778fef92e76e.png)
-> 등록한 식품의 등록일과 유통기한을 바(Bar)의 형태로 한 눈에 확인할 수 있음
(빨강 : 유통기한이 지난 경우, 노랑 : 유통기한에 임박한 경우, 초록 : 유통기한이 많이 남은 경우)

![7](https://user-images.githubusercontent.com/52379503/128649769-a96efdd5-d39d-4e1a-8fc0-572db661f5d5.png)
-> 등록한 식품 중에 찾고자하는 식품을 검색할 수 있음

![8](https://user-images.githubusercontent.com/52379503/128649771-5cc9f3f5-b42b-4532-b467-48155416aa21.png)
-> 등록한 식품을 보관 장소별로 확인할 수 있음

![9](https://user-images.githubusercontent.com/52379503/128649773-864e096c-5136-4b80-8a6a-377bfbda9040.png)
-> 등록한 식품을 왼쪽으로 스와이프(Swipe)하면 수정, 삭제 기능을 제공하는 메뉴가 나타남

![10](https://user-images.githubusercontent.com/52379503/128649774-05b43e05-5990-4608-8ba5-fa11f4756cda.png)
-> 등록한 식품의 알람 버튼을 켜면, 해당 식품의 유통기한을 기준으로 7일 이전, 3일 이전, 당일, 3일 이후, 7일 이후에 푸시 알림 제공
(푸시알림 내용 : OO의 유통기한이 O일 남았어요!)

![11](https://user-images.githubusercontent.com/52379503/128649775-0c9d4fd2-d804-4bc9-af78-4780aacefedb.png)
-> 푸시 알림이 울리는 시간을 사용자가 직접 설정할 수 있게 하여 원하는 시간에 푸시 알림이 울리도록 설정할 수 있게 함

#3-4. 식품 Tip
![12](https://user-images.githubusercontent.com/52379503/128649779-3111fdeb-e3f4-436a-8204-f916c3d7e371.png)
-> 관리 중인 식품의 Tip 버튼을 누르면 해당 식품의 여러 가지 정보를 제공하는 Tip 화면으로 이동함

![13](https://user-images.githubusercontent.com/52379503/128649781-5f5e3593-35c1-4bff-99f3-f71926594023.png)
-> 해당 식품의 보관 방법, 배출 방법, 레시피 정보, 구매처 정보 버튼을 눌러 웹에서 해당 정보를 빠르게 검색할 수 있음

![14](https://user-images.githubusercontent.com/52379503/128649783-fbcf26a3-5d95-4ac1-b09b-477861491f16.png)
-> 레시피 정보에 있는 자취세끼 버튼(왼쪽에서 두 번째)을 누르면 캡스톤디자인 수요일반 4조(cook쿠루삥뽕)가 만든 자취세끼 앱과 데이터를 연동하여 사용자가 관리 중인 식품으로 만들 수 있는 레시피의 목록을 제공함

![15](https://user-images.githubusercontent.com/52379503/128649785-ca41acfe-517d-44be-b320-e9d830bae755.png)
-> 레시피 목록에서 특정 레시피를 클릭하면, 해당 레시피의 상세 정보(조리 방식, 재료, 조리 과정 등) 확인 가능

#3-5. 위젯
![16](https://user-images.githubusercontent.com/52379503/128649787-1236679a-6665-4642-8755-c163bdbc5df6.png)
-> 사용자가 앱에 접속하지 않아도 언제 어디서나 등록한 식품을 쉽게 확인할 수 있도록 위젯 기능을 제공

![17](https://user-images.githubusercontent.com/52379503/128649790-b8a5e921-6613-4742-b7ff-3b109124eb95.png)
-> 위젯의 앱 아이콘 클릭 시 식품 관리화면, Tip버튼 클릭 시 해당 식품의 Tip화면으로 곧바로 이동

#3-6. 유통기한이 지난 식품 빠른 삭제
![18](https://user-images.githubusercontent.com/52379503/128649794-256d6a5f-d88a-4643-a52c-69f7a903cdd0.png)
-> 사용자가 앱 실행 시, 해당 시점을 기준으로 유통기한이 지난 식품을 찾아서 삭제 여부를 물어봄으로써, 유통기한이 지난 식품을 빠르게 관리 목록에서 삭제할 수 있도록 도움.

-> 만일 사용자가 유통기한이 지난 식품을 아직 소비하지 않아 관리 목록에 남겨두고 싶을 경우 ‘아니오’ 버튼을 누르면 되고, ‘아니오’ 버튼을 눌렀을 경우 해당 식품에 대해서는 추후 앱 실행 시에 삭제 여부를 물어보지 않음
