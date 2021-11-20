쉘 스크립트 관련

getopt 명령어를 사용하는 이유는

1. 다양한 입력 값이 존재할 경우 사용자와 개발자의 편의를 보장하기 위함 이고
2. 스크립트를 보다 체계적으로 관리할 수 있기 때문입니다.

getopts 명령어: 명령행 인수를 처리하고 유효한 옵션을 검사합니다.

구문
getopts OptionString Name [ Argument ...]

설명
getopts 명령은 매개변수 리스트에서 옵션 및 옵션 인수를 검색하는 Korn/POSIX 쉘 내장 명령입니다. 옵션은 +(더하기 부호) 또는 -(빼기 부호)로 시작하고 그 뒤에 문자가 옵니다. + 또는 -로 시작하지 않는 옵션은 OptionString을 종료합니다. getopts 명령은 호출될 때마다 Name의 다음 옵션 값과 쉘 변수 OPTIND에서 처리될 다음 인수의 색인을 배치합니다. 쉘이 호출될 때마다 OPTIND는 1로 초기화됩니다. 옵션이 +로 시작되는 경우 +는 Name의 값 앞에 추가됩니다.

sed 명령어

sed는 Stream Editor의 약자로 sed라는 명령어로 원본 텍스트 파일을 편집하는 유용한 명령어입니다.

1. vi처럼 실시간 편집이 아닙니다.
2. 원본을 건드리지 않고 편집

awk 명령어

awk는 파일로부터 레코드(record)를 선택하고, 선택된 레코드에 포함된 값을 조작하거나 데이터화하는 것을 목적으로 사용하는 프로그램입니다. 즉, awk 명령의 입력으로 지정된 파일로부터 데이터를 분류한 다음, 분류된 텍스트 데이터를 바탕으로 패턴 매칭 여부를 검사하거나 데이터 조작 및 연산 등의 액션을 수행하고, 그 결과를 출력하는 기능을 수행합니다.
