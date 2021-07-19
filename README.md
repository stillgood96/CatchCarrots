# CatchCarrots

https://stillgood96.github.io/CatchCarrots/

자바스크립트만 이용해서 만든 미니게임 
플레이 버튼을 누르면 타이머가 작동하고 시간안에 당근을 전부 클릭해야합니다.
도중에 벌레를 클릭하거나 시간안에 당근을 클릭못하면 판업이 나오고 정지버튼을 눌렀을 때도 마찬가지로 판업이 나옵니다. 
![image](https://user-images.githubusercontent.com/74526642/126193402-62f9f28d-9f89-4a2a-9ec9-c7a2c908fa9d.png)



1. HTML 

    ![image](https://user-images.githubusercontent.com/74526642/126193941-d57bc6b1-0c05-409b-a3d0-9366c07db5f5.png)
  
     먼저 헤더태그 안에는 게임시작 버튼, 타이머, 클릭해야할 당근의 수를 나타내도록 했습니다.
    ![image](https://user-images.githubusercontent.com/74526642/126194510-fcca0f4a-f091-4423-96ac-e54ef29f0cd9.png)


    그리고 게임이 정지될 때 보여질 pop-up 부분입니다.
    ![image](https://user-images.githubusercontent.com/74526642/126194596-29fc5077-3020-403c-9651-0c2348b804df.png)
    ![image](https://user-images.githubusercontent.com/74526642/126194704-41c2b256-7977-473d-a5f1-0a306896832b.png)


2. CSS 
  
    공통적인 CSS값 같은경우는 root를 이용해서 CSS 전역변수를 선언해서 사용했습니다.
    ![image](https://user-images.githubusercontent.com/74526642/126196864-66163bee-2134-47b8-8977-5766402f70a1.png)

    전체적인 스타일링은 flex를 이용해서 진행했습니다.
    ![image](https://user-images.githubusercontent.com/74526642/126196962-14c1f2f7-19a0-4f50-9231-074c5800f729.png)
  

3. JavaScript

    여기서 핵심적인 부분은 게임이 시작되면 벌레와 당근이 랜덤한 위치에 깔리게 되어야하는 부분이라고 생각합니다. 
    
    field 태그 내부에 벌레와 당근을 배치할것이고 깔기위한 field의 전체적인 좌표를 알아야 합니다.
    좌표를알기위해 getBoundingClientRect를 이용해서 함수를 정의합니다.
    ![image](https://user-images.githubusercontent.com/74526642/126202115-eae418ae-1542-4b27-b2b1-5c5d80fc16f4.png)
    ![image](https://user-images.githubusercontent.com/74526642/126203740-24e34a92-f1d7-4ea5-8ec3-839fe7a5285a.png)


  
  
  
