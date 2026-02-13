# Object Model  

### DTO  
데이터 교환용 객체  
getter/setter 사용  
비즈니스 로직 없음  
  
### VO  
값 자체를 표현하는 객체  
비즈니스 로직 포함  
getter만 가능  
  
### Entity  
DB에 연결되는 데이터 객체    


<br>

## 사용처  

- controller  
DTO 송수신  

- service  
DTO, VO, Entity 변환  

