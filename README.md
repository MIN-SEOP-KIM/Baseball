 # :baseball: 야구게임

## :baseball:규칙
![image](https://user-images.githubusercontent.com/93521131/173282617-03dcd89a-29a3-4d18-913a-1e8c4096441f.png)

(출처 : https://namu.wiki/w/%EC%88%AB%EC%9E%90%EC%95%BC%EA%B5%AC)

 이 규칙에 맞게 코드를 작성하였다.

 ## :baseball:코드

 ![image](https://user-images.githubusercontent.com/93521131/173283191-e1547bd7-08fb-4821-bd67-6f8c004d46cd.png)

컴퓨터가 임의로 정수를 지정해주고  do - while문을 통해 3개의 정수값이 중복되지 않도록, 코드를 작성해 주었다.

 ![image](https://user-images.githubusercontent.com/93521131/173283507-b67a0772-fe66-4862-90e0-83e9312ad87e.png)

횟수를 카운트 할 변수와 strike,ball을 카운트 할 변수 , 사용자가 입력한것을 받을 배열, 컴퓨터가 임의로 지정한 변수를 저장할 배열을 만들어주고,
while문에 들어가기 전에 do를 사용하여 카운트를 증가시켜 준다.

![image](https://user-images.githubusercontent.com/93521131/173283720-ead81800-e263-4d5e-8779-9c7b78526e19.png)

사용자가 입력한 정수값이 중복이 되지 않게 두번째 do에 작성한 코드이다. 마지막 while은 값이 같지 않을때 까지
 do -while이 반복되게 하는 코드이다.

![image](https://user-images.githubusercontent.com/93521131/173283990-5a02be21-3283-4128-a32a-4932d7ce0a29.png)

if를 통해 strike와 ball를 구분해주고, while문의 조건이 맞기 전까지, count값을 증가시켜준다 . 그후 count 값을 리턴해준다.

![image](https://user-images.githubusercontent.com/93521131/173284128-71542bcd-cb4e-4d47-8afb-6c20ac38ffc2.png)

if문안에서 playGame() 메소드에서 x,y,z의 리턴값을 가져와 result에 저장하고 , 그 result 값과 조건문 안의 값과 비교한 후 결과를 출력한다.

## :baseball:실행화면
![image](https://user-images.githubusercontent.com/93521131/173287098-330cb8c7-2ba3-4855-9f23-37244ceea176.png)

이런식으로 실행되며,

![image](https://user-images.githubusercontent.com/93521131/173287147-5f7ee96b-b8d4-4a5b-95ae-098bc2d34a73.png)

 strike가 3번이거나 , ball 11번 또는 다 맞추지 못했을 경우 결과 값을 출력해준다.
