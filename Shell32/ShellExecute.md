## ShellExecute

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern IntPtr ShellExecute(
   IntPtr hwnd,
   string lpOperation,
   string lpFile,
   string lpParameters,
   string lpDirectory,
   int nShowCmd
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shellexecutew)
