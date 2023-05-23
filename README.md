# 리눅스 top 명령어
__-top [옵션] 으로 입력해 출력한다__

-b : 배치모드로 정보를 출력한다. 실시간 상화 대화형모드로 정보를 화면에 일렬로 출력한다.  
-d delay : 지정한 시간(delay 초)의 간격으로 정보를 업데이트하여 출력한다.  
-i idle : 토글값이 off일 때, idle 프로세스나 좀비 프로세스 정보를 출력하지 않는다.  
-n num : 지정한 시간(num)만큼 업데이트 정보를 출력한다.  
-p pid : 지정한 프로세스 ID(pid)의 정보만을 출력한다.  
-q : 시간의 간격 없이 계속하여 업데이트 정보를 출력한다.  
-s : 몇 개의 대화식 명령을 비활성화한다(시큐어 모드).  
-S : 누적된 정보를 출력한다(cumulative 모드).  

__top 단축키 명령어__
| 명령어 | 설명 |
|-----------|:----------:|
|`space`|정보를 업데이트 한다.|
|`^L`|스크린을 다시 초기화한다.|
|`F&f`|필드를 추가나 제거한다./ 확인하고자 하는 항목의 알파벳을 누를 때마다 선택/취소가 반복된다.|
|`O&o`|출력하는 필드의 정렬 순서를 변경한다./ 대문자로 선택한 항목을 누르면 왼쪽으로 이동하고 소문자를 누르면 오른쪽으로 이동한다.|
|`h&?`|사용 가능한 명령어를 출력한다.|
|`k`|프로세스를 종료시킨다.|
|`n&#`|출력할 프로세스의 수를 지정한다.|
|`s`|출력할 정보의 업데이트 시간을 지정한다.|
|`W`|~/.toprc에 설정된 내용을 저장한다.|
|`q`|top을 종료한다.|
