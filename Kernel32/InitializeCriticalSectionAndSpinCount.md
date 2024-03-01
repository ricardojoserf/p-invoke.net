## InitializeCriticalSectionAndSpinCount

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitializeCriticalSectionAndSpinCount(
   out CRITICAL_SECTION lpCriticalSection,
   uint dwSpinCount
);
```

Microsoft documentation: (TODO)
