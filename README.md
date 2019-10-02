# SDIPen

1. CLine 클래스 추가
![Alt text](_images/1.PNG)

2. CLine.h에 아래와 같이 코드 작성
![Alt text](_images/2.PNG)

3. CLine.cpp에 아래와 같이 코드 추가
![Alt text](_images/3.PNG)

4. PenDoc.h의 public 에 아래와 같이 코드 추가
![Alt text](_images/4.PNG)

5. 속성의 메시지를 통해 WM_MOUSEMOVE 추가
![Alt text](_images/5.PNG)

6. PenView.cpp의 OnDraw에 아래와 같이 코드 추가
![Alt text](_images/6.PNG)

7. 클래스 뷰에서 CPenDoc을 선택 후 OnNewDocument와 Serialize 추가  
![Alt text](_images/7.PNG)

8. PenDoc.cpp에서 아래와 같이 코드 추가 후 Ctrl+F5
![Alt text](_images/8.PNG)
