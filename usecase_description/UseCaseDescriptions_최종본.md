### Use Case Description: 로그아웃

| Actor Action | System Response |
| --- | --- |
|  | 1. 로그아웃 화면을 출력한다. |
| 1. 회원 혹은 관리자가 로그아웃 버튼을 누른다. |  |
|  | 3. 로그아웃 완료 메시지를 출력하고 메인 페이지로 이동한다. |

Alternative Courses  
None.

---

### Use Case Description: 설문 검색

| Actor Action | System Response |
| --- | --- |
|  | 1. 설문 검색 화면을 출력한다. |
| 2. 회원이 현재 진행 중인 설문 리스트, 향후 진행 예정인 설문 리스트, 종료된 설문 리스트 중 하나를 선택 후 검색 키워드를 입력하고 검색버튼을 클릭한다. |  |
|  | 3. 검색 조건에 맞는 설문 리스트를 출력한다. |

Alternative Courses  
Step 3. 검색 키워드를 입력하지 않은 경우 검색어를 입력하라는 메시지를 출력한다.  
Step 3. 검색된 설문이 없는 경우 빈 검색 결과 화면을 출력한다.

---

### Use Case Description: 회원가입

| Actor Action | System Response |
| --- | --- |
|  | 1. 회원가입 화면을 출력한다. |
| 2. 입력정보(ID, 비밀번호, 전화번호, 이메일, 이름 등)를 입력하고 회원가입 버튼을 누른다. |  |
|  | 3. 회원가입 완료 메시지를 출력한다. |

Alternative Courses  
Step 3. ID, 전화번호, 이메일 중복으로 인한 회원가입 완료 실패 메시지를 출력한다.

---

### Use Case Description: 로그인 

| Actor Action | System Response |
|  --- | --- |
|  | 1. 로그인 화면을 출력한다.|
| 2. 입력정보(ID, 비밀번호)를 입력하고 로그인 버튼을 누른다. |  |
|  | 3. 로그인이 완료되었음을 알리고 메인 페이지로 이동한다.|

Alternative Courses  
Step 3. 로그인 정보가 일치하지 않는다면, 로그인 정보가 틀렸다는 메세지를 출력한다.

---

### Use Case Description: 회원 탈퇴 

| Actor Action | System Response |
| --- | --- |
|  | 1. 회원 탈퇴 화면을 출력한다.|
| 2. 회원탈퇴 버튼을 누른다. |  |
|  | 3. 회원 탈퇴를 확인하는 메세지를 제공한다. |

Alternative Courses  
None.

---

### Use Case Description: 설문 등록

|  Actor Action | System Response |
| --- | --- |
|  | 1. 설문 등록 화면을 출력한다.|
|  2. 설문 제목, 설문 설명, 문항 정보, 응답 정보, 시작 시각, 종료시각을 입력한 후에 설문 등록 버튼을 누른다. |  |
|  | 3. 설문 등록을 확인하는 메세지를 출력한다. |

Alternative Courses   
Step 3. 입력되지 않은 정보가 있다면, 해당 정보를 입력하라는 메세지를 출력한다.

---

### Use case description: 설문 상세정보 조회

| Actor Action | System Response |
| --- | --- |
|  | 1. 설문 검색 조건에 맞는 설문 리스트를 화면에 표시한다. |
| 2. 회원이 리스트에서 특정 설문을 선택한다. |  |
|  | 3. 선택된 설문의 상세 정보(제목, 설명, 문항, 응답 항목, 시작 시각, 마감 시각 등)와 진행 상태에 따른 활성화된 응답 버튼을 화면에 제공한다. |

Alternative Courses
<br />
Step 3. 진행 중인 설문이 아닌 경우 응답 버튼을 비활성화하여 화면에 제공한다.

---

### Use case description: 설문 리스트 조회

| Actor Action | System Response |
| --- | --- |
|  | 1. 현재 등록된 모든 설문의 리스트를 화면에 출력한다. |

Extensions
<br />
Step 1 이후, 관리자가 특정 설문 항목을 선택하면 해당 설문의 상세 내용을 팝업창으로 제시한다.
<br />
Step 1 이후, 관리자가 삭제 버튼을 누르면 해당 설문을 목록에서 제외하고 갱신된 리스트를 출력한다.

---

### Use case description: 설문 응답 통계 정보 조회

| Actor Action | System Response |
| --- | --- |
|  | 1. 통계 조회를 위한 기간 선택 옵션(1주일, 1개월, 1년)을 화면에 출력한다. |
| 2. 관리자가 원하는 검색 단위를 선택한다. |  |
|  | 3. 선택한 기간에 해당하는 전체 설문 수, 종료된 설문 수, 총 응답 수 정보를 출력한다. |

Alternative Courses
<br />
None.

---

### Use Case Description: 설문 응답

| Actor Action | System Response |
| --- | --- |
|  | 1. 설문 상세정보 조회 화면에서 현재 진행 중인 설문에 한해 응답 버튼을 활성화하여 표시한다. |
| 2. 응답 버튼을 누른다. |  |
|  | 3. 응답 화면으로 이동하여 설문 문항과 응답 항목을 표시한다. |
| 4. 설문에 응답한 후, 응답 버튼을 눌러 완료한다. |  |
|  | 5. 응답 완료 메시지를 표시한다. |

Alternative Courses
<br />
Step 1. 진행 중이 아닌 설문인 경우 응답 버튼이 비활성화되어 응답할 수 없다.

---

### Use Case Description: 응답한 설문 조회

| Actor Action | System Response |
| --- | --- |
| | 1. 회원이 응답한 모든 설문 목록을 한 화면에 표시한다. 각 항목에는 설문 제목, 응답 내용, 응답 일시가 있으며, 진행 중인 설문에 대해 수정과 취소 버튼이 활성화된다. |

Extensions
<br />
Step 1 이후, 회원은 현재 진행 중인 설문에 한해 취소 버튼을 눌러 응답을 취소할 수 있다.

---

### Use Case Description: 응답한 설문 수정

| Actor Action | System Response |
| --- | --- |
|  | 1. 응답한 설문 조회 화면에서 현재 진행 중인 설문에 한해 수정 버튼을 활성화하여 표시한다. |
| 2. 수정할 설문의 수정 버튼을 누른다. |  |
|  | 3. 응답 수정 화면으로 이동하여 기존 응답 내용과 가장 최근 수정 날짜를 표시한다. |
| 4. 응답 항목을 수정한 후, 수정버튼을 눌러 완료한다. |  |
|  | 5. 수정 완료 메시지를 표시한다. |

Alternative Courses
<br />
Step 1. 종료된 설문인 경우 수정 버튼이 비활성화되어 수정할 수 없다.
