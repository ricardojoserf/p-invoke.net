## SHSetUnreadMailCount

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHSetUnreadMailCount(
   string pszMailAddress,
   int iCount,
   string pszShellExecuteCommand,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shsetunreadmailcountw)
