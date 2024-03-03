## GetProcessImageFileName

```csharp
[DllImport("psapi.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint GetProcessImageFileName(
   IntPtr hProcess,
   StringBuilder lpImageFileName,
   uint nSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-getprocessimagefilenamea)
