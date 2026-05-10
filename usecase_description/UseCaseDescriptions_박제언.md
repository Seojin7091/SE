Use case description: 설문 상세정보 조회

| Actor action | System response |
| --- | --- |
| 1. None | 2. 검색 조건에 맞는 설문 리스트를 화면에 표시한다. |
| 3. 리스트에서 특정 설문을 선택한다. | 4. 선택된 설문의 상세 정보(제목, 설명, 문항, 응답 항목, 시작 시각, 마감 시각 등)와 진행 상태에 따른 응답 버튼을 화면에 제공한다. |
**Alternative Courses**
*None.


Use case description: 설문 리스트 조회

| Actor action | System response |
| --- | --- |
| 1. None | 2. 현재 등록된 모든 설문의 목록을 화면에 구성하여 보여준다. |
**Extensions**
*Step 2 이후, 관리자가 특정 항목을 선택하면 해당 설문의 세부 내용을 팝업창으로 제시한다.
*Step 2 이후, 관리자가 삭제를 요청하면 해당 설문을 목록에서 제외하고 갱신된 리스트를 보여준다.


Use case description: 설문 응답 통계 정보 조회

| Actor action | System response |
| --- | --- |
| 1. None | 2. 통계 조회를 위한 기간 선택 옵션(1주일, 1개월, 1년)을 화면에 출력한다. |
| 3. 원하는 검색 단위를 선택한다. | 4. 선택한 기간에 해당하는 전체 설문 수, 종료된 설문 수, 총 응답 수 정보를 출력한다. |
**Alternative Courses**
*None.
