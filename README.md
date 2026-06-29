# coffee-chat-portfolio
# 프로젝트: 커피챗 플랫폼 (Coffee Chat)

## 🔗 Repository Links
- **Frontend Repository:** [프론트엔드 깃허브 주소]
- **Backend Repository:** [백엔드 깃허브 주소]

## 💡 프로젝트 소개
사용자들이 실시간으로 커피챗을 예약하고 안정적으로 매칭되어 소통할 수 있는 플랫폼입니다. 클라이언트와 서버가 독립적으로 구동되는 아키텍처로 설계되었습니다.

## 💻 Frontend 구현 (React + Vite)
- Vite를 활용한 고성능 HMR(Hot Module Replacement) 환경 구축 및 빠른 개발 사이클 확보
- 효율적인 개발 흐름을 위한 ESLint 정적 분석 및 React 템플릿 최적화
- 사용자 경험(UX)을 고려한 맞춤형 매칭 UI 및 반응형 웹 디자인 구현

## ⚙️ Backend 구현 (Python + Docker)
- **예약 및 노쇼(No-Show) 관리:** apscheduler를 활용하여 예약 시간에 맞춘 백그라운드 스케줄링 및 노쇼 자동 처리 시스템 구축
- **컨테이너 기반 환경:** Docker를 도입하여 개발 및 운영 환경의 일관성을 유지하고 안정적인 서버 구동 환경 구성

## 🔧 주요 트러블슈팅 및 기술적 의사결정
- **스케줄러 작동 최적화:** 백그라운드 작업 실행 시 지속해서 발생하던 경고성 스케줄러 로그를 정밀 분석하고 제어하여 시스템의 안정성 확보
- **의존성 및 빌드 최적화:** pipreqs를 사용해 필요한 패키지만 정밀 스캔하여 requirements.txt를 체계적으로 관리. 이를 통해 도커 컨테이너 빌드 크기를 줄이고 배포 안정성 향상
