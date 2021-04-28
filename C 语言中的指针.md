# C 语言中的指针

## P1 指针基本介绍

链接：https://www.bilibili.com/video/BV1bo4y1Z7xf/?spm_id_from=333.788.recommend_more_video.9

## P2 指针代码示例

```c
#include <stdio.h>
int main()
{
	int a = 10;
	int *p;
	p = &a;
	printf("Address p is %d\n",p);
	printf("Size of integer is %d bytes\n",sizeof(int));
	printf("Address p+1 is %d\n",p+1);
    return 0;
	
}
```

结果：

```
Address p is 1628469084
Size of integer is 4 bytes
Address p+1 is 1628469088
```

指针增一后将按照所指变量所占地址数往上增长