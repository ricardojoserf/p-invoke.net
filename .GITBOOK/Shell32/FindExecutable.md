## FindExecutable

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern uint FindExecutable(
   string lpFile,
   string lpDirectory,
   StringBuilder lpResult
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-findexecutablew)
