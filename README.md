# 강동연 - Backend Developer Portfolio

백엔드 개발자 강동연의 포트폴리오 웹사이트입니다.

## 📋 프로젝트 소개

Spring Boot를 활용한 안정적이고 유지보수 가능한 백엔드 시스템 구현 경험과 주요 프로젝트를 소개하는 포트폴리오 웹사이트입니다.

## 🚀 주요 기능 (MockStalk 프로젝트)

### 백엔드 기능
- **실시간 주식 시세 기반 모의투자**: 실시간 시세 데이터를 활용한 모의투자 플랫폼
- **JWT 기반 인증 시스템**: Spring Security와 JWT를 활용한 안전한 사용자 인증
- **관심종목 관리**: 사용자별 관심 종목 등록, 조회, 삭제 기능
- **Redis 블랙리스트**: 로그아웃 시 토큰 무효화를 위한 Redis 기반 블랙리스트 구현
- **HttpOnly Cookie**: XSS 공격 방어를 위한 RefreshToken 안전 저장
- **AWS CI/CD 파이프라인**: GitHub Actions를 통한 자동 빌드 및 배포
- **Zero-Downtime 배포**: ECS 롤링 업데이트를 통한 무중단 배포

## 🛠️ 기술 스택 (MockStalk 프로젝트)

### Backend
- **Java, Spring Boot**: 백엔드 프레임워크
- **Spring Security**: 보안 및 인증 처리
- **JWT**: 토큰 기반 인증

### Database
- **MySQL**: 관계형 데이터베이스
- **Redis**: 인메모리 데이터베이스 (세션, 토큰 저장)

### Frontend
- **React**: 프론트엔드 프레임워크

### DevOps & Infrastructure
- **Docker**: 컨테이너화
- **GitHub Actions**: CI/CD 자동화
- **AWS ECS**: 컨테이너 오케스트레이션
- **RabbitMQ**: 메시지 브로커

### Testing
- **JUnit**: 단위 테스트
- **Postman**: API 테스트

### Tools
- **IntelliJ IDEA**: 개발 IDE
- **Git, GitHub**: 버전 관리
- **Notion, Slack**: 협업 도구


## 📄 섹션 구성

1. **Hero Section**: 소개 및 타이핑 애니메이션
2. **Experience**: 경력 사항 타임라인
3. **Project**: MockStalk 프로젝트 상세
   - 시스템 아키텍처
   - ERD
4. **Tech Stack**: 사용 기술 스택
5. **Implementation & Troubleshooting**: 
   - JWT 무상태성 한계 극복 및 Redis 블랙리스트 구현
   - GitHub Actions & AWS ECS 기반 CI/CD 자동화
6. **Core Code Implementation**: 주요 코드 구현 내용
7. **AWS CI/CD Pipeline**: 배포 파이프라인 상세 설명
8. **Demo Video**: 프로젝트 시연 영상

## 🎨 주요 구현 내용

### 1. JWT 인증 및 보안
- JWT 토큰 생성 및 검증
- Redis를 활용한 RefreshToken 저장
- HttpOnly Cookie를 통한 XSS 공격 방어
- 블랙리스트를 통한 로그아웃 토큰 무효화

### 2. AWS CI/CD 파이프라인
- GitHub Actions를 통한 자동 빌드 및 배포
- Docker 이미지 빌드 및 ECR 푸시
- ECS Task Definition 및 Service 배포
- Zero-Downtime 배포 구현


## 📞 연락처

- **GitHub**: [github.com/kdongyeon](https://github.com/kdongyeon)
- **Email**: kdy169@naver.com
- **Phone**: 010-4599-2285

## 📝 라이선스

이 프로젝트는 개인 포트폴리오 목적으로 제작되었습니다.

---

© 2025 Kang Dongyeon. All rights reserved.
