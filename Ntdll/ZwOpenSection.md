## ZwOpenSection

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int ZwOpenSection(
   out IntPtr SectionHandle,
   uint DesiredAccess,
   IntPtr ObjectAttributes
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntopensection)
