# SoftwareDebugging
CopyRight @Raymond Zhang
http://advdbg.org/books/swdbg/samples.aspx

程序名称

用途

正文

Err2Fail.exe

演示在特定条件下才表现出来的错误

1.6.1

AccKernel.exe

从用户空间访问内核空间

2.5.2

AcsVio.exe

写代码段导致非法访问异常

2.5

ProtSeg.exe

应用程序加载无效段寄存器导致异常

2.5

Fault.exe

使用结构化异常器处理除零异常后恢复程序运行

3.3.3

B2BStep.exe

分支到分支单步执行

4.3.4

HiInt3.exe

在代码中插入断点指令

4.1.1

DataBP.exe

手工设置数据断点

4.2.8

TryInt1.exe

在用户态代码中插入INT 1指令会违反保护规则

4.3.1

CpuWhere.exe

使用CPU的调试存储机制记录CPU的执行路线

5.4

Bts.sys

支持CpuWhere的驱动程序

5.4

LBR.dll

使用分支记录功能的WinDBG扩展模块

5.2.3

McaViewer.exe

读取MCA寄存器

6.3.2

Breakout.exe

试验应用程序自己调用DbgUiRemoteBreakin的效果

10.6.4

DebString

用于验证OutputDebugString API的工作原理

10.7

EvtFilter.exe

用于试验VC调试器的异常处理选项

10.5.5

HungWnd.exe

用于观察被中断到调试器后的程序窗口

10.6.9

MiniDbgee.exe

用作调试目标的简单Win32程序

10.4.2

TinyDbge.exe

用作调试目标的简单控制台程序

10.4.2

TinyDbgr.exe

使用调试API编写的简单调试器

10.4.2

SEH_Excp.exe

探索SEH的异常处理

11.4.3

SEH_Trmt.exe

探索SEH的终结处理

11.4.2

SEH_Mix.exe

嵌套使用SEH的异常处理和终结处理

11.4.6

VEH.exe

演示向量化异常处理器的用法

11.5.3

JitDbgr.exe

一个简单的JIT调试器

12.5.3

UdmpView.exe

读取和解析用户态转储文件

12.9.4

UEF.exe

触发未处理异常的控制台程序

12.1

UefWin32.exe

触发未处理异常的窗口程序

12.1

UefSndThrd.exe

在第2个线程总触发未处理异常的控制台程序

12.1

UefSrvc.exe

触发未处理异常的系统服务程序

12.1

UefCSharp.exe

触发未处理异常的.Net程序

12.1

UefSilent.exe

不显示应用程序错误对话框

12.4

ErrorMode.exe

观察SetErrorMode API的效果

13.6.1

HiCLFS.exe

使用CLFS API创建日志文件和读写日志记录

15.6

Crimson.exe

演示Crimson API的用法

16.9

ETW.exe

演示使用编程方法控制NT Kernel Logger

16.7.2

RawLog.exe

不使用清单文件而直接输出日志信息

16.9

KdTalker.exe

与内核调试引擎的对话程序

18.5.7

Verifiee.exe

探索程序验证器的分析目标

19.4.1

AllcStk.exe

演示栈的创建过程和栈溢出

22.2.3

BoAttack.exe

缓冲区溢出攻击的基本原理

22.10.2

BufOvr.exe

存在缓冲区溢出错误的小程序

22.10.1

CallConv.exe

包含各种函数调用协议的小程序

22.7

CallCV64.exe

演示64位系统下的函数调用协议

22.7.6

CheckESP.exe

不遵守栈平衡原则的小程序

22.6

HiStack.exe

用于观察栈的小程序

22.3.3

LocalVar.exe

用于观察局部变量的小程序

22.4.1

SecChk.exe

演示编译器的安全检查功能

22.11

StackChk.exe

演示栈检查函数的工作原理

22.8.3

StackOver.exe

通过死循环导致栈溢出的小程序

22.8.2

StkUFlow.exe

存在栈下溢错误的小程序

22.9

MemLeak.exe

使用CRT的调试支持自动转储内存泄漏

23.15

FreCheck.exe

用于分析释放堆块时触发的堆检查

23.8.3

HeapHFC

演示Win32堆的释放检查（HFC）机制

23.6.2

HeapMfc

演示内存泄漏的MFC程序

23.7

HeapOver

演示发生在堆上的缓冲区溢出

23.8

HiHeap.exe

用来分析基本内存分配和释放操作的控制台程序

23.3

SBHeap.exe

使用CRT的小堆块堆

23.11.2

Interop.exe

用于分析在同一个程序中使用两种异常处理机制

24.7

SehComp.exe

用于分析SEH异常处理编译方法的调试目标

24.5.2

SehRaw.exe

手工注册异常处理器

24.4.1

VC8Win32.exe

用于分析异常处理有关的安全问题

24.6

HiWorld.exe

VC2005产生的典型Windows程序

25.4.1

PdbFairy.exe

直接读取PDB文件的小程序

25.6.5

Sig2Time.exe

将PDB文件中的时间戳转换为时间

25.8

SymOption.exe

试验不同的符号文件选项

25.2

SymView.exe

符号文件观察器

25.6.8

D4D.dll

演示可调试设计的DLL模块

27.4

D4dTest.exe

使用D4D.dll的测试程序

27.4

PerfView.exe

演示性能监视程序的工作原理

27.5.3

MulThrds.exe

用于演示线程控制命令的调试目标

30.13.1
