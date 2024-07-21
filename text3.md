# 【問題】程式生成
```
請幫我完成9*9乘法表的C程式設計
```

## C語言
```
#include <stdio.h>

int main() {
    for (int i = 1; i <= 9; i++) {
        for (int j = 1; j <= 9; j++) {
            printf("%d x %d = %2d   ", i, j, i * j);
        }
        printf("\n");
    }
    return 0;
}

```
## C++語言
```
#include <iostream>
using namespace std;

int main() {
    for (int i = 1; i <= 9; i++) {
        for (int j = 1; j <= 9; j++) {
            cout << i << " x " << j << " = " << i * j << "   ";
        }
        cout << endl;
    }
    return 0;
}

```
