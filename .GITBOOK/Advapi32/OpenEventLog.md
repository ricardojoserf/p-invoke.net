## OpenEventLog

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysUInt)]
public static extern IntPtr OpenEventLog(
   string lpUNCServerName,
   string lpSourceName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openeventloga)
