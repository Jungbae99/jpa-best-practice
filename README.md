### 🧭 방향
- 목표 : 그룹 스터디 진행을 효과적으로 관리하기 위해 저장소를 운영한다.

---

### ⌚ 매주 월요일 저녁 10시
- 장소 : 디스코드

---

### 🤔 방식
- 1️⃣ jpa-best-practice 프로젝트를 자신의 계정으로 fork합니다.
- 2️⃣ fork한 repository를 개인 컴퓨터에 clone합니다.
- 3️⃣ 매 주 목표의 독서량을 읽고 정리하여 코드 저장(commit) & 개인 원격 저장소 저장(push)를 합니다.
- 4️⃣ github에서 PR(pull request)를 작성합니다.
    + PR 출발지는 fork한 자신의 저장소의 3️⃣번에서 생성한 branch로 합니다.
    + ex) jpa-best-practice:master <- jpa-best-practice:origin/master
- 5️⃣ 커밋 메시지를 작성합니다. PR 규칙 및 Commet Message 규칙 참고
- 6️⃣ PR들을 merge합니다.
- 7️⃣ **학습하면서 본 코드가 왜 좋은지 이유를 중점적으로 정리하여 공유합니다.**
- 8️⃣ 이후, 공용 폴더에 장.별로 구분하여 동일한 방식(1-6)으로 코드를 관리하며 스터디를 완료합니다.

---

### 📦 패키지 구성 가이드
```
1주차(항목1~5)
ㄴ 우연.md
ㄴ 현우.md
```

---

### 🤙🏻 PR 규칙 및 Commit Message 규칙
- Pull Request (공용 저장소)
    + 이름 장 제목
    + ex) docs: 우연 1장 항목 1~3 완료

- Commit Message (개인 저장소)
    + 자유

---

