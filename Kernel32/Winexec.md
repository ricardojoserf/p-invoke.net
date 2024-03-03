## Winexec

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint WinExec(string lpCmdLine,
   uint uCmdShow
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-winexec)
