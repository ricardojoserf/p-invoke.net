## GetPrivateProfileString

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetPrivateProfileString(
   string lpAppName,
   string lpKeyName,
   string lpDefault,
   StringBuilder lpReturnedString,
   uint nSize,
   string lpFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getprivateprofilestringw)
