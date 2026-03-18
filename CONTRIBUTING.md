# 🤝 Contributing Guide

일관된 코드 품질과 관리를 위해 아래 규칙을 준수해 주세요.

## 📝 커밋 컨벤션 (Commit Message)
기본적으로 `type: description` 형식을 사용합니다.

- `feat`: 새로운 기능 추가
- `fix`: 버그 수정
- `docs`: 문서 수정 (README, 주석 등)
- `style`: 코드 의미에 영향을 주지 않는 수정 (포맷팅, 세미콜론 등)
- `refactor`: 코드 리팩토링
- `test`: 테스트 코드 추가 및 수정
- `chore`: 빌드 업무 수정, 패키지 매니저 설정 등

**예시:** `feat: ESP32 오디오 샘플링 속도 최적화`

## 🌿 브랜치 전략 (Branching Strategy)
- `main`: 제품 배포용 최종 브랜치 **(직접 Push 금지)**
- `develop`: 개발 통합용 브랜치
- `feature/기능명`: 개별 기능 개발용 브랜치
