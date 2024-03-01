## RtlSetProcessIsCritical

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int RtlSetProcessIsCritical(
   bool NewValue,
   bool RestoreValue,
   bool* OldValue,
   uint Flags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntsetinformationprocess)
