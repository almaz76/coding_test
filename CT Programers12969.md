# CT-Programers12969

Class: SCP 101
Created: Jun 05, 2020 2:50 PM
Link: https://programmers.co.kr/learn/courses/30/lessons/12969
Reviewed: Yes
Type: coding

# 직사각형 별찍기

이 문제에는 표준 입력으로 두 개의 정수 n과 m이 주어집니다.
별(*) 문자를 이용해 가로의 길이가 n, 세로의 길이가 m인 직사각형 형태를 출력해보세요.

```c
#include <stdio.h>

int main(void) {
    int a;
    int b;
    scanf("%d %d", &a, &b);
    for (int i = 0; i < b; i++) {
        for (int j = 0; j < a; j++) {
            printf("*");
        }
        printf("\n");
    }
    return 0; 
}
```
