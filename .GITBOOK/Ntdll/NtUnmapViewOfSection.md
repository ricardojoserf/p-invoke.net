## NtUnmapViewOfSection

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtUnmapViewOfSection(
   IntPtr ProcessHandle,
   IntPtr BaseAddress
);
```

Microsoft documentation: [Link](https://ntdoc.m417z.com/ntunmapviewofsection)
