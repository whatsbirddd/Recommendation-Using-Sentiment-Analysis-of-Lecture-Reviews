# Recommendation Using Sentiment Analysis of Lecture Reviews 
📚 **프로젝트 진행기간** : 2021.03 ~ 2021.06


📚 **프로젝트 기획 이유**
수십개의 강의평가를 하나씩 읽어보면서 매번 불편함을 느꼈다. 내가 듣고싶은 강의에 대한 리뷰가 한눈에 볼 수 있게 제공을 해주면 얼마나 편할까라는 생각을 하던중 텍스트 분석에 관심도 있어 팀프로젝트를 진행하게 되었다. ABSA를 구현하는 데에 시간이 많이 부족했지만 시도해본 것에 의의를 두고 다음 프로젝트때에는 데이터 부족과 라벨링에 대해서 좀 더 고민을 하고 더 다양한 도전을 해보기로 했다


📚 **프로젝트 과정**


**1. Web data crawling**

**2. Data Pre-processing**

  I tried
  - pykospacing
  - compare performance : mecab,khaiii > kkma, hannanum, okt
  - soynlp
 
**3. Frequency based text analysis**

**4. Text similarity**

  - cosine ✅
  - euclidean
  - manhattan
  - zaccard
  
  euclidean, manhattan, zaccard ,,, performance is not so good,,,
  
**5. ABSA(Aspect Based Sentiment Analysis)**

  1. General Aspects : professor, exam, lecture, homework, gpa
  2. Sentiment Analysis
  
  I tried...
  
  - self-training(pseudo-label)
  - bi-LSTM
  - LSTM

📚 **프로젝트 과정 기록**
📃아래의 노션페이지를 활용해서 팀프로젝트를 진행했습니다📃

https://www.notion.so/_-7df58021f7fb4741be7f5ed9637c6c0a
 
