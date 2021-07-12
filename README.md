# TestProgram1
1. bulid path -> lombok 라이브러리 추가한다.
2. BeanConfiguration.java : @Configuration import한다.
3. BoardController.java : @GetMapping(value = "insert.do") -> @PostMapping(value = "insert.do") 변경한다.
4. board.sql : COMMIT; -> COMMIT
5. dependency jackson-databind 추가
6. spring-test version 5.1.4.RELEASE로 수정
