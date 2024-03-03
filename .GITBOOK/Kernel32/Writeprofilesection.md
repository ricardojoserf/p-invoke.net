## Writeprofilesection

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteProfileSection(string lpAppName,
   string lpString
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-writeprofilesectionw)
