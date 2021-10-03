__1. RGB와 CMYK__
- RGB: 가산혼합(빛), 디지털  
    Primary Colors: Red, Green, Blue  
- CMYK: 감산혼합(안료), 출력  
    Primary Colors: Cyan, Magenta, Yellow, Key/Black  
      
 Visble Colors>RGB>CMYK  
  
![](https://blog.pack.ly/wp-content/uploads/2016/04/cmyk-rgb-color-gamut-300x269-1.png.webp)  
<https://incheon.greenart.co.kr/community/greenDesignNews_view?idx=1312>  
<https://www.kopytek.com/blog/know-difference-cmyk-rgb/>  
<https://www.myprintsouth.com/resources/blog_articles.html/article/2018/01/22/designing-for-print-rgb-vs-cmyk>  
<https://blog.pack.ly/en/graphic-design-in-a-nutshell-part-3-rgb-or-cmyk-which-and-when/cmyk-rgb-color-gamut-300x269/>  

__2. Bit Depth__  
- Pixel: 이미지의 최소 단위  
- Bit: 1pixel 당 표현할 수 있는 RGB 색상의 개수  
    영상화질에 결정적인 영향을 미치는 요소  
    0 또는 1  
    ex) 1 bit = 0, 1  
        2 bit = 00, 01, 10, 11  
    0부터 시작  
    ex) 8bit = 0~255 총 256  
    Bit Depth(Color Depth) 숫자가 높을수록 세밀한 표현 가능  

<https://www.youtube.com/watch?v=y23s8-p37WU>  
<https://www.youtube.com/watch?v=1_mbGO_KNzg>



__3. Alpha__  
- 투명도(Transparency) channel  
- RGBA (Full-color pixel)  
- RGB 각 채널에서 흰색에 가까울 수록 해당 채널의 색과 비슷하고, 검은색에 가까울수록 반대의 색  
- Photoshop 레이어 마스크(Layer Mask): 알파 채널을 시각화 할 수 있는 방법 중 하나  

__4. Color Space__  
- Vector Data
- (x, y, z) (r, g, b) 3차원 좌표로 치환  
- ex) 8bit Red (255, 0, 0)  
  
- scalar (x)  
    vector 2 (x, y)  
    vector 3 (x, y, z)  
    vector 4 (x, y, z, w) (r, g, b, a)  
    integer 0, 1, 2, 3, 4 ••• n
    floating point 0.1, 2.35 •••  
    string "a", "abc", "2D", "Digital", "Compositing" •••  
    boolean 0, 1 off/on  


- Color Gamut (색재현율, 색영역)  
    원본의 색상을 화면 상에서 어느 정도 표현할 수 있는지 수치화 (다양성)  
    기기 차이 있음  
    상영 될 매체에 따라 색상 보정  
    *현재 업계 표준: ACES  

![](https://www.viewsonic.com/library/wp-content/uploads/2019/04/LB0055-2-compressed-1024x576.jpg)  
    
<https://news.samsungdisplay.com/18197/>  
<https://color.viewsonic.com/explore/content/Color-gamut_6.html>  
<https://www.viewsonic.com/library/photography/what-is-color-gamut/>  
