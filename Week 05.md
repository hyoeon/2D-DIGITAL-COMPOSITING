__1. Chroma Key__  
- Chroma Key: Key가 되는 색상을 이용해 alpha 추출  
- Keyers: Chroma Screen을 alpha로 바꿔주는 기능  
- Dispill: spill 없애기  

- Why?  
Roto 이전의 기능 (필름에서는 쓸 수 없음)  
Matte 추출하기 위함   
Green을 쓰는 이유  
① 적은 양의 빛도 ok  
② 더 밝게 표현  
③ 야외 촬영 ok  
④ 의상  

- Chroma Key Lighting  
그림자 지지 않게  
조명 고르게 (적어도 촬영되는 부분 만큼은 배경이 고르게 쳐져 있도록)  
그림자는 공중x, 상이 맺힐 때만 보임  

__2. NUKE Keying__  
Utility  (B/G 뿐만 아니라 RGB, Luminance까지)  
- Keyer1
RGB 뿐만 아니라 luminance  
간단하게 배경과 오브젝트 분리  
- Hue Keyer  
지정한 색상 영역을 alpha로 뺌  
- Difference  
Input A - B 차이를 alpha로  


(B/G) Screen  
- Keylight  
- Ultimatte  
- Primatte  
- IBKGizmo  
- Chroma Keyer  


디벨롭 예정
https://learn.foundry.com/nuke/content/reference_guide/keyer_nodes/keyer_nodes.html
