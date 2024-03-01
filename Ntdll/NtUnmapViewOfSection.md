## NtUnmapViewOfSection

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtUnmapViewOfSection(
   IntPtr ProcessHandle,
   IntPtr BaseAddress
);
```

Microsoft documentation: (TODO)
