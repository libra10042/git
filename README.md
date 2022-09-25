### Git commit message

---

[좋은 Git commit message를 위한 영어사전](https://blog.ull.im/engineering/2019/03/10/logs-on-git.html) / [Commit Convension](https://www.google.com/search?q=%ED%8F%B4%EB%8D%94+%EC%88%98%EC%A0%95+coding+conversion&oq=%ED%8F%B4%EB%8D%94+%EC%88%98%EC%A0%95+coding+conversion&aqs=chrome..69i57j0i546l2.6192j0j7&sourceid=chrome&ie=UTF-8)

- **feat** : 새로운 기능 추가
- **fix** : 버그 수정
- **docs** : 문서 수정
- **style** : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- **refactor** : 코드 리펙토링
- **test** : 테스트 코드, 리펙토링 테스트 코드 추가 
- **chore** : 빌드 업무 수정, 패키지 매니저 수정
- **rename** :	파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
- **solve** : 알고리즘 문제

<br><br>

### Java docs

| 이름 | 설명 |
| --- | --- |
| @version | 패키지 등 구현체 버전 |
| @author | 코드 작성자 |
| @deprecated | 해당 구현체의 삭제, 지원 중단을 예고함.  |
| @since | 해당 구현체가 추가된 버전. |
| @see |  참조할 다른 클래스/ 메서드 / 외부 링크. |
| @link | @see 와 동일 |
| @exception | [ExceptionClass Desciption] throw 할 수 있는 예외 정의, ExceptionClass 알파벳 순으로 작성. |
| @throws | @exception과 동일 |
| @param | [ParamName Description] 메서드, 생성자 인자값 설명 |
| @return | 반환 값 설명 |
| @serial | Serializeable 인터페이스에 사용 |
| @serialData | writeObject writeExternal 메서드로 작성된 추가적 데이터를 설명 |
| @serialField | serialPersistnetFields 배열의 모든 필드에 사용.  |


<br><br>

### Git-flow strategies

- master : 제품으로 출시될 수 있는 브랜치
- develop : 다음 출시 버전을 개발하는 브랜치
- feature : 기능을 개발하는 브랜치
- release : 이번 출시 버전을 준비하는 브랜치
- hotfix : 출시 버전에서 발생한 버그를 수정 하는 브랜치
