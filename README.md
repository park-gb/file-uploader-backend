# AWS와 React를 활용한 파일 업로드 시스템: Backend
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

## Requirement
### 1) Frontend 구축
- [파일 업로드 웹 페이지 구축: (1) React 기반 Frontend 개발](https://heytech.tistory.com/403)
- 코드: [Github](https://github.com/park-gb/file-uploader-frontend)

### 2) AWS 세팅
- [파일 업로드 웹 페이지 구축: (2) AWS IAM 역할 생성](https://heytech.tistory.com/404)
- [파일 업로드 웹 페이지 구축: (3) AWS Lambda 생성](https://heytech.tistory.com/405)
- [파일 업로드 웹 페이지 구축: (4) AWS S3 생성](https://heytech.tistory.com/406)
- [파일 업로드 웹 페이지 구축: (5) AWS API Gateway 생성](https://heytech.tistory.com/407)

### 3) Backend 코드 수정
#### (1) S3 버킷 이름 입력
- ```file-processing-service.js``` 파일 내 5번째 line에 본인이 생성한 S3 버킷 이름 입력
- [파일 업로드 웹 페이지 구축: (4) AWS S3 생성](https://heytech.tistory.com/406)

#### (2) API Gateway 리소스 이름 입력
- ```index.js``` 파일 내 3번째 line에 본인이 생성한 API Gateway 리소스 이름 입력
- [파일 업로드 웹 페이지 구축: (5) AWS API Gateway 생성](https://heytech.tistory.com/407)

## 참고자료
- 유튜브, [How to Build a File Upload System on AWS with React and a Serverless API | Lambda, S3, API Gateway](https://www.youtube.com/watch?v=IgAE-ycnb94)
