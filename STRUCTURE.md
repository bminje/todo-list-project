# STRUCTURE

## Objects
- **Task**: 할 일 항목 객체
  - 속성: id, title, completed

## Procedures
- **initialize_app**: 애플리케이션 초기화 절차
  - 설명: 앱을 초기화하고 초기 데이터를 로드합니다.

## Functions

### 팀장 (관리자)
1. **view_tasks**: 할 일 목록 보기 기능
   - 설명: 사용자에게 전체 할 일 목록을 표시합니다. 서버에서 데이터를 불러와 프론트엔드에 표시합니다.

### 팀원 1
1. **add_task**: 할 일 추가 기능
   - 설명: 사용자가 새로운 할 일을 추가하고 서버에 저장한 후 프론트엔드에 업데이트합니다.
   
2. **delete_task**: 할 일 삭제 기능
   - 설명: 사용자가 특정 할 일을 삭제하고 데이터를 업데이트합니다.

### 팀원 2
1. **edit_task**: 할 일 수정 기능
   - 설명: 사용자가 기존 할 일을 수정하고, 수정된 내용을 서버에 저장하고 프론트엔드에 업데이트합니다.

2. **complete_task**: 할 일 완료 표시 기능
   - 설명: 사용자가 할 일의 완료 여부를 표시하고, 완료된 할 일을 체크하여 데이터를 업데이트합니다.

### 팀원 3
1. **filter_tasks**: 할 일 필터링 기능
   - 설명: 완료된 할 일과 미완료된 할 일을 필터링하고, 필터 옵션을 제공하여 사용자가 원하는 할 일만 볼 수 있도록 합니다.

2. **search_tasks**: 할 일 검색 기능
   - 설명: 사용자가 할 일 목록에서 특정 할 일을 검색하고, 키워드를 입력하여 일치하는 할 일을 검색하여 표시합니다.