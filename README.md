# Discovery Service

## 소개

본 서비스는 JobFinder 프로젝트의 Service Discovery(Eureka Server) 역할을 담당합니다.
각 서비스(user-service, board-service, gateway)가 등록되어 서로를 탐색할 수 있도록 합니다.

---

## 역할

* 서비스 등록 및 관리
* 서비스 상태 모니터링
* 클라이언트 서비스 간 위치 정보 제공

---

## 접근 경로

```text
http://jobfinder-antaehoon.kro.kr:8761
```

---

## 참고

* 본 서비스는 MSA 구조에서 서비스 간 통신을 위한 핵심 인프라 역할을 합니다.
* 실제 비즈니스 로직은 포함되어 있지 않습니다.
