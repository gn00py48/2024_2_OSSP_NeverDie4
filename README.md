# 2024_2_OSSP_NeverDie4_Frontend
동국대학교 2024-2 공개 SW 프로젝트 : CSC4004-02(JHR) 4조 불사조(NeverDie4) 팀 레포지토리입니다.

## 팀원
- 신재용 (AI융합학과, 202211@@@@) : 팀장, BE
- 강근우 (컴퓨터공학과, 2022112097) : 디자인, FE
- 김경섭 (컴퓨터공학과, 202211@@@@) : FE
- 김민성 (AI융합학과, 202211@@@@) : BE
- 이건민 (컴퓨터공학과, 202011@@@@) : BE

## 깃허브 컨벤션 (Frontend)
강근우: KGW  
김경섭: KGS  

<✨ 기본 워크플로우>  
: 각자가 자신의 브랜치에서 작업한 후에 'main' 브랜치로 병합하는 방식을 사용할겁니다.

1. 각자 브랜치에서 작업
2. 브랜치 업데이트 및 커밋
3. 브랜치 푸시
4. 병합 전 main 브랜치 업데이트
5. 병합
6. 병합 결과 푸시

### 명령어 예시
#### 브랜치에서 작업
```
git checkout KGW
# 작업 수행 (코드 작성, 파일 수정 등)

git add .
git commit -m "작업 내용 설명"
git push origin KGW
```

#### 병합하기 전에 main 업데이트 및 병합
```
git checkout main
git pull origin main
git merge KGW

# 충돌이 발생한 경우 파일을 수정하고 병합편집기 사용
git add .
git commit -m "충돌 해결"
git push origin main
```

### 명령어 요약 (순서대로)
```
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
```

<✨ ChatGPT가 알려주는 병합 충돌 방지 및 해결>  
작업을 자주 푸시하고 병합하기: 각자 작업 내용을 자주 푸시하고 main 브랜치의 최신 내용을 자신의 브랜치에 자주 병합하는 것이 좋습니다. 이렇게 하면 충돌을 더 작은 단위로 해결할 수 있습니다.

---

## 커밋 규칙 (Commit Convention)

| 커밋 유형      | 설명                                       |
|----------------|--------------------------------------------|
| feat           | 새로운 기능 추가                           |
| fix            | 버그 수정                                  |
| docs           | 문서 수정                                  |
| style          | 코드 formatting, 세미콜론 누락, 코드 변경 없음  |
| refactor       | 코드 리팩토링                              |
| test           | 테스트 코드 추가                           |
| chore          | 패키지 매니저 수정, 기타 수정              |
| design         | 사용자 UI 디자인 변경                      |
| comment        | 주석 추가 및 변경                          |
| rename         | 파일 또는 폴더 명 수정 또는 이동           |
| remove         | 파일 삭제 작업                             |
| !BREAKING CHANGE | 큰 API 변경                              |
| !HOTFIX        | 급하게 치명적인 버그 수정                  |

--------------------------------------------------------------
