## GetPrivateProfileSection

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetPrivateProfileSection(
   string lpAppName,
   IntPtr lpReturnedString,
   uint nSize,
   string lpFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getprivateprofilesectionw)
