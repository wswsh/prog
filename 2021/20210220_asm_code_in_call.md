#### C++中类成员函数的汇编代码常见的如下：
```
push   %r15
push   %r14
push   %r13
push   %r12
push   %rbp
mov    %rsi,%rbp
push   %rbx
mov    %rdi,%rbx
sub    $0x138,%rsp
```
为什么要这样？先看一个简单的例子

#### c++中普通成员函数的汇编代码：
```
```