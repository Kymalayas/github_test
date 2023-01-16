# github_test
dev lecture for github
# QA 시트
https://docs.google.com/spreadsheets/d/1ahTK4ElXIb9wi9s34bxyJF0toZKNR9KZJ9zs0aFbKfI/edit#gid=0
# CBS Mass Frontend

기관회원 로그인 후 교육 생성
일반 회원의 교육 보기
# Staging Server
Staging server deployed with Cloudflare Pages. Every push to `main` branch is deployed to `https://cbs-mass.pages.dev`. Staging frontend talks to the staging backend at `https://cbs-m-bnd.tetrasignum.com` deployed to the AWS EC2 instance. DNS records managed by [name.com](https://name.com)

# 할 일

- aside accordian 만들기

## 성빈

- 왼쪽 좁을때 왼쪽방향 말풍선 만들어야함

## 동인

- [x] 반려회원에서 그룹설정 버튼 빼기
- [x] 그룹 관리 페이지 api 연동
- [x] 그룹 추가 기능 구현
- [x] 그룹 설정 기능 붙이기
- [x] 검색 기능 구현
- [x] 정렬 가지고 있는 데이터로 필터링
- [x] 그룹 상세페이지 퍼블리싱 및 api 연동
# Requirements
* node version 16

# figma 주소

https://www.figma.com/file/OgY9Kfw8sUCEwOwsB9HYcx/CBS-MASS-WEB-(share)
kled@kakao.com / tjdqls1!

kled@kakao.com
tjdqls1!

# api 문서

https://tetrasignum.dooray.com/project/3003666259951696998/3080628766803817676
seongbin
tjdqls1!

# api google sheet

https://docs.google.com/spreadsheets/d/1vMsoxo7zP1FWLAPOA4hZW7yE85JvE3IRl7NCjQ37i_w/edit#gid=1130741576

# db

mysql
주소: 3.36.57.230/3306
계정: cbs/CbsmassPWD!@#


# 계정

tester44_user1/qwe123
tester44/qwe123

# 디자인피드백
https://www.figma.com/file/SG2lYKZCcAMCqPX9ZSBFiT/CBS-MASS-feedback?node-id=401%3A29

psbinn@naver.com / tjdqls1!

# 할 일
- 예약 취소 관리 디자인은 없는지? 예전에 화면 흐름 관해서 설명 한번 에이미님이 해주셨던 거 같은데 다시 한번 해주실 수 있으실까요?
- ADMIN - reservation 2-2 예약 취소, 예약 추가 디자인은 없는지? api 도 현재 없는것은로 확인되는데 일단 넘어가면 되는 부분인지?
- 기획, 디자인 상으로 get_reservation_detail 에 취소자도 닮겨야 할 것 같습니다, 예약 상세 조회의 역할을 하는 api가 필요합니다.
- 기획, 디자인 상으로 교육 삭제가 있는데 api 교육 삭제가 있는지?
- 교육 장소 관리 디자인은 없는지?
- 교육 결과 상제 api 가 있는지? 디자인 상으로 ADMIN - result page 1-1 에 해당되는 내용
- 정기 교육 생성 시 교육 시간을 두시간으로 정하면 교육이 2시간묶으로 내려와야 할 것 같습니다.
- (당일)교육 생성 시 launch_time 을 설정 안하도록 되어있는데 이렇게 되면 에러가 발생하는 듯 합니다. 일반 교육 생성이 가능하도록 수정 부탁드립니다.


# fix
- user result


tester1
tester1!


tester1_user2
tester1_user2!
