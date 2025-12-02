# ReverseShell
Stealth windows x64 HTTPS reverse shell

# 项目构想
纯汇编实现 HTTPS反弹shell

我自己的项目GalaxyGate 实现栈欺骗 间接系统调用

[NtSocket](https://github.com/A-Normal-User/NtSocket_NtClient_NtServer)只调用Native API 实现HTTPS连接

[No-Consolation](https://github.com/fortra/No-Consolation)实现内存中内联执行cmd.exe

但是从文件系统读cmd.exe容易被安全软件注意 要不然就远程拉取

或者 拆出meterpreter的shell

理论可行 工程量很大
