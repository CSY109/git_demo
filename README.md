# Hello, World! (C 语言版)

这是一个最简单的 C 语言程序，用于输出 "Hello, World!" 到控制台，是编程入门的第一个经典示例。

## 📋 代码说明
### 代码文件
- 文件名：`hello_world.c`（建议将你的 C 代码保存为这个名称，也可自定义）
- 核心功能：通过 `printf` 函数向标准输出打印 "Hello, World!" 字符串，并换行。

### 代码核心逻辑
```c
#include<stdio.h>   // 引入标准输入输出头文件，为 printf 函数提供声明
int main()          // 程序入口函数，程序从这里开始执行
{
    printf("Hello, World!\n");  // 输出字符串，\n 表示换行
    return 0;       // 程序正常结束，返回 0
}