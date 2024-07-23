# GitHub Desktop 가이드: Stash, Branch, Build

이 가이드는 GitHub Desktop을 사용하여 stash, branch, 그리고 build 작업을 수행하는 방법을 설명합니다.

## Stash

Stash는 작업 중인 변경사항을 임시로 저장하는 기능입니다.

1. 변경사항 스태시하기:
   - 변경사항이 있는 상태에서 상단 메뉴의 'Branch' -> 'Stash Changes'를 선택합니다.
   - 스태시에 대한 설명을 입력하고 'Stash Changes' 버튼을 클릭합니다.

2. 스태시 적용하기:
   - 상단 메뉴의 'Branch' -> 'Unstash Changes'를 선택합니다.
   - 적용할 스태시를 선택하고 'Restore'를 클릭합니다.

## Branch

Branch는 독립적인 작업 라인을 만들 때 사용합니다.

1. 새 브랜치 생성:
   - 현재 브랜치 이름 옆의 드롭다운 메뉴를 클릭합니다.
   - 'New Branch'를 선택하고 새 브랜치 이름을 입력합니다.

2. 브랜치 전환:
   - 브랜치 드롭다운 메뉴에서 전환할 브랜치를 선택합니다.

3. 브랜치 병합:
   - 병합할 대상 브랜치로 전환합니다.
   - 상단 메뉴의 'Branch' -> 'Merge into Current Branch'를 선택합니다.
   - 병합할 브랜치를 선택하고 'Merge'를 클릭합니다.

4. 브랜치 삭제:
   - 브랜치 드롭다운 메뉴에서 삭제할 브랜치에 마우스를 올리고 'Delete' 버튼을 클릭합니다.

## Build

GitHub Desktop은 직접적인 빌드 기능을 제공하지 않지만, 외부 빌드 도구와 연동하여 사용할 수 있습니다.

1. 외부 빌드 도구 설정:
   - 'Preferences' (macOS) 또는 'Options' (Windows)에서 'Integrations' 탭을 선택합니다.
   - 'External Editor'에서 사용할 IDE나 텍스트 에디터를 선택합니다.

2. 빌드 실행:
   - 저장소를 우클릭하고 'Open in [선택한 에디터]'를 선택합니다.
   - 에디터에서 프로젝트를 열고 빌드 명령을 실행합니다.

3. 빌드 결과 확인:
   - 빌드 후 변경된 파일은 GitHub Desktop의 'Changes' 탭에 표시됩니다.
   - 변경사항을 검토하고 필요한 경우 커밋합니다.

참고: 지속적 통합(CI) 도구를 사용하는 경우, GitHub 저장소에 푸시하면 자동으로 빌드가 트리거될 수 있습니다. 이는 GitHub Desktop에서 직접 수행되는 것이 아니라 GitHub 웹 인터페이스나 외부 CI 도구에서 확인할 수 있습니다.
