# 작물별 시비처방 자동 생성 프로그램

농가별 면적, 토양검정 값, 비료 성분, 작물과 품종을 입력해 시비처방을 계산하는 정적 웹 프로그램입니다.

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더의 파일을 저장소에 올립니다.
3. 저장소의 `Settings` > `Pages`로 이동합니다.
4. `Build and deployment`의 `Source`를 `GitHub Actions`로 선택합니다.
5. `Actions` 탭에서 `Deploy to GitHub Pages` 작업이 완료될 때까지 기다립니다.
6. 배포가 끝나면 GitHub Pages 주소로 접속합니다.

## 파일 구조

- `index.html`: GitHub Pages 첫 화면입니다. 실제 프로그램 파일로 자동 이동합니다.
- `outputs/crop-fertilizer-prescription.html`: 실제 시비처방 프로그램입니다.
- `.github/workflows/pages.yml`: GitHub Pages 자동 배포 설정입니다.
- `.nojekyll`: 정적 파일을 그대로 배포하기 위한 설정입니다.

## 참고

현재 작물별 기본 시비량은 예시 기준값입니다. 실제 운영 전에는 농촌진흥청, 흙토람, 지역 농업기술센터 기준에 맞춰 작물별 기준값을 검토해 적용하세요.
