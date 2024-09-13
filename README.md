# 2024_2_OSSP_NeverDie4_Frontend
동국대학교 2024-2 공개 SW 프로젝트 : CSC4004-02(JHR) 4조 불사조(NeverDie4) 팀 레포지토리입니다.

## 팀원
- 신재용 (AI융합학과, 202211@@@@) : 팀장, BE
- 강근우 (컴퓨터공학과, 2022112097) : 디자인, FE
- 김경섭 (컴퓨터공학과, 202211@@@@) : FE
- 김민성 (AI융합학과, 202211@@@@) : BE
- 이건민 (컴퓨터공학과, 202011@@@@) : BE

## 2024_2_OSSP_불사조팀 깃허브 컨밴션 (Frontend)
강근우: KGW
김경섭: KGS

<✨ 기본 워크플로우>
: 각자가 자신의 브랜치에서 작업한 후에 'main' 브랜치로 병합하는 방식을 사용할겁니다.

1. 각자 브랜치에서 작업
2. 브랜치 업데이트 및 커밋
3. 브랜치 푸시
4.용)
git add .
git commit -m "충돌 해결"

git push origin main
# main 브랜치에 병합이 완료되면, 이를 원격 저장소에 푸시



<✨ 명령어 순서대로만 모음>
git checkout KGW
git add .
git commit -m "작업 내용 설명"
git push origin KGW
git checkout main
git pull origin main
git merge KGW
git add .
git commit -m "충돌 해결"
git push origin main



<✨ chat gpt가 알려주는 병합 충돌 방지 및 해결>
작업을 자주 푸시하고 병합하기: 각자 작업 내용을 자주 푸시하고 main 브랜치의 최신 내용을 자신의 브랜치에 자주 병합하는 것이 좋습니다. 이렇게 하면 충돌을 더 작은 단위로 해결할 수 있습니다.



<🚀 커밋 규칙 (Commit Convention)>
커밋 유형	설명
feat	새로운 기능 추가
fix	    버그 수정
docs	문서 수정
style	코드 formatting, 세미콜론 누락, 코드 자체의 변경이 없는 경우
refactor	코드 리팩토링
test	테스트 코드, 리팩토링 테스트 코드 추가
chore	패키지 매니저 수정, 그 외 기타 수정 ex) .gitignore
design	CSS 등 사용자 UI 디자인 변경
comment	필요한 주석 추가 및 변경
rename	파일 또는 폴더 명을 수정하거나 옮기는 작업만인 경우
remove	파일을 삭제하는 작업만 수행한 경우
!BREAKING CHANGE	커다란 API 변경의 경우
!HOTFIX	급하게 치명적인 버그를 고쳐야 하는 경우
