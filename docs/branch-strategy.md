# 🌿 Branch Strategy

## 🏷 Main Branches

- `main`: 최종 배포 브랜치 및 문서 관리 브랜치
- `develop`: 기능 개발 통합 브랜치 (서비스 코드 중심)

## 🧪 Working Branches

### 🚀 feature/*
- 새로운 기능 개발 시 사용
- `from`: `develop` → `to`: `develop`
- 예: `feature/login-api`

### 🐞 fix/*
- 버그 수정 시 사용
- `from`: `develop` → `to`: `develop`
- 예: `fix/signup-validation`

## 🔁 Merge Rule

- **Pull Request 필수**
- 코드 및 문서 리뷰 후 병합
- 머지 방식: **Squash and Merge**

## 🧾 Branch Naming Convention

- **소문자**와 **하이픈(`-`)** 사용
- 브랜치 유형 접두사로 시작:
  - `feature/`
  - `fix/`
