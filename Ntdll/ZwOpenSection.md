## ZwOpenSection

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int ZwOpenSection(
   out IntPtr SectionHandle,
   uint DesiredAccess,
   IntPtr ObjectAttributes
);
```

Microsoft documentation: (TODO)
