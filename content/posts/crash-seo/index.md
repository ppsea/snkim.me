---
title: "Crash Seo"
date: 2022-01-17T22:18:09+09:00
draft: false
tags: ["seo", "web", "tip"]
categories: ["etc"]
resources:
  - name: "featured-image"
    src: "seo.jpeg"
---

# SEO 박살내기

### 검색 알고리즘?

> 검색한 키워드의 맥락을 이해하고 적절한 웹 사이트 내 콘텐츠 페이지들을 노출하는것

### 검색 엔진 작동구조 5단계

1. 검색 엔진 크롤러 봇이 웹상에서 데이터 수집

2. 인덱서 프로그램 → 데이터를 검색엔진용으로 parsing

3. parsing된 데이터를 데이터베이스에 저장

4. 사용자 키워드 검색 → 형태소 분석

5. 내부 랭킹 알고리즘에 따라 인덱스 된 웹 페이지의 점수를 매겨 높은 순위별로 결과값 return

### SEO Flow

> 키워드 → 페이지 → 콘텐츠 → 링크 → 크롤 → 인덱스 → 순위 → 트래픽 → 전환

1. 키워드

   - 고객의 검색 니즈에 따른 키워드들이 제대로 페이지마다 녹아들었는가?

   - 경쟁사는 어떤 키워드를 사용하는가?

   - 가장 중요한 핵심은 ‘한 키워드 = 한 페이지’

2. 페이지

   - 중복 콘텐츠를 동시에 노출하지 않습니다.

   - 동일한 내용의 콘텐츠가 여러 개의 URL로 존재하게 하지 않습니다.

   - [잘 설명된 페이지](https://www.searchenginejournal.com/technical-seo/url-parameter-handling/#close)

3. 콘텐츠

   - 검색 니즈에 부합하는 양질의 콘텐츠가 있는가?

   - 가독성이 있고 흥미를 불러 일으킬만하고, 숙독의 여지가 있는가?

   - 특정 콘텐츠의 경우 쉽게 링크를 퍼갈 수 있는 장치가 마련되어 있는가?

4. 링크

   - 페이지와 양질의 콘텐츠만으로 검색 순위는 올라가지 않습니다. 자사 웹 사이트 페이지에 링크가 많이 첨부(추천)되고, 다른 웹 사이트에 노출되어야 점수가 평가됩니다.

   - 페이지 내 다른 페이지로 이동할 수 있는 링크가 확보되어 있는가?

   - 연관 페이지들이 서로 링크로 얽혀 있는가?

   - 외부 사이트 또는 SNS가 페이지를 추천하거나 소개하는 링크를 제공하는가?

   - 내부링크 노출을 위해 내비게이션이나 추천 영역을 마련하여 연관 페이지로 이동할 수 있게 링크를 달아주세요. (이전 글이나 추천 글을 소개하는 기능)

5. 크롤

   - 별로 중요하지 않은 페이지만 크롤되고 있진 않은가?

   - 반드시 크롤되어야 하는 페이지가 크롤되지 않는가?

     - 크롤링 봇이 바라보는 웹페이지 : [http://tools.seobook.com/general/spider-test/](http://tools.seobook.com/general/spider-test/)

   - 아무리 열심히 디자인하더라도 해당 이미지에 텍스트 정보인 alt값이 누락되었다면 크롤러는 이미지를 이해할 수 없게 됩니다. 크롤러가 읽어야 할 텍스트 정보가 부족하지 않은지, 오류가 없는지 살펴보며 설계해야 합니다.

   - 가독성을 고려한 타이틀 태그와 메타태그 삽입하기

   - Title

     - 한글 32자 미만, 영어 60자미만
     - 중복 title 방지

   - keywords. 검색 쿼리

     - 앞의 2개의 쿼리가 검색순위에 영향을 많이 끼침.
     - 비슷한 의미의 keyword의 나열은 좋지 않음.

   - 메타 description.

     - 영문 50 ~ 160자 (""사용금지)

   - 링크에 ‘<a> 태그(하이퍼링크를 걸어주는 태그)’나 이미지의 ‘alt 태그’ 같은 앵커 텍스트를 올바르게 누락 없이 기재하기

   - URL 구조를 올바르게 설계하여 웹사이트가 지니는 정보들을 크롤러가 모두 발견하게 만들기

   - 크롤러가 크롤링 작업을 수행할 때 HTTP 상태 응답 코드를 되돌려주기

6. 인덱스

   - 검색어와 부합하는 정보의 퀄리티가 중요

     - 키워드와 콘텐츠, 링크, 크롤러가 판단하는 타이틀 태그나 메타태그가 올바른지 등을 점검

   - 사이트맵 등록

   - 웹마스터 도구의 URL 검사 툴로 인덱싱 요청

   - 페이지 로딩 속도 올리기

   - 사이트 갱신 빈도 늘리기(자주 업데이트)

7. 순위

   - 유사 페이지가 많을 경우 크롤러가 어떤 것을 더 먼저 노출시켜줄지 점수를 매기기 어려움. ‘1페이지 1키워드’로 구성

   - 키워드, 랭킹 분석 [https://analytics.moz.com/](https://analytics.moz.com/pro/keyword-explorer/keyword/serp-analysis?locale=ko-KR&q=react%20%ED%94%84%EB%A1%A0%ED%8A%B8)

8. 트래픽

   - 검색엔진최적화는 ‘검색엔진에 최적화된 사이트’로 개선하는 것을 넘어, 우리의 목적에 맞게 트래픽이 유입되고 해당 트래픽 사용자가 전환(Conversion)까지 하는 것이 목표가 되어야 합니다.

   - 트래픽이 많은 페이지와 적은 페이지의 키워드를 분석하여 저조한 페이지의 키워드를 변환 시키는 전략 필요

9. 전환

   - 유입된 방문자가 고객으로 전환되도록 유도하기

### References

url parameter 다루기 : [https://www.searchenginejournal.com/technical-seo/url-parameter-handling/](https://www.searchenginejournal.com/technical-seo/url-parameter-handling/#close)

seo 기술적 가이드 : [https://ecommerce-platforms.com/articles/technical-seo-guide](https://ecommerce-platforms.com/articles/technical-seo-guide)

lighthouse 사이트 품질분석: [https://velog.io/@dell_mond/Lighthouse-사용법](https://velog.io/@dell_mond/Lighthouse-%EC%82%AC%EC%9A%A9%EB%B2%95)

크롤 봇이 보는 웹 페이지 HTML분석: [http://tools.seobook.com/general/spider-test/](http://tools.seobook.com/general/spider-test/)

Web-aria : [https://yongbeomkim.github.io/html/html-web-aria/](https://yongbeomkim.github.io/html/html-web-aria/)

SEO 분석 : [https://www.beusable.net/blog/?p=4138](https://www.beusable.net/blog/?p=4138)

키워드 분석 : [https://moz.com/blog/tactical-keyword-research-in-a-rankbrain-world](https://moz.com/blog/tactical-keyword-research-in-a-rankbrain-world)

json ld : [https://json-ld.org/playground/](https://json-ld.org/playground/)

리치 테스트: [https://search.google.com/test/rich-results?hl=ko&id=35MupjwzOraSokvqaZpUXg](https://search.google.com/test/rich-results?hl=ko&id=35MupjwzOraSokvqaZpUXg)
