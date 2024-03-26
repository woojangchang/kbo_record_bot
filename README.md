# KBO 경기결과 텔레그램 봇 만들기

## 기획
- 날짜를 전송하면 해당 날짜의 (롯데) 경기 결과를 가져옴
  - 경기 결과는 statiz 데이터를 스크랩
- 명령어에 따라 다른 결과값을 가져옴(스코어보드, 득점 장면 등)
- AWS Lambda와 API Gateway 이용
- 봇은 텔레그램 이용(무료이며 간단하다.)


## 개발 진행 상황
### 스크랩
- [x] 스코어보드
- [x] 승-패-세
- [x] 경기 Best, Worst
- [x] 득점 장면
- [ ] 타격 기록
- [ ] 투구 기록

### AWS
- [x] Lambda 생성
- [x] API Gateway 연결

### 봇
- [x] 텔레그램 봇 생성