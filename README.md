# crawling-text_mining

###### 서울대학교 빅데이터 혁신공유대학 Dr. 야마다 아키히코님 코드를 클론코딩하였습니다.

-----------------------------------------

2019년과 2022년, 3년 사이에 bts에 대한 관련 키워드와 사람들의 반응이 어떻게 변화 하였을지 알아보는 코드입니다.

-----------------------------------------
### 1. 2022년
 
> <img src="./crawling-textmining images/bts2022.jpg" alt="bts2022"></img><br/>
> 2022년 1월 1일 부터 업로드 날짜인 2022년 10월 15일까지 bts 단어를 검색하였습니다.

> <img src="./crawling-textmining images/df2022.jpg" alt="df2022"></img><br/>
> 검색한 결과를 1000행 9열 배열으로 나타냅니다.

> <img src="./crawling-textmining images/bts content.jpg" alt="bts content"></img><br/>
> 위 결과 중에는 내용(content)에 bts가 포함된 것이 아닌 사용자 아이디(username)에 bts가 포함된 것도 나왔기 때문에 내용(content)에만 bts또는 BTS가 나온 것만 걸러줍니다.

> <img src="./crawling-textmining images/bts content result2022.jpg" alt="bts content result2022"></img><br/>
> 837행 9열 배열이 만들어 집니다.

> <img src="./crawling-textmining images/stopwords.jpg" alt="stopwords"></img><br/>
> 불요어(분석에 의미없는(필요없는) 단어)를 제거해 줍니다. 여기에선 rt(리트윗), bts, BTS를 불요어로 지정하였습니다. bts로 검색하였기 때문에 bts(BTS)가 많이 나올 것이고, 이 bts(BTS)라는 단어는 분석에 필요없는 단어입니다.

> <img src="./crawling-textmining images/전처리2022.jpg" alt="전처리2022"></img><br/>
> 불요어와 특별한 의미가 없는 단어를 없앤 전처리 결과입니다.
 
> <img src="./crawling-textmining images/word cloud2022.png" alt="word cloud2022"></img><br/>
> word cloud로 나타낸 결과입니다. 빈도 수가 많을 수록 단어가 크게 보입니다. Pop, Duo, Group, Favorite이 관련 키워드로 많이 검색된 걸 알 수 있습니다.

> <img src="./crawling-textmining images/감정분석 시각화2022.png" alt="감정분석 시각화2022"></img><br/>
> 감성분석을 시각화한 것 입니다. 부정적(negative)보다 긍정적(positive) 반응이 더 많다는 것을 확인할 수 있습니다.

> <img src="./crawling-textmining images/Topic Analysis2022.jpg" alt="Topic Analysis2022"></img><br/>
> 주제에 따라 10가지로 분류한 결과입니다. 크게 AMAs, 곧 열리는 부산 콘서트, 앨범, favorite 으로 나뉩니다.

### 2. 2019년
> <img src="./crawling-textmining images/bts2019.jpg" alt="bts2019"></img><br/>
> 2019년 1월 1일 부터 2019년 12월 31일까지 bts 단어를 검색하였습니다.

> <img src="./crawling-textmining images/df2019.jpg" alt="df2019"></img><br/>
> 검색한 결과를 1000행 9열 배열으로 나타냅니다.

> <img src="./crawling-textmining images/bts content result2019.jpg" alt="bts content result2019"></img><br/>
> 앞과 같이 내용(content)에 나온 것만 걸러 944행 9열 배열이 만들어 집니다.

> <img src="./crawling-textmining images/전처리2019.jpg" alt="전처리2019"></img><br/>
> 불요어와 특별한 의미가 없는 단어를 없앤 전처리 결과입니다.

> <img src="./crawling-textmining images/word cloud2019.png" alt="word cloud2019"></img><br/>
> word cloud로 나타낸 결과입니다. ARMY, yes, JIMIN이 관련 키워드로 많이 검색된 걸 알 수 있습니다.

> <img src="./crawling-textmining images/감정분석 시각화2019.png" alt="감정분석 시각화2019"></img><br/>
> 감성분석을 시각화한 것 입니다. 긍정적(positive)보다 부정적(negative) 반응이 더 많다는 것을 확인할 수 있습니다.

> <img src="./crawling-textmining images/Topic Analysis2019.jpg" alt="Topic Analysis2019"></img><br/>
> 주제에 따라 10가지로 분류한 결과입니다. 크게 멤버별로 주제가 나뉩니다.

----------------------------------
## 결론
1. 현재년도인 2022년과 3년 전인 2019년을 비교해 보았을 때 키워드는 물론, 사람들의 bts 관련 단어 사용이 부정적에서 긍정적으로 변화하였습니다. 
2. 사용자이름(username)에 bts가 들어간 사람이 2019년 보다 2022년에 늘어났다는 것을 행의 수가 줄어든 것으로 알 수 있습니다.
3. 주제분석 부분에서 2019년에 비해 2022년에 영어비율이 더 많아진 것으로 보아 외국에서 2019년보다 더 유명해진 것을 알 수 있습니다.
