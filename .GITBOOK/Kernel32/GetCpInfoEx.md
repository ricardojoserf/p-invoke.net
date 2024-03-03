## GetCpInfoEx

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCPInfoEx(string CodePage,
   uint dwFlags,
   out CPINFOEX lpCPInfoEx
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getcpinfoexw)
