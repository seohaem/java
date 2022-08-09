# effective_java
[BOOK/강의] 이펙티브 자바 책 + 강의로 공부하기

1. 시작일 : 2021/10/09
2. 종료일 : 2021/12/23
3. 상태 : 완료 


### blog 포스팅 바로가기 (복습 시작 : 2022/07/08 ~)
| | | |
|-|-|-|
|공부일자|제목|URL|
|-|아이템 1. 생성자 대신 정적 팩터리 메서드를 고려하라|포스팅 준비중|
|-|아이템 2. 생성자에 매개변수가 많다면 빌더를 고려하라|포스팅 준비중|
|-|아이템 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라|포스팅 준비중|
|-|아이템 4. 인스턴스화를 막으려거든 private 생성자를 사용하라|포스팅 준비중|
|-|아이템 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라|포스팅 준비중|
|-|아이템 6. 불필요한 객체 생성을 피하라 |포스팅 준비중|
|-|아이템 7. 다 쓴 객체 참조를 해제하라|포스팅 준비중|
|-|아이템 8. finalizer와 cleaner 사용을 피하라|포스팅 준비중|
|-|아이템 9. try-finally보다는 try-with-resources를 사용하라|포스팅 준비중|
|-|아이템 10. equals는 일반 규약을 지켜 재정의하라|포스팅 준비중|
|-|아이템 11. equals를 재정의하려거든 hashCode도 재정의하라|포스팅 준비중|
|-|아이템 12. toString을 항상 재정의하라|포스팅 준비중|
|-|아이템 13. clone 재정의는 주의해서 진행하라|포스팅 준비중|
|-|아이템 14. Comparable을 구현할지 고려하라|포스팅 준비중|
|07/11|아이템 15. 클래스와 멤버의 접근 권한을 최소화하라|https://devfunny.tistory.com/540|
|07/11|아이템 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라|https://devfunny.tistory.com/542|
|07/12|아이템 17. 변경 가능성을 최소화하라|https://devfunny.tistory.com/543|
|07/13|아이템 18. 상속보다는 컴포지션을 사용하라|https://devfunny.tistory.com/544|
|07/14|아이템 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라|https://devfunny.tistory.com/548|
|07/15|아이템 20. 추상 클래스보다는 인터페이스를 우선하라|https://devfunny.tistory.com/551|
|07/16|아이템 21. 인터페이스는 구현하는 쪽을 생각해 설계하라|https://devfunny.tistory.com/556|
|07/17|아이템 22. 인터페이스는 타입을 정의하는 용도로만 사용하라|https://devfunny.tistory.com/558|
|07/17|아이템 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라|https://devfunny.tistory.com/560|
|07/19|아이템 24. 멤버 클래스는 되도록 static으로 만들라|https://devfunny.tistory.com/561|
|07/21|아이템 25. 톱레벨 클래스는 한 파일에 하나만 담으라|https://devfunny.tistory.com/562|
|07/25|아이템 26. 로 타입은 사용하지 말라|https://devfunny.tistory.com/563|
|07/26|아이템 27. 비검사 경고를 제거하라|https://devfunny.tistory.com/573|
|07/27|아이템 28. 배열보다는 리스트를 사용하라|https://devfunny.tistory.com/574|
|07/30|아이템 29. 이왕이면 제네릭 타입으로 만들라|https://devfunny.tistory.com/575|
|07/31|아이템 30. 이왕이면 제네릭 메서드로 만들라|https://devfunny.tistory.com/576|
|08/01|아이템 31. 한정적 와일드카드를 사용해 API 유연성을 높이라|https://devfunny.tistory.com/579|
|08/02|아이템 32. 제네릭과 가변인수를 함께 쓸 때는 신중하라|https://devfunny.tistory.com/582|
|08/03|아이템 33. 타입 안전 이종 컨테이너를 고려하라|https://devfunny.tistory.com/585|
|08/04|아이템 34. int 상수 대신 열거 타입을 사용하라|https://devfunny.tistory.com/586|
|08/04|아이템 35. ordinal 메서드 대신 인스턴스 필드를 사용하라|https://devfunny.tistory.com/587|
|08/05|아이템 36. 비트 필드 대신 EnumSet을 사용하라|https://devfunny.tistory.com/588|
|08/06|아이템 37. ordinal 인덱싱 대신 EnumMap을 사용하라|https://devfunny.tistory.com/589|
|08/06|아이템 38. 확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라|https://devfunny.tistory.com/590|
|08/06|아이템 39. 명명 패턴보다 애너테이션을 사용하라|https://devfunny.tistory.com/591|
|08/06|아이템 40. @Override 애너테이션을 일관되게 사용하라|https://devfunny.tistory.com/592|
|08/06|아이템 41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라|https://devfunny.tistory.com/593|
|08/06|아이템 42. 익명 클래스보다는 람다를 사용하라|https://devfunny.tistory.com/594|
|08/07|아이템 43. 람다보다는 메서드 참조를 사용하라|https://devfunny.tistory.com/596|
|08/07|아이템 44. 표준 함수형 인터페이스를 사용하라|https://devfunny.tistory.com/598|
|08/07|아이템 45. 스트림은 주의해서 사용하라|https://devfunny.tistory.com/600|
|08/07|아이템 46. 스트림에서는 부작용 없는 함수를 사용하라|https://devfunny.tistory.com/602|
|08/08|아이템 47. 반환 타입으로는 스트림보다 컬렉션이 낫다|https://devfunny.tistory.com/604|
|08/08|아이템 48. 스트림 병렬화는 주의해서 적용하라|https://devfunny.tistory.com/606|
|08/08|아이템 49. 매개변수가 유효한지 검사하라|https://devfunny.tistory.com/612|
|08/09|아이템 50. 적시에 방어적 복사본을 만들라|https://devfunny.tistory.com/613|
