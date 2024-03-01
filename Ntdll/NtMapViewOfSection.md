## NtMapViewOfSection

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtMapViewOfSection(
   IntPtr SectionHandle,
   IntPtr ProcessHandle,
   ref IntPtr BaseAddress,
   uint ZeroBits,
   uint CommitSize,
   ref LARGE_INTEGER SectionOffset,
   ref uint ViewSize,
   SECTION_INHERIT InheritDisposition,
   uint AllocationType,
   uint Win32Protect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntmapviewofsection)
