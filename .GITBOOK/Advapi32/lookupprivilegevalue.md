## lookupprivilegevalue

```csharp
[DllImport("advapi32.dll", SetLastError = true)]
public static extern bool LookupPrivilegeValue(string lpSystemName,
   string lpName,
   out LUID lpLuid
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegevaluea)
