## Writeprivateprofilesection

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WritePrivateProfileSection(string lpAppName,
   string lpString,
   string lpFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-writeprivateprofilesectionw)
