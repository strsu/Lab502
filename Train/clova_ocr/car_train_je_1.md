# CLOVA OCR 기반 한글데이터 훈련

> ## 환경
 |Option|Train_Select|
 |:---|:---|
 |Transformation|TPS|
 |FeatureExtraction|VGG|
 |SequenceModeling|BiLSTM|
 |Prediction|CTC|
 |imgH|100|
 |imgW|100|
 |charachter|가나다라마바사아자차카타파하거너더러머버서어저고노도로모보소오조구누두루무부수우주배허호외교영준국기협정대표울종중용산성동광진문랑북강봉원은평포양천금등작관악초남송래해운연제상장달인미추홀계화옹전유덕세경안명택과시흥군의왕이김여리춘릉태백속삼척홍횡월창선철충청옥증괴음단공령논룡당예익읍완임실순목담곡례암함신항위칠통밀녕합귀0123456789|
 
> ## 훈련 결과

 총 110개의 이미지를 대상으로 테스트

 ### * 테스트 이미지 샘플
 <img src = "https://user-images.githubusercontent.com/80444851/110818080-4a857200-82d0-11eb-8893-9149a8e570d3.jpg" width="400px">
 
 ### * 틀린 결과 이미지
 110개중 14개 이미지 오답
 
 <img src = "https://user-images.githubusercontent.com/80444851/110820084-1e6af080-82d2-11eb-9080-c0d5d063ea86.png" width="400px" align="left">
 
 <img src = "https://user-images.githubusercontent.com/80444851/110820132-2b87df80-82d2-11eb-8c77-63effef5a805.png" width="400px">
