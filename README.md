# Linux를 이용한 서버 설치 방법


## 1. Apache-Tomcat 연동, app deploy


### 개념 

![image](https://user-images.githubusercontent.com/100884647/167235208-b5df6884-bd1e-427b-acab-cdb0aafa27a5.png)

- Apache<br>
    아파치 소프트웨어 재단에서 만든 Web Server.<br>  
    정적 데이터 요청을 처리하는 데 적합하다.
<br>     
- Tomcat<br>
    아파치 소프트웨어 재단에서 유지하는 서블릿 컨테이너만 있는 웹 애플리케이션 서버(WAS).<br>
    동적인 정보를 처리한다.<br>
    
- Mod_jk<br>
    Apache(WS)와 Tomcat(WAS)을 연동하기 위한 Module이다.<br>
    mod_jk는 Tomcat의 일부로 배포 되지만, Apache(WS)에 설치되어야 한다.<br>
    
    

- 연동 과정
![image](https://user-images.githubusercontent.com/100884647/167235627-8e000551-b699-45ea-b66c-6cefe0b01fc6.png)

### Apache-Tomcat 설치 및 연동, app deploy하는 방법
<iframe width="949" height="534" src="https://www.youtube.com/embed/dbIq0sKl5nw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## 2. Oracle Weblogic 설치 및 app deploy


### 개념

- Oracle Weblogic<br>
    오라클이 개발한 자바 EE 웹 애플리케이션 서버.<br>
   
  

![image](https://user-images.githubusercontent.com/100884647/167236150-9f1de6dc-654f-4a79-bdf0-a40df8547238.png)

- Domain<br>
    WebLogic의 관리단위.<br>
    WebLogic을 사용하기 위해 필요한 스크립트와 서버로그의 기본위치.<br><br>
    Domain에서 구성된 환경 및 자원은 동일 Domain 내에서 적용.<br>

- DAS(Domain Administration Server)<br>
    하나의 Domain을 관리하기 위한 관리서버.<br>
    Domain의 구성 및 설정 가능.<br>
    
- MS(Managed Server)<br>
    DAS에 종속적인 WebLogic 인스턴스.<br>
    실제 서비스 배포.<br>
    
- Cluster<br>
    무중단 페일오버(Failover)를 위해 구성.<br>
    같은 Domain의 두 개 이상의 서버로 구성.<br>
    

### Oracle Weblogic 설치 및 사용 

<iframe width="949" height="534" src="https://www.youtube.com/embed/BoTuSUeKpug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
   

