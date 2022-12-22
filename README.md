# Java_web_handling
자바 웹을 다루는 기술
## 책 이미지
![image](https://user-images.githubusercontent.com/96603612/209159653-086fd4f6-f6f0-44c0-96ea-f81a86487fdc.png)



### 챕터 5장 서블릿 기초

#### 서블릿 메서드 호출
    @Override
    public void init() throws ServletException{
      System.out.println("init 메서드 호출");
    }

    //브라우저의 요청 처리
    @Override
    protected void doGet(HttpServletRequest req, HttpServletResponse resp)
    throws ServletException, IOException{
      System.out.println("doGet 메서드 호출");
    }

    @Override
    public void destroy() {
      System.out.println("destroy 메서드 호출");
    }
   
