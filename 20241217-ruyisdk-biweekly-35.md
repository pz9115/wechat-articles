# RuyiSDK双周进展汇报  第035期·2024年12月17日

## 卷首语

## 包管理器

## IDE

## GCC

## V8
1. 移植Growable stack到RISC-V的Wasm liftoff baseline compiler和turbofan compiler
2. 修复ICache flush在多核芯片上的bug，将flush范围从local harts改为包括remo特harts
3. 移植和实现MutableInt32 to ScriptContext slots优化
4. 在正则表达式编译器中添加压栈后栈内存边界检测，加强安全性
5. 继续实现Leap tiering功能

## 操作系统支持矩阵

## SDK

基于之前的验证和测试整理 Milkv Duo 重构需求：

- [Milkv Duo 重构需求](https://gitee.com/yunxiangluo/milkv-duo/blob/master/%E9%87%8D%E6%9E%84%E9%9C%80%E6%B1%82.md)

Milkv Duo SDK todo（缺陷）持续更新：

- [Milkv Duo SDK todo](https://gitee.com/yunxiangluo/milkv-duo/blob/master/todo.md)