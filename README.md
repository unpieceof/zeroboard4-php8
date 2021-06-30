# zeroboard4-php8
제로보드4 pl9 UTF-8(zb4pl9.utf8.zip) 버전에 PHP8 호환 작업을 하였습니다.

## 패치내용
- [x] PHP8 환경에서의 정상 작동 보장
- [x] 기초적인 보안 취약점 패치
- [x] [CloudFlare CDN 관련 문제점 패치](https://gist.github.com/kijin/25be59ac4b0d7c5ef722)
- [x] 게시판 스킨에서 memo_on.swf 외에 memo_on.mp3 파일도 사용 할 수 있도록 변경
- [x] 관리자 페이지의 "DB 상태 보기"메뉴 클릭 시 비밀번호 해시 길이를 41자까지 사용 할 수 있도록 자동 패치
- [ ] 심화 보안 취약점 패치
- [ ] PHP8 이상에서 나타나는 정의되지 않은 변수 관련 Warning 제거

## 테스트 환경
* Apache 2.4.48
* nginx 1.20.1
* PHP 8.0.7
* MariaDB 10.4.19

## 유의사항
본 프로젝트를 이용해서 일어나는 일에 대한 책임은 전적으로 이용자 본인에게 있습니다.
