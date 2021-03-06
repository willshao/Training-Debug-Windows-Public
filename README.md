## 准备工作、工具、环境和Demo
- 环境：
	- OS：Win7 / Win8.1 / Win10
	- IDE：VS2015 / VS2017
- 下载：[工具 & Demo](https://share.weiyun.com/5SHAbCW)
- 源码：[Github](https://github.com/wu-wenxiang/Training-Debug-Windows-Public/tree/master/src)，[下载](https://github.com/wu-wenxiang/Training-Debug-Windows-Public/archive/master.zip)

## 课程安排
- 第1天
	- Installation, Configuration & QuickStart
		- Precheck Installation
			- Python
			- VisualStudio
		- Windbg
		- Sysinternal Kit
		- How to launch a process as debug target with Windbg?
		- How to attach/detach a process with Windbg?
	- About Symbol
		- How did assemblies export their external functions?
		- What's the symbols?
		- How to config the symbol path in debugger settings?
		- How did assemblies map to their symbol files?
		- How did assemblies map to their source codes?
		- What're the differences between public & private symbol?
		- How to generate a public symbol?
		- What does the symbol path syntax mean?
		- How to build a symbol server?
		- The best practices about symbol configurations
		- What's the order when windbg search the symbols?
		- How to call a function with its symbol name from an assembly?
	- About Debugger
		- What's the differents between c call & standard call?
		- What's the basic principle of the debugger?
		- List the typical debug events
		- What's the differences between soft, hard and memory breakpoints?
		- How to implement Onlaunch debugging?
		- How to implement Attach debugging?
		- How to implement Breakpoint?
		- How to implement Hook & Injection?
	- Windbg Usage
		- How to examine the Process Information?
		- How to viewing and edit Memory?
		- How to set a Breakpoint at function entries?
		- How to set a Breakpoint target writing memory?
		- How to use debugger extensions?
		- How to use !analyze in hang / crash scenarios?
		- Why my source code could not display with !analyze -v?
		- How to find error code of a win32 api that returns false
- 第2天
	- Windbg Advanced
		- How to set a Conditional Data Breakpoint?
		- How to write a Simple Debugger Command Program?
		- How to build the SimpleLabExts Debugger Extension
		- How to write scripts by pykd, or javascript?
	- About Sysinternal tools
		- How to find which process locked the files?
		- How to release the file from the process?
		- How to check the owner about a popup window?
		- How to monitor memory/cpu/io by procexp?
		- How to check the callstack for a high cpu process?
		- How to check the strings from heap?
		- How to check the PATH environment about the process?
		- How to monitor file/registry/network/process/thread?
		- How to capture a full memory dump?
		- How to capture dumps based on conditions?
		- How to analyze dumps automatically?
	- About Graphic
		- What's the Rendering Pipeline?
		- Windows Graphic Overview
		- Comparing Direct2D and GDI Hardware Acceleration
		- Demo: Direct2D in action
		- How to improve the performance of Direct2D apps?
		- Demo Algorithm 1: reverse string
		- Demo Algorithm 2: K-Means clustering
	- About Performance Tunning
		- Performance Counters
		- ETLTrace Collecting
		- Demo: Xperf
		- Demo: GpuView
- 第3天
	- About Crash
		- How to debug Access Violations?
		- How to debug Heap Corruption?
		- How to debug Stack Corruption?
	- About Hang
		- Common hang scenarios
			- Wait for Lock
			- Wait for Web Services
			- Wait for DB
		- How to debug a Spinning Thread?
	- About Leak
		- GFlags
		- How to debug a Native Memory Leak?
		- Finding COM Leaks Using Extensions
		- VMMap
		- RAMMap
		- LeakTrack extension
	- About HighCPU
		- Live Debug with HighCPU
		- Dump Analysis with HighCPU
		- Common HighCPU scenarios
			- Regex
			- Parallel race
			- Blank loop
			- GC
- 第4天
	- About Mex
		- Demo: Mex Usage
	- About Windbg Preview
		- Time Travel Debugging Overview
	- About X64 Debug
		- Parameter Passing and Stack
		- Home Space and Optimized Code
	- About Real Case (Optional, real case from cisco also OK)
		- Demo: Crash when export certificate
		- Demo: Crash when call a function from an assembly
		- Demo: Hang with Lock / WebService / DB
		- Demo: High CPU since blank loop
		- Demo: High CPU since parallel race
		- Demo: High CPU since regex

## 专题
- [Graphic](https://github.com/wu-wenxiang/Training-Debug-Windows-Public/tree/master/doc/Graphic.md)
- [Debug](https://github.com/wu-wenxiang/Training-Debug-Windows-Public/tree/master/doc/Debug.md)
- [MediaFoundation](https://github.com/wu-wenxiang/Training-Debug-Windows-Public/blob/master/doc/MediaFoundation.md)
