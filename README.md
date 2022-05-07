## Linux를 이용한 서버 설치 방법


## 1. Apache-Tomcat 연동, app deploy


### 개념 

![image](https://user-images.githubusercontent.com/100884647/167235208-b5df6884-bd1e-427b-acab-cdb0aafa27a5.png)

- Apache<br>
-   아파치 소프트웨어 재단에서 만든 Web Server.<br>  
-   정적 데이터 요청을 처리하는 데 적합하다.
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



   

