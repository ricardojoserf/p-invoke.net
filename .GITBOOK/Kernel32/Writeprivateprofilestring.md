## Writeprivateprofilestring

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WritePrivateProfileString(string lpAppName,
   string lpKeyName,
   string lpString,
   string lpFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-writeprivateprofilestringw)
