## ShellExecuteEx

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern bool ShellExecuteEx(
   ref SHELLEXECUTEINFO lpExecInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shellexecuteexw)
