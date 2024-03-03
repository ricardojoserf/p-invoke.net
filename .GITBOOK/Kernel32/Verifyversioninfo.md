## Verifyversioninfo

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool VerifyVersionInfo([In] ref OSVERSIONINFOEX lpVersionInfo,
   uint dwTypeMask,
   ulong dwlConditionMask
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-verifyversioninfow)
