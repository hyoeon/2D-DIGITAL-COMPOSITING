__1. Gamma__  
- 디스플레이에 입력되는 신호의 밝기(Gray Level)와 화면상에 나타나는 영상의 휘도 간 상관 관계를 결정하는 수치  
- 기기의 차이 있음  
- Gamma value=1 입력=출력  
    Gamma value>1 화면이 어둡게 표현  
    Gamma value<1 화면이 밝게 표현  

- Linear Workflow  
감마 조작     
제대로 안 되어 있으면 이슈 발생  
8bit sRGB 이미지들이 감마 적용 후 생기는 이슈가 다수, 요즘은 x  
프로그램 내 스포이드로 뽑은 컬러, HDR 이미지들은 linear space로 제작 됨  

![](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FkI5tJ%2FbtqtYLHZ3Gs%2Fet3rchG3M94RLRGvnd0Mek%2Fimg.jpg)  
<https://frauniemand.tistory.com/8>  
<https://kyoungwhankim.github.io/ko/blog/color_linearworkflow/>  
<https://www.youtube.com/watch?v=Hlj5ep-85ys>  

__2. ACES__  
- 아카데미에서 개발한 컬러 시스템  
- 미디어 엔터테인먼트 산업의 변화, 디지털로의 전환 -> 표준 제시 
 
 
__3. Premultiplication__
- rgb pixel과 alpha pixel을 곱해둠 
- 제대로 안 될 경우, 외곽부분이 어둡게 또는 밝게 변함


1)  Straight alpha (unassociated alpha; unmatted RGB + alpha)  
    R - Red, G - Green, B - Blue, A - Alpha 각각을 나타냄  
2)  Premultiplied alpha (associated alpha; matted RGB  + alpha)  
    Alpha 값을 미리 RGB에 곱해둠  


<https://www.teamten.com/lawrence/graphics/premultiplication/>  
<https://nanite.tistory.com/98>  
