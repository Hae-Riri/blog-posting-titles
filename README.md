# blog-posting-titles
정리할 예정인 주제들.. 아주 늦더라도 언젠가  하려고 일단 여기 적어둠.


날짜 관해서 모던자바랑 같이 연계해서 쓰거나,
배치 관련해서 여쭙거나,
nginx conf 파일 제대로 파헤치기

DDD 다시 하기. aggregate 모델 다시 보기. 추천해주신 책과 함께.

<br> <br>

<img width="741" alt="image" src="https://user-images.githubusercontent.com/35680213/177558753-70fdeed9-8879-4bed-9b31-6b5e80ffabdb.png">
<img width="485" alt="image" src="https://user-images.githubusercontent.com/35680213/177562109-3112da87-a0cc-49a4-833c-6ce3dd81d183.png">
<img width="498" alt="image" src="https://user-images.githubusercontent.com/35680213/177562150-b1727db4-c54e-4c2f-a297-e3c3763a9cdd.png">
<img width="724" alt="image" src="https://user-images.githubusercontent.com/35680213/177562811-7e211d5c-6842-4a3e-a1d4-bd725bda3ed6.png">
<img width="540" alt="image" src="https://user-images.githubusercontent.com/35680213/177563987-afbc68f1-a02a-4010-b511-3965777f4c8c.png">
<img width="493" alt="image" src="https://user-images.githubusercontent.com/35680213/177564104-a3154a70-9d76-4de0-880d-34e679d83117.png">




log.info("value= {}", value);
log.info("value=" + value);

- nginx 원리, 팀 프론트플젝 nginx 사용 이해하기

- netty, kqueue 등 webclient의 동작 이해 잘하기. reactor 와 flatMap, map,
- concurrentHashMap, hashMap 등둥...

- 나아아아중에 spring batch  듣다 만거 다시 듣기
- rxjava도 듣다 만 거 많잖아... 듣기....


- 왜 코드 마지막 줄에 한칸이 더 
- Did not observe any item or terminal signal within 10000ms in 'flatMap' (and no fallback has been configured) flatMap 다시 알아봐...

- webMVC랑 import 활용해서 내가 원하는 빈만 주입하여 테스트하기. controller 말고, scheduler일 때 테스트하고 싶은 경우!

<br>
- [ ] subList의 위험성
  - 내가 해둔 관련 필기 : https://selective-bathtub-e65.notion.site/11-0b30059fd00a4ea88215d736417c0710

- [ ] JPA 연장
  - 댓글로 말씀하신 상황 원인 공부하기 : https://eocoding.tistory.com/74?category=941319

- [ ] 왜 생성자 주입을 권장하나

- [ ] Reactor 연장
  - Netty 이벤트 루프에 대해
  - webclient 비동기답게 활용하기
    - 스트림의 원리. forEach랑 그냥 for문이랑 어떻게 다르길래 forEach만 비동기가 먹혔을까? https://wiki.11stcorp.com/pages/viewpage.action?pageId=450633380
    - flatMap, Map 차이, flatMap 위치 차이 https://wiki.11stcorp.com/pages/viewpage.action?pageId=451610916 / concatMap 등등...
    - concurrentMap, HashMap 비동기 여부 / collectMap

- [ ] 왜 ServiceImpl을 요새는 안 쓸까? 쓰는 코드는 또 왜 쓰고 있나? / 
- AOP + JDK Dynamic Proxy와 CGLIB 참고 https://steady-coding.tistory.com/608
- https://www.popit.kr/spring-oop-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D-%EC%98%88%EC%A0%9C1-service-serviceimpl-%EA%B5%AC%EC%A1%B0%EC%97%90-%EB%8C%80%ED%95%9C-%EA%B3%A0%EC%B0%B0/

- GraphQL : https://tech.kakao.com/2019/08/01/graphql-basic/
- [ ] graphql은 어떻게 overFetching과 underFetching을 해결했을까? 서버가 만지는 데이터는 그대로인데 클라이언트가 서버랑 주고받는 데이터를 원하는 것만 만지게 할 수 있다는 건지? 만약 그런거라면 그게 왜 이점이고 어떤 이점을 갖는 건지?
- [ ] queryResolver안에 아무 메소드도 없던데 이거 왜 구현하는지 알아봐야 함...


### 보류
- [ ] save와 saveAll의 차이는...뭐... 이거는 안해도 될 것 같다.
