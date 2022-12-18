# 난수 생성
## rand
랜덤한 숫자를 반환한다.
헤더파일 stdlib.h에 매크로로 작성되어있는 [0~RAND_MAX] 사이의 값을 반환한다. RAND_MAX = 32767
rand() 함수는 프로그램이 생성될때 딱 값이 정해지므로 프로그램을 여러번 실행시켜도 동일한 값이 나온다.

ex)
int random_num = rand();

## srand
헤더 파일 : <stdlib.h>
srand 함수는 seed 값을 이용해서 rand 함수의 결과값이 변할 수 있게 만들어 준다.

ex)
srand(seed);
int random_num = rand();

## time
헤더 파일 : <time.h>
UCT 기준 1970년 1월 1일 0시 0분 0초 부터 경과된 시간을 초(sec)로 반환하는 함수.

## rand, srand, time
rand, srand, time을 이용하려 핸덤한 배열을 만들어 보자.
