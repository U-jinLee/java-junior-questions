# java-junior-questions
자바의 기본적인 질문과 답변을 업데이트 하는 리포지토리

## 1️⃣ 기초

1. 📌 JDK와 JRE의 차이점은 무엇입니까?
- 자바 개발 도구, 자바 실행 환경 JDK안에 JRE가 포함되고 JVM은 JRE에 포함된다. 개발을 하기 위해서는 JDK만 다운받으면 된다.
2. 📌 ==와 equals의 차이점은 무엇입니까?
- equals는 대상의 내용 자체의 비교이고 ==연산자는 대상의 주소값을 비교
3. 📌 두 객체가 동일한 hashCode를 가지면 Equals()가 참이어야 합니다, 그렇죠?
- hashcode 외에도 객체의 값과 등 객체의 내부상태와 비교돼야 한다.
5. 📌 자바에서 final의 기능은 무엇입니까?
- 한번 값이 정해진 후 변수 내의 값이 변하지 않음을 의미
6. 📌 자바에서 Math.round(-1.5)는 무엇을 의미합니까?
- 반올림에 사용하는 static 메서드
7. 📌 String은 기본 데이터 타입입니까?
- String은 primitive type이 아닌 참조 타입, 문자열 데이터의 주소를 참조하는 방식으로 동작
8. 📌 자바에서 문자열을 조작하는 클래스는 무엇이 있습니까? 각 클래스의 차이점은 뭘까요?
9. 📌 String str ="i"와 String str = new String("i")가 동일합니까?
- String str = "i"는 문자열 리터럴로 초기화된 문자열 객체이며 해당 객체는 문자열 풀에 저장된다. new String("i")는 새로운 문자열 객체를 생성한 것이다.
10. 📌 문자열을 반전시키는 가장 좋은 방법은 무엇인가요?
11. 📌 String 클래스의 일반적인 메서드는 무엇이 있나요?
12. 📌 추상 클래스에서 추상 메서드는 필수적인가요?
13. 📌 보통의 클래스와 추상 클래스의 차이는 무엇인가요?
14. 📌 final은 추상 클래스를 수정할 때 사용할 수 있나요?

## 2️⃣ Container

14. 📌 자바 컨테이너란 무엇인가요?
15. 📌 Collection과 Collections의 차이는 무엇인가요?
16. 📌 List, Set, Map의 차이점을 말해주세요.
17. 📌 HashMap과 Hashtable의 차이는 무엇인가요?
18. 📌 각각 어떤 상황에서 HashMap과 TreeMap을 선택하나요?
19. 📌 HashMap 구현 원칙은 무엇인가요?
20. 📌 HashSet 구현 원칙은 무엇인가요?
21. 📌 ArrayList와 LinkedList의 차이점은 무엇인가요?
22. 📌 Array에서 List로 전환하려면 어떻게 해야하나요?
23. 📌 ArrayList와 Vector의 차이점을 말해주세요.
24. 📌 Array와 ArrayList의 차이점을 말해주세요.
25. 📌 Queue에서, poll()과 remove()의 차이는 무엇인가요?
26. 📌 thread-safe한 컬렉션 클래스들은 무엇이 있을까요?
27. 📌 iterator란 무엇인가요?
28. 📌 iterator의 사용 목적은 무엇인가요? 어떤 특징이 있죠?
29. 📌 iterator와 listIterator의 차이는 무엇인가요?

## 3️⃣ multi-threading

30. 📌 병렬과 동시성의 차이점을 말해주세요.
31. 📌 스레드와 프로세스의 차이를 말해주세요.. 
- 프로세스는 운영체제로부터 자원을 할당받아 실행 중인 프로그램 인스턴스, 스레드는 그 프로세스 내에서 실행되는 작은 작업 단위
32. 📌 데몬 스레드는 무엇인가요?
33. 📌 스레드를 만드는 방법을 나열해주세요.
34. 📌 runnable과 callable의 차이는 무엇인가요?
35. 📌 스레드의 여러가지 상태에 대해 말해주세요.
36. 📌 sleep()과 wait()의 차이는 무엇인가요?
37. 📌 notify()와 notifyAll()의 차이는 무엇인가요?
38. 📌 thread run()과 tnread start()의 차이는 무엇인가요?
39. 📌 스레드 풀을 생성할 수 있는 여러가지 방법을 말해주세요.
40. 📌 스레드 풀의 상태에 대해 말해주세요.
41. 📌 스레드 풀에서 submit()과 execute()의 차이는 무엇인가요?
42. 📌 자바 프로그램에서 멀티 스레드 작업의 안전성을 어떻게 보장할 수 있을까요?
- synchronized 키워드를 사용하여 공유 데이터에 대한 접근을 동기화할 수 있습니다.
## 4️⃣ reflection

43. 📌 reflection이란 무엇인가요?
44. 📌 자바 직렬화란 무엇인가요? 어떤 상황에서 필요한가요?
45. 📌 동적 프록시란 무엇인가요? 
46. 📌 동적 프록시는 어떻게 사용하나요?

## 5️⃣ object copy

47. 📌 복사가 사용되는 이유는 무엇인가요?
48. 📌 객체 복사는 어떻게 할 수 있나요?
49. 📌 깊은 복사와 얕은 복사의 차이를 말해주세요.
