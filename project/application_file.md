# 환경별 파일 분리  

## `application.yml`:  
모든 환경에 적용되는 기본적인 것만 작성하기  

다 적고 다른 설정(`application-dev.yml` 등)으로 덮어씌우는 방식은 좋지 않다  
-> 덮는 것을 누락하여 운영 서버에 적용되는 일 방지  

<br>

## `application-환경이름.yml`:  
1. `application-환경이름.yml` 파일 작성
2. 인텔리제이 적용
활성화된 프로파일: `환경이름`
<img width="802" height="689" alt="image" src="https://github.com/user-attachments/assets/7e28bd74-122b-4d11-9aff-7e840a661c59" />  

<br>

<br>

## 환경변수 설정  

#### 1. `.gitignore`에 환경변수 파일 추가  
```
**/.env*   # 추가
```

#### 2. 환경변수 파일 작성  
프로젝트 root 바로 아래 `.env` 파일 생성  
_예시)_  
```
MYSQL_IP=
MYSQL_PORT=
MYSQL_DB_NAME=
MYSQL_USERNAME=
MYSQL_PASSWORD=
```

#### 3. 인텔리제이 적용  
환경변수: `환경변수 파일 위치`  
_2번 사진 참고_  



