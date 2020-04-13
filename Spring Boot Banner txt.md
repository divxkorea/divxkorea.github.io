# [Spring Boot] Banner.txt를 이용한 버전 명시

1.각 프로젝트 yml 파일에 application > name 항목 밑에 version 속성 및 버전을 명시해주세요.

예제)

![Spring%20Boot%20Banner%20txt/Untitled.png](Spring%20Boot%20Banner%20txt/Untitled.png)

2.아래 사이트에서 아스키 텍스트 코드를 생성 후 생성된 Text를 복사해주세요.(Font는 본인 편한대로 명시 혹은 팀내 별도로 정의 필요)

[http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type Something](http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20)

3.각 프로젝트 resources 폴더 하위에 banner.txt파일을 생성합니다. 2번 과정에서 복사한 text를 붙여넣기 합니다.

예제)

[banner.txt](Spring%20Boot%20Banner%20txt/banner.txt)

[4. Run](http://4.Run) 또는 maven install 시 War파일에 banner.txt파일이 포함되며 실제 Start시 아래와 같이 프로젝트에 대한 버전 명명 함께 명시됨을 확인 가능합니다.

![Spring%20Boot%20Banner%20txt/Untitled%201.png](Spring%20Boot%20Banner%20txt/Untitled%201.png)