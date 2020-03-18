# README

## vscode 扩展 "win32-asm-dev"

开发中的基于masm的win32汇编语言扩展插件，计划支持
highlight，debugger，snipptes
目前已经基本实现了大部分masm伪指令和大部分x86_64系列CPU的指令集的高亮支持。
下一步计划开发自动补全功能。
配套的win32的rc资源文件编辑调试扩展工具在本插件debugger功能开始开发时进行。

目前已支持的高亮的处理器指令集
MMX,SSE,SSE2,SSE3,SSSE3,SSE4.1,SSE4.2,EM64T,VT-x,AES,AVX,AVX2,FMA3,TSX