### 🚀 예제 코드
- [에이콘 출판사꺼 아님](https://github.com/switchover/spring-boot-persistence)

---

### ✅ 목차
1장. 연관관계
- 항목 1: @OneToMany 연관관계를 효과적으로 구성하는 방법
- 항목 2: 단방향 @OneToMany 연관관계를 피해야 하는 이유
- 항목 3: 단방향 @ManyToOne의 효율성
- 항목 4: @ManyToMany 연관관계를 효과적으로 구성하는 방법
- 항목 5: @ManyToMany에서 Set이 List보다 나은 이유
- 항목 6: CascadeType.REMOVE 및 orphanRemoval=true를 사용해 하위 엔터티 제거를 피해야 하는 이유와 시기
- 항목 7: JPA 엔터티 그래프를 통해 연관관계를 가져오는 방법
- 항목 8: JPA 엔터티 서브그래프를 통해 연관관계를 가져오는 방법
- 항목 9: 엔터티 그래프 및 기본 속성 처리 방법
- 항목 10: 하이버네이트 @Where 어노테이션을 통한 연관관계 필터링 처리
- 항목 11: @MapsId를 통한 단방향/양방향 @OneToOne 최적화 방법
- 항목 12: 단 하나의 연관관계만 Null이 아닌지 확인하는 방법

2장. 엔터티
- 항목 13: 엔터티의 플루언트 API 스타일 적용 방법
- 항목 14: 하이버네이트 프록시를 통한 자식 측에서 부모 연관관계 채우기
- 항목 15: 영속성 레이어에서 자바 8 Optional 사용 방법
- 항목 16: 불변 엔터티 작성 방법
- 항목 17: 엔터티 복제 방법
- 항목 18: 더티 트래킹을 활성화하는 이유와 방법
- 항목 19: 불리언을 Yes/No로 매핑하는 방법
- 항목 20: 애그리거트 루트로부터 최적의 도메인 이벤트 발행

3장. 페치
- 항목 21: 다이렉트 페치 사용 방법
- 항목 22: 미래 영속성 콘텍스트에서 데이터베이스 변경 사항 전파를 위한 읽기 전용 엔터티의 사용 이유
- 항목 23: 하이버네이트 Bytecode Enhancement를 통한 엔터티 속성 지연 로딩 방법
- 항목 24: 서브엔터티를 통한 엔터티 속성 지연 로딩 방법
- 항목 25: 스프링 프로젝션을 통한 DTO 가져오기
- 항목 26: 스프링 프로젝션에서 엔터티를 추가하는 방법
- 항목 27: 엔터티의 일부 또는 외부 가상 속성을 통한 스프링 프로젝션 보완 방법
- 항목 28: * - to  - One 연관관계를 포함하는 스프링 프로젝션의 효율적 로딩 방법
- 항목 29: 연관된 컬렉션을 포함하는 스프링 프로젝션 주의 사항
- 항목 30: 스프링 프로젝션을 통한 모든 속성 가져오는 방법
- 항목 31: 생성자 표현식을 통해 DTO를 가져오는 방법
- 항목 32: 생성자 표현식을 통해 DTO에서 엔터티를 가져오지 말아야 하는 이유
- 항목 33: JPA Tuple을 통해 DTO를 가져오는 방법
- 항목 34: @SqlResultSetMapping 및 @NamedNativeQuery를 통해 DTO를 가져오는 방법
- 항목 35: ResultTransformer를 통해 DTO를 가져오는 방법
- 항목 36: 커스텀 ResultTransformer를 통해 DTO를 가져오는 방법
- 항목 37: @Subselect를 통해 엔터티를 쿼리에 매핑하는 방법
- 항목 38: Blaze - Persistence 엔터티 뷰를 통해 DTO를 가져오는 방법
- 항목 39: 단일 SELECT로 부모와 연관관계를 효율적으로 가져오는 방법
- 항목 40: JOIN과 JOIN FETCH 결정 방법
- 항목 41: 모든 왼쪽 엔터티를 가져오는 방법
- 항목 42: 관련 없는 엔터티로부터 DTO를 가져오는 방법
- 항목 43: JOIN문 작성 방법
- 항목 44: JOIN 페이지네이션 방법

4장. 배치 처리
- 항목 46: 스프링 부트 스타일 배치 등록 방법
- 항목 47: 부모  - 자식 관계 배치 등록 최적화 방법
- 항목 50: CompletableFuture를 통한 엔터티 배치 처리
- 항목 51: 배치 업데이트에 대한 효율적인 처리 방법
- 항목 52: 효율적으로 배치 삭제하는 방법(연관관계 없이)
- 항목 53: 효율적으로 배치 삭제하는 방법(연관관계와 함께)
- 항목 54: 배치로 연관관계 가져오는 방법
- 항목 55: 배치 등록에서 PostgreSQL (BIG)SERIAL을 피해야 하는 이유

5장. 컬렉션
- 항목 56: @ElementCollection 컬렉션 JOIN FETCH 방법
- 항목 57: @ElementCollection에 대한 DTO 방법
- 항목 58: @ElementCollection과 @OrderColumn을 함께 사용해야 하는 이유와 시기
- 항목 59: 엔터티 컬렉션 병합 방법

6장. 커넥션과 트랜잭션
- 항목 60: 실제 필요 시점까지 커넥션 획득 지연 방법
- 항목 61: @Transactional(readOnly=true)의 실제 작동 방식
- 항목 62: 스프링이 @Transactional을 무시하는 이유
- 항목 63: 트랜잭션 타임아웃 설정 및 롤백이 예상대로 작동하는지 확인하는 방법
- 항목 64: 리포지터리 인터페이스에서 @Transactional을 사용하는 이유와 방법

7장. 식별자
- 항목 65: MySQL에서 하이버네이트 5 AUTO 생성자 타입을 피해야 하는 이유
- 항목 66: hi/lo 알고리듬을 통한 시퀀스 식별자 생성 최적화 방법
- 항목 67: Pooled(   - lo) 알고리듬을 통한 시퀀스 식별자 생성 최적화 방법
- 항목 68: equals() 및 hashCode()를 올바로 오버라이드하는 방법
- 항목 69: 스프링 스타일로 하이버네이트 @NaturalId를 사용하는 방법
- 항목 70: 하이버네이트 @NaturalId 사용 및 엔터티 식별자 조회 생략 방법
- 항목 71: @NaturalId 칼럼 참조 연관관계 정의 방법
- 항목 72: 자동 생성 키를 얻는 방법
- 항목 73: 커스텀 시퀀스 ID를 생성하는 방법
- 항목 74: 복합 기본키를 효율적으로 구현하는 방법
- 항목 75: 복합키에서 관계를 정의하는 방법
- 항목 76: 연결 테이블에 대한 엔터티 사용 방법

8장. 산출 속성
- 항목 77: 산출된 비영속 속성 매핑 방법
- 항목 78: @Generated를 통한 산출된 영속 속성 매핑 방법
- 항목 79: JPQL 쿼리에서 여러 파라미터와 함께 SQL 함수 사용 방법
- 항목 80: @JoinFormula를 통해 @ManyToOne 관계를 SQL 쿼리에 매핑하는 방법

9장. 모니터링
- 항목 81: SQL문 카운트 및 어설션 사용 이유와 방법
- 항목 82: 프리페어드 스테이트먼트 바인딩 및 추출 파라미터 로깅 방법
- 항목 83: 쿼리 상세 정보 로깅 방법
- 항목 84: 임계치를 사용한 느린 쿼리 로그 방법
- 항목 85: 트랜잭션 및 쿼리 메서드 상세 로깅

10장. DataSource 및 커넥션 풀 설정
- 항목 86: HikariCP 설정 커스터마이징 방법
- 항목 87: 2개의 커넥션 풀을 갖는 2개의 데이터 소스 구성 방법

11장. 감사
- 항목 88: 생성 및 수정 시간과 엔터티 사용자 추적 방법
- 항목 89: 하이버네이트 Envers 감사 활성화 방법
- 항목 90: 영속성 콘텍스트를 확인하는 방법
- 항목 91: 테이블 메타데이터 추출 방법

12장. 스키마
- 항목 92: 스프링 부트에서 Flyway 설정 방법
- 항목 93: schema    - *.sql을 통한 두 데이터베이스 생성과 엔터티 매칭 방법

13장. 페이지네이션
- 항목 94: 오프셋 페이지네이션 성능 저하 발생 시기와 이유
- 항목 95: COUNT(*) OVER 및 Page〈entity/dto〉를 사용한 오프셋 페이지네이션 최적화 방법
- 항목 96: SELECT COUNT 서브쿼리 및 Page〈entity/dto〉를 사용한 오프셋 페이지네이션 최적화 방법
- 항목 97: JOIN FETCH 및 Pageable 사용 방법
- 항목 98: HHH000104 조치 방법
- 항목 99: Slice〈T〉 findAll() 구현 방법
- 항목 100: 키세트 페이지네이션 구현 방법
- 항목 101: 키세트 페이지네이션에 다음 페이지 버튼 추가 방법
- 항목 102: ROW_NUMBER()을 통한 페이지네이션 구현 방법

14장. 쿼리
- 항목 103: 하이버네이트 HINT_PASS_DISTINCT_THROUGH를 통한 SELECT DISTINCT 최적화 방법
- 항목 104: JPA 콜백 설정 방법
- 항목 105: 스프링 데이터 쿼리 빌더를 통한 결과 세트 크기 제한과 카운트 및 삭제 파생 쿼리 사용 방법
- 항목 106: 포스트 커밋에서 시간 소요가 많은 작업을 피해야 하는 이유
- 항목 107: 중복된 save() 호출을 피하는 방법
- 항목 108: N+1 문제 방지 이유와 방법
- 항목 109: 하이버네이트 기반 소프트 삭제 지원 사용 방법
- 항목 110: OSIV 안티패턴 회피 이유와 방법
- 항목 111: UTC 시간대로 날짜/시간 저장 방법(MySQL)
- 항목 112: ORDER BY RAND()를 통해 작은 결과 세트를 뒤섞는 방법
- 항목 113: WHERE/HAVING 절에서 서브쿼리를 사용하는 방법
- 항목 114: 저장 프로시저 호출 방법
- 항목 116: 데이터베이스 뷰 매핑 방법
- 항목 117: 데이터베이스 뷰 수정 방법
- 항목 118: WITH CHECK OPTION을 사용하는 이유와 방법
- 항목 119: 데이터베이스 임시 순위를 행에 효율적으로 할당하는 방법
- 항목 120: 모든 그룹의 상위 N개 행을 효율적으로 찾는 방법
- 항목 121: Specification API를 통한 고급 검색 구현 방법
- 항목 122: IN 절 파라미터 패딩을 통한 SQL 캐싱 향상 방법
- 항목 123: Specification 쿼리 페치 조인 생성 방법
- 항목 124: 하이버네이트 쿼리 실행 계획 캐시 사용 방법
- 항목 125: 스프링 QBE(Query By Example)를 통한 비영속 엔터티의 데이터베이스 존재 여부 확인 방법
- 항목 126: 하이버네이트 @DynamicUpdate를 통해 수정된 칼럼만 UPDATE문에 포함하는 방법
- 항목 127: 스프링에서 네임드 (네이티브) 쿼리를 사용하는 방법
- 항목 128: 다른 쿼리/요청에서 부모와 자식을 가져오는 가장 좋은 방법
- 항목 129: 업데이트를 사용한 병합 작업 최적화 방법
- 항목 130: SKIP LOCKED 옵션을 통한 동시 테이블 기반 큐 구현 방법
- 항목 131: 버전 기반(@Version) OptimisticLockException 발생 후 트랜잭션 재시도 방법
- 항목 132: 버전 없는 OptimisticLockException의 트랜잭션 재시도 방법
- 항목 133: 버전 기반 낙관적 잠금 및 분리된 엔터티를 처리하는 방법
- 항목 134: 장기 HTTP 통신에서의 낙관적 잠금 메커니즘 및 분리된 엔터티 사용 방법
- 항목 135: 엔터티가 수정되지 않은 경우에도 잠긴 엔터티 버전을 증가시키는 방법
- 항목 136: PESSIMISTIC_READ/WRITE 작동 방식
- 항목 137: PESSIMISTIC_WRITE가 UPDATE/INSERT 및 DELETE에서 작동하는 방식

15장. 상속
- 항목 138: 단일 테이블 상속을 효율적으로 사용하는 방법
- 항목 139: SINGLE_TABLE 상속 계층 구조에서 특정 하위 클래스 가져오기
- 항목 140: 조인 테이블 상속의 효율적 사용 방법
- 항목 141: 클래스별 테이블 상속의 효율적 사용 방법
- 항목 142: @MappedSuperclass 효율적 사용 방법

16장. 일반 타입과 하이버네이트 타입
- 항목 143: 하이버네이트 타입 라이브러리를 통한 하이버네이트 및 미지원 타입 처리 방법
- 항목 144: CLOB 및 BLOB 매핑 방법
- 항목 145: 자바 열거형을 데이터베이스에 효율적으로 매핑하는 방법
- 항목 146: JSON 자바 객체를 MySQL JSON 칼럼에 효율적으로 매핑하는 방법
- 항목 147: JSON 자바 Object를 PostgreSQL JSON 칼럼에 효율적으로 매핑하는 방법

부록
- 부록 A. (하이버네이트) JPA 기본 사항
- 부록 B. 연관관계 효율성
- 부록 C. 하루를 절약할 수 있는 5가지 SQL 성능 팁
- 부록 D. 유용한 데이터베이스 인덱스를 만드는 방법
- 부록 E. SQL Phenomena
- 부록 F. 스프링 트랜잭션 격리 수준
- 부록 G. 스프링 트랜잭션 전파
- 부록 H. 플러싱 메커니즘
- 부록 I. 2차 캐시
- 부록 J. 도구
- 부록 K. 하이버네이트 6
