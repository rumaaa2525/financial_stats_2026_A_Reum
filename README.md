# financial_stats_2026_A_Reum

이 저장소는 금융통계 수업용으로 수집-분석-보고서-시각화를 GitHub에서 관리하기 위한 개인 저장소입니다. 각 학생은 자신의 저장소를 소유하며, 공용 코드 공유는 권장되지 않습니다. 필요 시 포트폴리오로 활용 가능한 공개 저장소로 운영합니다.

목적
- 수집 데이터: data/제조/YYYY-MM-DD.csv 형식으로 저장
- 원본 원문: raw_html/YYYY-MM-DD.html 형식으로 보관
- 분석/렌더링 스크립트: scripts/
- 보고서/문서: reports/
- 시각화 산출물: figures/
- 자동화 워크플로우: .github/workflows/

초기 구조 개요
- data/제조/YYYY-MM-DD.csv
- raw_html/YYYY-MM-DD.html
- scripts/
- reports/
- figures/
- .github/workflows/
- README.md
- CHANGELOG.md (향후 변경 이력 관리)
- requirements.txt (파이썬 패키지 의존성 예: pandas, plotly)

사용 방법 (간단)
1) 로컬에 저장소를 클론합니다.
   git clone https://github.com/rumaaa2525/financial_stats_2026_A_Reum.git
2) 저장소 디렉토리로 이동합니다.
   cd financial_stats_2026_A_Reum
3) 기본 폴더가 이미 있다면 건너뛰고, 없으면 생성합니다.
   mkdir -p data/제조 raw_html scripts reports figures .github/workflows
4) 간단한 설명 파일과 의존성 파일을 추가합니다.
   echo "# 데이터 설명" > README.md
   echo -e "pandas\nplotly" > requirements.txt
5) 첫 커밋을 만듭니다.
   git add .
   git commit -m "Initialize project: folders + README + requirements"
6) 원격 main 브랜치에 푸시합니다.
   git push origin main
