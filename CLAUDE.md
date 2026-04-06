# Figma → Code 프로젝트

## 기술 스택
- React 19 + TypeScript 5
- Tailwind CSS v4 (utility-first)
- Vitest + React Testing Library
- pnpm (npm, yarn 사용 금지)

## 코딩 규칙
- 컴포넌트는 `src/components/{FeatureName}/` 폴더에 생성
- 파일명: PascalCase.tsx
- props 인터페이스는 컴포넌트 이름 + Props (예: ButtonProps)

## 금지 사항
- inline style 직접 작성 금지 (Tailwind 클래스 사용)
- any 타입 사용 금지
- console.log 커밋 금지

## 자주 쓰는 명령어
- `pnpm dev` — 개발 서버
- `pnpm test` — 테스트 실행
- `pnpm build` — 프로덕션 빌드

## Figma 관련
- Figma MCP 연결됨 (figma-mcp 설정 참조)
- 디자인 토큰은 `App.css` 에서 관리
- 컴포넌트 추출 시 항상 접근성(aria) 속성 포함