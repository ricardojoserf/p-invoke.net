## GetConsoleProcessList

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetConsoleProcessList(
   [Out] uint[] lpdwProcessList,
   uint dwProcessCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsoleprocesslist)
