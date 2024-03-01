## Tryentercriticalsection

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool TryEnterCriticalSection(
   [In,
   Out] ref CRITICAL_SECTION lpCriticalSection
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-tryentercriticalsection)
