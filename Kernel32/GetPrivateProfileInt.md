## GetPrivateProfileInt

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetPrivateProfileInt(
   string lpAppName,
   string lpKeyName,
   int nDefault,
   string lpFileName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getprivateprofileintw)
