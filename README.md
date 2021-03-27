# Google Page Clone Project



#### 혹시 HTML과 CSS가 처음이시라면 이 <a href="https://github.com/keinn51/Basic_Html_CSS">사이트</a> 에서 기초에 대해서 학습해 보세요!

<br>

이 레퍼지토리는 HTML과 CSS의 기본에 대해서 학습하기 위해 만들어졌다.

구글 페이지를 간단하게 클로닝 하면서, 기초적으로 알고 있었던 <b>HTML지식과 CSS지식</b>을 응용해보자.

<br>

결과적으로 다음과 같이 만들어져야 한다.
<br>



<img width="1437" alt="스크린샷 2021-03-27 오후 7 34 52" src="https://user-images.githubusercontent.com/79993356/112717992-8147c300-8f33-11eb-9979-6902cc267acc.png">



<br>

아래부터는 개인적으로 클로닝을 하면서 체크해볼 만하다고 생각했던 것들을 정리한 내용이다.

아래 내용은 약간의 스포를 담고 있다..😅 하지만 모르는 상태에서 MDN만 알고 만들기는 쉽지 않으니 한 번 보고 만들어보는 걸 추천한다 🙌

<br><br>


---



**✅ Link와 favicon**

<br>

![1](https://user-images.githubusercontent.com/79993356/112718524-ebae3280-8f36-11eb-8afd-4d3f3f173075.png)



<a href="https://technote.kr/187">Link란??</a>



rel은 html과 이미지와의 상관 관계를 알려주는 속성이다.

 

여기서 중요한건 favicon이란 과연 무엇인가이다. (왜 favicon을 <a href="https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwj6n7f7uvDuAhWZd94KHXsrCZQQFjAAegQIARAC&url=https%3A%2F%2Fmoolgogiheart.tistory.com%2F84&usg=AOvVaw0u_FD3ZW-VgRivKH3jvklT">두 개</a>나 설정 했을까?)

 

Favicon은 쉽게 얘기해서, 웹사이트 접속했을 때, 탭에서 보이는 이미지이다.

<br>

![2](https://user-images.githubusercontent.com/79993356/112718588-69723e00-8f37-11eb-9a9e-5061f1698298.png)



이런 것이라고 보면 된다.



<br><br>



**✅ hover**

<br>

![4](https://user-images.githubusercontent.com/79993356/112718638-b1916080-8f37-11eb-98d7-5172df6ee9ed.png)

a속성을 가진 요소 위로 마우스 커서를 가져가면 효과가 발생한다.

<br>

![5](https://user-images.githubusercontent.com/79993356/112718656-cc63d500-8f37-11eb-9fea-3d7ade7ac83b.png)

원래는 빨간색 문자였는데, 클릭하니까 <b>오렌지 색</b>으로 변한다!



<br>

<br>



**✅ Block & Inline**



![7](https://user-images.githubusercontent.com/79993356/112720861-37b3a400-8f44-11eb-81a4-38803fb78d87.png)



Block과 inline요소는 **매우매우 중요하다!**

위에 나타난 것에서와 같이 b, span, a 말고는 거의 다 block요소이다.

>  block요소의 가장 중요한 특징은 가로화면의 100%를 자기가 다 차지한다.

<a href="https://homzzang.com/b/html-103"> block VS inline</a>

<br><br>



<b>✅ display</b>

<a href="https://aboooks.tistory.com/85">display란?</a>

inline과 block요소는 display로 사용자가 요소를 어떻게 바라볼 지를 설정한다.



원래 inline 요소를 block 요소로 보이게 만들 수도 있고, 원래 block 요소를 inline 처럼 보이게 만들 수도 있다.



주로 div 태그 안에서 가장 많이 설정해주는 편이다.



![6](https://user-images.githubusercontent.com/79993356/112721106-7b5add80-8f45-11eb-9398-d3edf0b5bc64.png)



<br>

<br>

**✅ span**

![8](https://user-images.githubusercontent.com/79993356/112721164-cbd23b00-8f45-11eb-80bf-391c17925fed.png)



<br>

<br>

**✅ Padding**

![9](https://user-images.githubusercontent.com/79993356/112721177-e1dffb80-8f45-11eb-9ae0-3f00943e815a.png)



<a href="https://bangu4.tistory.com/25">Margin과 Padding의 차이</a>

**border**을 경계로 Margin은 바깥쪽, padding은 안 쪽의 공백을 의미한다!



<br>

<br>

**✅ border**

![0](https://user-images.githubusercontent.com/79993356/112721351-af82ce00-8f46-11eb-88de-012c6c6815fc.png)



border을 코딩할 때에는 '너비-스타일-색상' 순이다.

EX) border: 1px **solid** black;

**반드시 스타일 속성은 입력해야한다.** 안 그러면 아무 것도 안 나온다.

<br>

![2](https://user-images.githubusercontent.com/79993356/112721420-f375d300-8f46-11eb-9151-4dd6a0491bae.png)



요소의 네모난 부분을 동글동글하게 만들고 싶다면, **border-radius**를 쓰면 된다.

신기하게도 얘는 border이 없어도 쓸 수 있다.

<br><br>

**✅ Margin Auto**

![3](https://user-images.githubusercontent.com/79993356/112721387-d50fd780-8f46-11eb-99bd-b8f9e9b4f015.png)



웹페이지에서 이미지를 중앙에 맞추어야 할 때, 굳이 margin을 양쪽으로 **픽셀 하나하나 맞출 필요는 없다.**

display를 block요소를 주고, margin을 auto를 주면 알아서 **''중앙 정렬''**을 해주는 신기한 현상을 볼 수 있다.

이 것이 무슨 말인지 모른다면 **MDN사이트**를 참고한다😄

<br><br>

**✅ position**



![5](https://user-images.githubusercontent.com/79993356/112721398-dd681280-8f46-11eb-9e8e-f5b1dfd7e389.png)



CSS position 속성은 **문서 상에 요소를 배치하는 방법**을 지정한다.

<br>

![6](https://user-images.githubusercontent.com/79993356/112721399-de993f80-8f46-11eb-8761-cff6b851a090.png)



**Absolute**는 문서에서 내가 원하는 요소가 어디에 위치할 것인지에 대해서 '절대적인 좌표'로 표현하는 것이다.

 **공간을 차지하지 않아서, 다른 요소 위에서 나타나곤 한다.**

<br>

![8](https://user-images.githubusercontent.com/79993356/112721401-df31d600-8f46-11eb-97bb-24a10bfcfca7.png)



반대로 **relative**는 **원래대로 코딩하면 있어야 할 위치에서 부터 ** 이동시켜 준다. 

하지만 **공간을 가지기** 때문에, 원래 있던 자리에도 공백이 생긴다.



따라서 내가 'Bottom:0' 이라고 두었으니, 저 요소는 페이지 제일 아래 쪽에, 여백 없이 들어간다는 것을 알 수 있다.

<br><br>

+ **z-Index**



![image](https://user-images.githubusercontent.com/79993356/112721632-43a16500-8f48-11eb-8e6e-67a0f7e5fa95.png)



위와 같은 순서로 div태그가 설정되어 있다고 한다면, 

<br>

![9](https://user-images.githubusercontent.com/79993356/112721402-dfca6c80-8f46-11eb-8522-c732990aeedf.png)



이렇게 된다.

이 친구는 **요소가 겹칠 때 순서를 정해주는** 친구다. **높은 숫자 일수록 앞으로** 나온다.
