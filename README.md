# 7_4_ex1.py
````
이중 반복문을 사용하여 아래의 출력을 할 수 있도록 하세요. 첫번째 입력값으로 앞의 수를 출력하고 두번째 입력값으로 반복적으로 첫번째 입력값을 입력값만큼 출력하시오. 
(첫번째 입력값은 1 ~ 3까지만 입력, 두번째 입력값은 3 ~ 5까지만 입력한다고 가정한다. 특별이 입력값의 제한을 구지 프로그램에 적용하지 마세요. 큰 값을 입력하면 출력라인이 너무 많아져서 제한한 것임)

[입력부분]
2
3
[출력부분] #출력형식에서 두 수는 print(x1, x2) 형태를 사용하세요. 두수 사이의 ,는 꼭 
#사용하되, x1과 x2의 형태는 변경되어도 됩니다.
0 1
0 2
0 3
1 1
1 2
1 3
````

- 2018년도 여름계절에 수강하였던 파이선 프로그래밍의 과제 문제에 대한 코드이다.

````
num1 = int(input())
num2 = int(input())

for i in range(0, num1):
    for j in range(1, num2+1):
        print(i,j)
````

- 두 수를 입력 받아 중첩 for문을 이용하여 숫자를 규칙에 맞게 반복하여 출력하도록 하였다.

* for문 : 구간을 반복하기 위하여 쓴다. 특정 조건이 완료되거나 나가는 조건이 발생하면 종료한다.
````
for i in range(5):
print(i)          -> 여기서 i의 값은 0에서 4까지, 즉 0,1,2,3,4의 값이 순서대로 들어간다.

위 예시의 결과 값
0
1
2
3
4

for i in range(1, 10, 2):
print(i)          -> 여기서 i의 값은 1에서 10까지 2씩 증가하는 수(1,3,5,7,9)를 순서대로 가진다.

위 예시의 결과 값
1
3
5
7
9
````
