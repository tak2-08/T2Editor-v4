# T2Editor v4 배포본 매니페스트

**상태: EOL (지원 종료) — 이 계열의 모든 판본**
판본 3건 · 출처 시점 2026-09-27 · 배포 API `https://dsclub.kr/api/t2editor/version/index.php?action=list`

릴리즈 노트에 실리는 배포 설명 전문을 옮긴 기록이다.

---

## 1. v4.0.0

- **상태: EOL**
- 배포일: 2025-10-07
- 저장소 표제: T2Editor 4.0.0
- 브랜치: `releases/v4.0.0` · 태그: `v4.0.0`
- ZIP: `4.0.0.zip` (1186618 bytes)
- sha256: `611629a86c2b31fe6d2946d59fdeb5c1872c5754a66e5b4c6cfea931259b3757`
- 배포 시점 유효 라이선스: **1.0.1**
- 라이선스 원본 위치: 배포본 안 `readme.txt`
- readme.txt: 포함 (sha256 `4517765689c1632b6d3b61df5416b1863ed9b0b1781d3ff3c3384393583d0c30`)
- 배포 API 원본: <https://dsclub.kr/api/t2editor/version/index.php?action=download&version=4.0.0&file=0>

### 배포 설명

```text
1. 에디터 콘텐츠 html로 내보내기 스킨 호환성 향상 (plugin/export/export_html_skin.html)
2. 라이센스 검증 방식 및 라이센스 파일 변경 (editor.lib.php, reademe.txt, License_ko.txt&License_en.txt -> Old로 이동)
*라이센스 검증을 에디터 실행 구조에 통합하여 검증 실패 시 에디터 자체가 초기화되지 않도록 변경
```

---

## 2. v4.0.1

- **상태: EOL**
- 배포일: 2025-10-08
- 저장소 표제: T2Editor 4.0.1
- 브랜치: `releases/v4.0.1` · 태그: `v4.0.1`
- ZIP: `4.0.1.zip` (1194813 bytes)
- sha256: `0f3c0cf55269abf441133d80690a241e307ba68810751b80a89ea860c28e6c76`
- 배포 시점 유효 라이선스: **1.0.1**
- 라이선스 원본 위치: 배포본 안 `readme.txt`
- readme.txt: 포함 (sha256 `73c416b52a63682e571795a302c4e0d08f74d77b6b48e4cff46715d79a3855fa`)
- 배포 API 원본: <https://dsclub.kr/api/t2editor/version/index.php?action=download&version=4.0.1&file=0>

### 배포 설명

```text
editor.lib.php의 reademe.txt 라이선스 검증 코드 강화
(무료 공개 배포 정신을 유지하기 위한 선택)
```

---

## 3. v4.0.2

- **상태: EOL**
- 배포일: 2025-10-08
- 저장소 표제: T2Editor 4.0.2
- 브랜치: `releases/v4.0.2` · 태그: `v4.0.2`
- ZIP: `4.0.2.zip` (1195773 bytes)
- sha256: `00c24278f6a3d8139faac5799395a43f5005cb9f8be07d76a3eea717f950af0a`
- 배포 시점 유효 라이선스: **1.0.1**
- 라이선스 원본 위치: 배포본 안 `readme.txt`
- readme.txt: 포함 (sha256 `6c1bcc621bf562e20eaa2ce2bc9bd01773b061a439ebf1cb3884a7cb6f178d04`)
- 배포 API 원본: <https://dsclub.kr/api/t2editor/version/index.php?action=download&version=4.0.2&file=0>

### 배포 설명

```text
이미지 업로드 시간 및 지연에 따른 이미지 블록 추가 대기시간 단축 (/plugin/image/image.js)
​*이미지 업로드 완료 후 이미지 블록을 추가하는 것에서 이미지 추가 즉시 이미지를 base64로 변환하여 이미지 블록 url로 사용, 이후 이미지 업로드 완료 시 서버에 업로드된 이미지url로 교체되도록 구현
```
