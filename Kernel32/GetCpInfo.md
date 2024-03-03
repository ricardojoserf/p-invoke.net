## GetCpInfo

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCPInfo(uint CodePage,
   out CPINFO lpCPInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getcpinfo)
