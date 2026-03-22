# AWS First Project 🚀

> AWS EC2와 Nginx를 활용해 웹 서버를 구축하고,
> 도메인 연결 및 HTTPS 적용까지 완료한 프로젝트입니다.

---

## 📌 소개

AWS EC2를 활용하여 웹 서버를 구축하고,
Nginx를 통해 HTML 페이지를 배포한 프로젝트입니다.

---

## 🛠 사용 기술

* AWS EC2
* Linux (Amazon Linux)
* Nginx (웹 서버)
* HTML
* Let's Encrypt (SSL 인증)
* DNS (가비아)

---

## 🌐 배포 링크

* https://www.choiferriswheel.com

---

## 🚀 배포 과정

1. AWS EC2 인스턴스 생성 및 서버 환경 구축
2. Nginx 웹 서버 설치 및 HTML 페이지 배포
3. 가비아 도메인 구매 후 DNS 설정 (A 레코드 연결)
4. Let's Encrypt를 이용한 SSL 인증서 발급
5. HTTPS 적용 및 보안 연결 완료

---

## 🔒 HTTPS 적용

* Let's Encrypt를 활용하여 SSL 인증서 적용
* HTTP → HTTPS 리다이렉트 설정

---

## 💡 배운 점

* 클라우드 서버 구축 과정 이해
* 웹 서버 배포 경험
* 리눅스 명령어 활용
* 도메인(DNS) 연결 및 HTTPS 적용 경험

---

## ⚠️ 트러블슈팅

* DNS 전파 지연으로 인해 도메인 연결이 즉시 반영되지 않는 문제 발생
* Nginx 설정(server_name) 오류로 SSL 인증서 자동 적용 실패
* AWS 보안 그룹에서 HTTPS(443) 포트 미개방으로 접속 불가 문제 발생

👉 각 문제를 로그 확인 및 설정 수정으로 해결하며,
실제 서비스 환경에서의 문제 해결 경험을 쌓았습니다.

---

## 📊 결과

EC2를 통해 실제 웹페이지를 인터넷에 배포하고,
도메인 및 HTTPS를 적용하여 외부에서 안전하게 접근 가능한 환경을 구축했습니다.
