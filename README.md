# .github Repository

GitHub Organization의 **특별한 repository**입니다. <br/>
조직 전체에 공통으로 적용되는 설정과 문서를 관리합니다.


## 주요 기능

### 1. 조직 프로필 (`profile/README.md`)

`https://github.com/DoRunDoDun` 방문 시 표시되는 팀 소개 페이지

```
profile/README.md → 조직 프로필에 표시
```

### 2. 공통 커뮤니티 파일

조직의 모든 repository에 자동으로 적용됩니다. (개별 repo에 파일이 없을 경우)

| 파일 | 용도 |
|------|------|
| `CODE_OF_CONDUCT.md` | 행동 강령 |
| `CONTRIBUTING.md` | 기여 가이드 |
| `SECURITY.md` | 보안 정책 |
| `SUPPORT.md` | 지원 리소스 |

### 3. Issue/PR 템플릿

```
ISSUE_TEMPLATE/
├── bug_report.md
└── feature_request.md

PULL_REQUEST_TEMPLATE.md
```

### 4. GitHub Actions 템플릿

```
workflow-templates/
├── ci.yml
└── ci.properties.json
```


## 파일 우선순위

1. **개별 repository 파일** 우선
2. `.github` repository 파일이 기본값

예: `DoRunDoDun/project-a`에 `CONTRIBUTING.md`가 없으면 `.github/CONTRIBUTING.md`를 사용


## 참고 자료

[커뮤니티 health 파일](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) | [조직 프로필](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) | [Issue/PR 템플릿](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests)
