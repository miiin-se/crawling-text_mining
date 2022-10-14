# crawling-text_mining

###### 서울대학교 빅데이터 혁신공유대학 Dr. 야마다 아키히코님 코드를 클론코딩하였습니다.

-----------------------------------------

2019년과 2022년, 3년 사이에 bts에 대한 관련 키워드와 사람들의 감성이 어떻게 변화하였을 지 알아보는 코드입니다.

-----------------------------------------
### 1. 2022년
 
> <img src="./crawling-textmining images/bts2022.jpg" alt="bts2022"></img><br/>
> 2022년 1월 1일 부터 업로드 날짜인 2022년 10월 15일까지 bts 단어를 검색하였습니다.

> <img src="./crawling-textmining images/df2022.jpg" alt="bts2022"></img><br/>
> 검색한 결과를 1000행 9열 배열으로 나타냅니다.

> <img src="./crawling-textmining images/bts content.jpg" alt="bts2022"></img><br/>
> 위 결과 중에는 내용(content)에 bts가 포함된 것이 아닌 사용자 아이디(username)에 bts가 포함된 것도 나왔기 때문에 내용(content)에만 bts또는 BTS가 나온 것만 걸러 줍니다.

> <img src="./crawling-textmining images/bts content result2022.jpg" alt="bts2022"></img><br/>
> 837행 9열 배열이 만들어 집니다.

> <img src="./crawling-textmining images/stopwords.jpg" alt="bts2022"></img><br/>
> 불요어(분석에 의미없는(필요없는) 단어)를 제거해 줍니다. 여기에선 rt(리트윗), bts, BTS를 불요어로 지정하였습니다. bts로 겁색하였기 때문에 bts(BTS)가 많이 나올 것이고, 이 bts(BTS)라는 단어는 분석에 필요없는 단어입니다.

> <img src="./crawling-textmining images/전처리2022.jpg" alt="bts2022"></img><br/>
> 불요어와 특변한 의미가 없는 단어를 없앤 전처리 결과입니다.
 
> <img src="./crawling-textmining images/word cloud2022.png" alt="bts2022"></img><br/>
> word cloud로 나타낸 결과입니다. 빈도 수가 많을 수록 단어가 크게 보입니다. Pop, Duo, Group, Favorite이 관련 키워드로 많이 검색된 걸 알 수 있습니다.

> <img src="./crawling-textmining images/감정분석 시각화2022.png" alt="bts2022"></img><br/>
> 감성분석을 시각화한 것 입니다. 부정적(negative)보다 긍정적(positive) 반응이 더 많다는 것을 확인할 수 있습니다.

> <img src="./crawling-textmining images/Topic Analysis2022.jpg" alt="bts2022"></img><br/>
> 주제에 따라 10가지로 분류한 결과입니다.

### 2. 2019년
> <img src="./crawling-textmining images/bts2019.jpg" alt="bts2022"></img><br/>
> <img src="./crawling-textmining images/df2019.jpg" alt="bts2022"></img><br/>
> <img src="./crawling-textmining images/bts content result2019.jpg" alt="bts2022"></img><br/>
> <img src="./crawling-textmining images/전처리2019.jpg" alt="bts2022"></img><br/>
> <img src="./crawling-textmining images/word cloud2019.png" alt="bts2022"></img><br/>
> <img src="./crawling-textmining images/감정분석 시각화2019.png" alt="bts2022"></img><br/>
> <img src="./crawling-textmining images/Topic Analysis2019.jpg" alt="bts2022"></img><br/>
